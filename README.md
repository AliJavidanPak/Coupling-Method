# The Coupling Method: Building a Bridge Between Random Worlds

A theoretical and computational study of coupling methods in probability theory, with applications to distributional comparison, cryptography, and Markov-chain convergence.

The project begins with the total variation distance as a quantitative measure of the difference between two discrete probability distributions. The equivalence between its standard definition and its one-sided formulation is derived explicitly and verified numerically.

The central part of the project develops the coupling method. A coupling is introduced as a joint distribution whose marginals are two prescribed distributions, providing a common probabilistic framework in which the two random variables can be compared. The coupling inequality

$$P(X\neq Y)\geq \|p-q\|_{\mathrm{TV}}$$

is derived, followed by the construction of an optimal coupling that attains equality. The optimal sampling procedure is implemented numerically and tested using Monte Carlo sampling, reproducing the theoretical total variation distance.

The method is then applied to a cryptographic problem: transforming a system satisfying strong secrecy into one satisfying perfect secrecy. Using an optimal coupling between the joint message–ciphertext distribution and the product of its marginals, the project proves perfect secrecy and derives the bound

$$P(\mathrm{error}_{\mathrm{new}})\leq \delta+\epsilon.$$

Finally, coupling is applied to Markov-chain convergence. A two-state weather model is used to study stationary distributions, coupled trajectories, and meeting times. Numerical simulations illustrate how rapid coupling corresponds to forgetting the initial state and hence to rapid convergence toward the stationary distribution.

The project combines probability theory, rigorous derivations, stochastic simulation, and applications to information theory and Markov processes.
