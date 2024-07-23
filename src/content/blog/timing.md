---
title: The importance of timing, as told by a rainbow.
author: Marwan
pubDatetime: 2024-07-23T21:15:00Z
slug: timing
featured: false
draft: true
tags:
  - physics
  - ablation loading
  - films
description: What lesson the film Blue Valentine taught me, and which I applied to ablation loading of trapped ions for quantum computers.
---

Timing is key.

Let [Blue Valentine (2010)](https://www.imdb.com/title/tt1120985/) demonstrate. Here, a well-timed rainbow transforms a bus carrying Dean and Cindy (Ryan Gosling and Michelle Williams) into an allegory for their relationship:

![rainbow-left](@assets/images/timing/rainbow-left.png)
![rainbow-right](@assets/images/timing/rainbow-right.png)

_What a shot._ How often can you follow one end of the rainbow to the other in one continuous shot? Serendipity in abundance. But not to sell Derek Cianfrance's direction short: it takes a lot of work and skill to execute this well. (I won't spoil the rest of the film.)

It's difficult to plan these moments. In fact, that's sometimes also true for science—much as we try. And so, here's how Blue Valentine ties in with ablation loading.

---

At [eleQtron](https://eleqtron.com/), a spinoff from [Universität Siegen](https://www.physik.uni-siegen.de/quantenoptik/index.xml.en?lang=en) building trapped ion quantum computers, we collaborated (and continue to collaborate) with the University closely. We would go for pulsed laser ablation loading of ions, our path determined mainly by us wanting cryostatic cooling for better vacuum quality and thus longer trapping times. This excluded using the typical resistive atomic ovens/dispensers, since they typically produce too much heat for the cryostat to work.

Our University colleagues had already sorted the initial design of the ablation target and material. They had a CAD model of a vacuum chamber, and a pulsed laser on the way. But the optical table was empty, and we didn't have a finished plan.

Our lucky moment was that I put no thought whatsoever into choosing the optimal target material form when starting to work on the project. We just wanted to load Ytterbium. So we started out straight away with Ytterbium metal in a hole, and thus were able to load relatively efficiently.

The material form is important because Ytterbium oxidises in air. That makes it annoying to work with when you put it in vacuum, because you have to break the oxide layer with high energy pulses upon first use, spraying debris all over the trap and reducing its performance.[^1] One possibility is to use a compound form, such as YbCl<sub>3</sub>, that doesn't oxidise.[^2] But, if we extrapolate from [Barium loading research](https://doi.org/10.1063/5.0149778), then it looks like we'd be trading one problem for another, because it takes orders of magnitude more pulse energy to break the atoms free from the compound when ablating. That energy goes partly to the ablated atoms, making them travel faster and thus harder to trap. Overall, compound forms may actually be less efficient to load with.

If we'd have started from a completely finished plan, then we may not have considered the optimal material choice, because we'd likely have assumed the people before us had solved that problem. (Word of warning: the latter happens way too often in physics).

If we'd started from nothing, we'd have gotten bogged down by things that didn't matter as much. Overthinking often yields suboptimal results.

All things considered, the timing of when I started working on ablation loading was perfect. That timing was our 'Blue Valentine' moment. We couldn't have planned that.

Overarching point is, solutions in science are sometimes stumbled upon. We often want to progressively lead to it, or at least try. But, "[Luck is what happens when preparation meets opportunity](https://en.wikiquote.org/wiki/Seneca_the_Younger#Disputed)". So, perhaps something I learned is that if we prepare ahead to make the timings work in our favour better, we can get us over these technical hurdles by doing _less_ work. Kind of like how time is often an effective doctor.

---

[^1]: The same problem happens with atomic dispensers, but you can keep them much further away from the trap chip to avoid this problem.
[^2]: At least, I _think_ YbCl<sub>3</sub> doesn't oxidise readily in air.
