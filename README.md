# polysemantic-feature-disambiguation

In this notebook I explore how a small one layer language model disambiguates activations from a polysemantic neuron. I find that a small set of context-dependent neurons either cancel or reinforce the polysemantic neuron’s contribution so that the final residual stream points toward the correct next token. Furthermore, ablating the context-specific neuron set shifts the model’s next-token predictions in the expected direction.
