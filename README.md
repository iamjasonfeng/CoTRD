# CoTRD

[PDF](https://iamjasonfeng.github.io/CoTRD/chain_of_thought_reinforcement_decoding.pdf)

Abstract

Chain-of-Thought Reinforcement Decoding (CoTRD) is one of my solutions for the ARC-AGI 3 Kaggle
competition. CoTRD is a test-time decoding method designed to increase the influence of an agent's
previous reasoning on its next response without weight updates, an external reward model, or a symbolic
representation of the task. It measures how the model's output changes when its previous reasoning is
removed, then uses that difference during decoding. This paper documents three implementations in the
following order: CoTRD (Full CAD), CoTRD Enhanced, and CoTRD Standard. It merely documents
CoTRD and does not present or compare scores.
