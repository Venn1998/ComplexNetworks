# ComplexNetworks

Simple projects to understand concepts from the Complex Network course at UOC


* In 1_StructuralDescriptors are investigated different structural descriptors for many networks provided by the professor (in the A1-networks folder).
After this, to analyze the degree distribution of the networks, we plot the Probability Distribution Function, Cumulative Distribution Function and Complementary CDF for each network, in lin-lin or log-log scale, depending on the properties of the degree distribution.


* In 2_Models I implemented many generators of complex networks models: 
  - Erdös-Rényi (ER) networks, either G(N,K) or G(N,p)
  - Watts-Strogatz (WS) small-world model
  - Barabási & Albert (BA) preferential attachment model
  - Configuration Model (CM)

  There's also an estimation of the exponent for the empirical degree distributions of BA and CM (SF).


* In 3_CommunityDetection I tried many community detection algoithms on different networks. Then I compared the results obtained with some reference clusterings uisng as metrics Jaccard Index, Normalized Mutual Information (arithmetic normalization), and Normalized Variation of Information. 


* In 4_Dynamics I implemented a Monte Carlo simulation of an epidemic spreading dynamics in complex networks, using the SIS model in which each node represents an individual which can be in two possible state: Susceptible (S), i.e. healthy but can get infected; Infected (I), i.e. has the disease and can spread it to the neighbors.
I calculated the fraction of infected nodes, ρ, in the stationay state, as a function of the infection probability of the disease β, for different values of the recovery probability μ. This was done on different undirected networks (e.g. Erdös-Rényi, scale-free, real), different sizes, average degrees, exponents, etc.
Moreover, the ρ(β) result obtained from Monte Carlo simulations was compared with the theoretical prediction provided by the Microscopic Markov Chain Approach (MMCA) model.


