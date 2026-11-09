---
layout: default
title: Piotr Wilam
---

Interpretability of language models:<br>
how a model's representation of a language forms during training.

[GitHub](https://github.com/piotrwilam) · [LinkedIn](https://www.linkedin.com/in/piotrwilam) · [piotrwilam@gmail.com](mailto:piotrwilam@gmail.com)

---

## From measurement to mechanism

I have started with code, because the grammar of a programming language is known exactly, so every construct the model should learn can be listed before any measurement.

**A conjecture.** Activations hold far more than has been read from them. Two routes lead into them. One trains a second model on the activations — a probe, a sparse autoencoder, a crosscoder — and reads its features; it finds what nobody named. The other keeps the reading direct and declares the instrument in advance: what the model is shown, and the arithmetic that turns its activations into numbers. My conjecture is that the second route has been left early and goes much further: for any concept that can be named, a declared instrument reads more, and more can be named than has been. The first route does not replace it, because a learned instrument reorganises what the activations contain and no more.

**Making the reading a measurement.** The direct reading was left for good reasons: a neuron can mix meanings, a list of neurons has no threshold, readings did not transfer between studies. Paper \[1\] answers each of them. The population of prompts is declared: for every construct, every factor around it is drawn at its rate in a reference corpus. The battery is drawn twice, so every number carries a noise unit. The arithmetic is fixed before reading: one number per neuron, in units of the neuron's own spread on ordinary code, with the construct's token out of role subtracted. A set of checks says when the reading may be used, and its resolution across training checkpoints is measured. The result, a calibrated concept profile, is comparable across checkpoints and across models of the same architecture.

**Results.** Representational drift \[2\]: in one model read across two trillion tokens, the loss at a construct's positions reaches its floor in the beginning of training; the neurons that carry the construct never settle, and the model relies on the current ones more and more. No deeper, no later \[3\]: composed constructs wire no deeper and no later than atomic ones — found in the MSc, now being repeated on calibrated concept profiles (in progress). Next: what is stable when the carriers are not — a small core and a wide drifting fringe.

**The direction.** Basics first: an instrument — calibrated batteries leading to calibrated readings — then observations that are measurements. From observations to a first iteration of mechanisms: from which neurons carry a construct to how the model computes it. Then natural language, other models, small LLMs trained from scratch. This is the route from the MSc towards a PhD. All of this is one part of a larger question: how the computations of a language model work.

---

## Papers

\[1\] *Calibrated concept profiles: making the reading of a model's neurons a measurement.* arXiv 2611.09196, 2026. [arXiv](https://arxiv.org/abs/2611.09196) · [PDF](/papers/calibrated-concept-profiles.pdf) · [repo](https://github.com/piotrwilam/AtlasCalibratedConceptProfiles) · [data](https://huggingface.co/datasets/piotrwilam/AtlasOpenCoder)

\[2\] *Representational drift in a code model: behaviour settles, which neurons carry it does not.* arXiv 2611.09204, 2026. [arXiv](https://arxiv.org/abs/2611.09204) · [PDF](/papers/representational-drift.pdf) · [repo](https://github.com/piotrwilam/AtlasRepresentationalDrift)

\[3\] *Grammatical composition does not order the circuits of a code model: depth and formation time across training.* MSc dissertation, UCL, 2026. [PDF](https://github.com/piotrwilam/No-Deeper-No-Later/releases/download/msc-submission/Piotr-Wilam_MSc_dissertation.pdf) · [repo](https://github.com/piotrwilam/No-Deeper-No-Later)

\[4\] *What, Where, and How: Disentangling the Roles of Task, Language, and Model in Code Model Representations.* arXiv 2607.21491, 2026. [arXiv](https://arxiv.org/abs/2607.21491) · [repo](https://github.com/piotrwilam/Atlas2x2)

---

## Path

- MSc in the philosophy and physics programme, KUL, Poland.
- MSc in differential geometry, University of Oxford, supervised by Roger Penrose.
- Left the DPhil in the 1990s to found Onet.pl, a unicorn, Poland's first internet portal; its first CEO.
- Partner at Innovation Nest, an early-stage venture fund; investments in software companies in Poland and across Europe, co-invested with Y Combinator, Seedcamp, a16z, SignalFire and Khosla Ventures.
- 2025: enrolled at UCL to study the models from inside. MSc in Computational Statistics and Machine Learning, 2026, supervised by Ehsan Shareghi.
- Now: the research above, towards a PhD.

---

## Interests

Two questions sit behind the research. What is language, as an entity — one instance of a more general mathematical object? And how does language fit the bigger picture: world, world model, subjects, sensations, consciousness?

---

## Beyond research

Recent reading and inspirations: Ted Chiang, *Exhalation*; Ray Nayler, *The Mountain in the Sea*; David Deutsch, *The Beginning of Infinity*.

Over sixty countries visited; my entrepreneurial experience includes publishing travel guides.

Yoga and dancing, from contact improvisation to tango.

Family and children.
