# Heterosynaptic Cooperativity in Pair-based Spike-Timing-Dependent Plasticity (STDP)

## _Abstract_

Neurons are connected by points of contact, known as synapses. A fundamental property of such a synapse is that the strength of the connection it represents is plastic rather than static. In other words, each synapse has a weight associated with it, which represents the strength of the connection between the presynaptic and postsynaptic neuron, and these weights are subject to change owing to the activity pattern of the two neurons. This dynamic characteristic of synapses is termed plasticity.

Experimentally, we can distinguish between to forms of plasticity: homosynaptic and heterosynaptic plasticity. The two forms differ in their requirement of presynaptic activity during induction. Homosynaptic plasticity is induced in synapses whose presynaptic neurons are directly involved in the plasticity induction process whereas the heterosynaptic case is associated with synapses of presynaptic neurons that are not involved in the induction [ 5 ].

In our work, we review existing literature on heterosynaptic plasticity, including experimental_ evidence as well as the potential roles of this form of plasticity. Furthermore, we use an experimental study to device models of heterosynaptic plasticity to investigate synapse-level implications of this form of plasticity [ 28 ].

In order to investigate the effects of our heterosynaptic plasticity mechanism, we use classical, pair-based STDP rules to induce homosynaptic plasticity and augment the STDP to account for the heterosynaptic effects. We use different simulation setups to obtain insights into suitable STDP kernels for heterosyanptically-active neurons as well to analyse spatial patterns that emerge along dendrites due to specific configurations of initial synaptic weights. We implemented a framework for heterosynaptic plasticity into our existing program for spiking network models to facilitate our simulations. Additionally, an important design goal of the framework was to allow rapid extendibility in terms of new heterosynaptic rules as more experimental or theoretical data on the topic comes to surface.
