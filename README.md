# C.-elegans_locomotive_simulator
Ready to install and run MatLab app that simulates the forward and backward locomotive neural network dynamics with multiple control variables.
![alt text](Example.png?raw=true)
The user can specify the type of networks used (electron micrograph connectivity produced by Varshney [1], left-right symmetrized, fully symmetrized [2]) for the forward+backward network system as well as the type for the inter-connectivity between these two. It is possible to specify the type of weights used for the connectivity (binary or integer) and the ability to randomly alter these, normalize the in-degree of each neuron for both types of interactions, the initial distribution of voltages, type of model used for the chemical synapses interactions, strength of the gap junctions and chemical synapses interactions and more. Eve more one is able to specify which neurons receive a static input current, the amplitude and frequency of an undulatory input and a Gaussian random walk input.
After the simulation has concluded the app also calculates the level of synchronicity (LoS) as per the equation below for the pair of neurons for each of the two networks for the last second of simulation time.

![alt text](LoS.png?raw=true)
--------------
[1] Lav R Varshney, Beth L Chen, Eric Paniagua, David H Hall, and Dmitri B Chklovskii. Structural properties of the caenorhabditis elegans neuronal network. PLoS computational biology, 7(2):e1001066, 2011

[2] Flaviano Morone and Hernan A Makse. Symmetry group factorization reveals the structure-function relation in the neural connectome of caenorhabditis elegans. Nature communications, 10(1):1–13, 2019

Bryan E. Avila
