---
layout: article
title:  "Current project: locomotion BMI driven by cortical dynamics"
excerpt: "A novel locomotion prosthesis system."
categories: research
share: false
image:
  teaser: pedal_thumb.png
  
---

I am currently working with graduate student Sean Perkins on a novel locomotion prosthesis system, with applications to wheelchair
control, exoskeletons, and other prosthetic devices. 

<img src="https://karschro.github.io/images/pedal_thumb.png" class="image-right"> 

This work is not yet published, so stay tuned.

Abstract:

Brain-machine interfaces (BMIs) for reaching have enjoyed continued performance improvements, allowing remarkable
2D cursor control. Yet there remains significant clinical need for locomotor (e.g., wheelchair control)
BMIs, which could benefit a larger patient population. Fewer studies have addressed this need, and the best
strategy for doing so remains undetermined. Here we demonstrate an approach based upon rhythmic neural activity.
We leverage a behavioral task wherein monkeys cycle a hand-held pedal, forward or backward, to advance
along a virtual track, pausing on targets for reward. This task does not emulate natural locomotion, but rather
provides a view of cortical activity during learned, voluntary, rhythmic movement. Such activity is robust and was
recently characterized (Russo et al. 2018), affording opportunities to develop novel decode algorithms and test
them in an online setting.

We constructed a decoder that decoded virtual self-motion, based on recordings from 192 electrodes implanted
in motor cortex. Unlike algorithms for cursor control, we did not directly map neural states to commanded velocity
or position. Instead, we leveraged the most robust aspects of response structure: an overall shift in neural
state when moving versus stationary, and rotations of the neural state while cycling. We used these features
to decode when the subject was moving, and decoded direction based on the finding that neural-state rotations
occur in different planes during forward versus backward cycling. Perhaps because the subject need not learn
a novel mapping to control the BMI, performance was high even during the first few sessions of brain control.
An additional performance gain was obtained by leveraging a neural dimension that reflected cycling direction at
movement initiation. Resulting brain-control success rates were very close to those achieved under arm-control.
Thus, rhythmic neural activity provides a robust substrate for BMI control, but requires different decode strategies
than have been employed previously.
