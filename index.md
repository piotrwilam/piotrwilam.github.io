---
layout: default
title: Piotr Wilam
---

Interpretability of language models — how a model's representation of a language forms during training.

[GitHub](https://github.com/piotrwilam) · [LinkedIn](https://www.linkedin.com/in/piotrwilam) · [piotrwilam@gmail.com](mailto:piotrwilam@gmail.com)

---

## From measurement to mechanism

I have started with code, because the grammar of a programming language is known exactly, so every construct the model should learn can be listed before any measurement.

**A conjecture.** The activations of a model's own neurons are the model's primary reaction to its input, and the primary object to read. Probes, sparse autoencoders and crosscoders are instruments trained on top of that object; they are useful when they are checked against it. I hold this as a working conjecture, not a result. The conjecture would be wrong if learned features turned out to be followable across training where neurons are not.

**Making the reading a measurement.** The field left direct reading for good reasons: a neuron can mix meanings, a list of neurons has no threshold, readings did not transfer between studies. The first paper below turns the direct reading into a measurement. The population of stimuli is declared, so a reading is of something stated. The battery is drawn twice, so every number carries a noise unit. A set of checks says when the reading may be used, and its resolution across training checkpoints is measured. The result is a calibrated concept profile: one number per neuron per construct, comparable across checkpoints and models.

**Results.** Representational drift: in one model read across two trillion tokens, the loss at a construct's positions reaches its floor in the first 4% of training; the neurons that carry the construct never settle, and the model relies on the current ones more and more. No deeper, no later: composed constructs wire no deeper and no later than atomic ones — found in the MSc, now being repeated on calibrated concept profiles (in progress). Next: what is stable when the carriers are not — a small core and a wide drifting fringe.

**The direction.** Basics first: an instrument — calibrated batteries leading to calibrated readings — then observations that are measurements. From observations to a first iteration of mechanisms: from which neurons carry a construct to how the model computes it. Then natural language, other models, small LLMs trained from scratch. This is the route from the MSc towards a PhD. Behind it is the big question: how the computations of LLMs work.

## Papers

- *Calibrated concept profiles: making the reading of a model's neurons a measurement.* arXiv, 2026. [repository](https://github.com/piotrwilam/AtlasCalibratedConceptProfiles) · [dataset: battery and profiles](https://huggingface.co/datasets/piotrwilam/AtlasOpenCoder)
- *Representational drift in a code model: behaviour settles, which neurons carry it does not.* arXiv, 2026. [repository](https://github.com/piotrwilam/AtlasRepresentationalDrift)
- *Grammatical composition does not order the circuits of a code model: depth and formation time across training.* MSc dissertation, UCL, 2026. [code and data](https://github.com/piotrwilam/No-Deeper-No-Later)
- *What, Where, and How: Disentangling the Roles of Task, Language, and Model in Code Model Representations.* arXiv 2607.21491, 2026. [arXiv](https://arxiv.org/abs/2607.21491) · [repository](https://github.com/piotrwilam/Atlas2x2)

---

## Path

- MSc in the philosophy and physics programme, KUL (Catholic University of Lublin), Poland.
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
