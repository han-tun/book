# Inference and Decision-Making with Multiple Parameters

This chapter is focused on the extending the Normal-Normal
conjugate family introduced in \@ref(sec:normal-normal)
to the problem of inference in a Normal population with an unknown
mean and variance.  We will introduce the Normal-Gamma conjugate
family for inference about the unknown mean and variance and will
present Monte Carlo simulation for inference about functions of the
parameters as well as sampling from predictive distributions, which
can assist with prior elucidation. For situations when limited prior
information is available, we discuss a limiting case of the
Normal-Gamma conjugate family, leading to priors that can be used for
a reference analysis.  Finally, we will show how to create a more
flexible and robust prior distribution by using  mixtures of the
Normal-Gamma conjugate prior.
For inference in this case we will introduce Markov Chain Monte Carlo,
a powerful simulation method for Bayesian inference.

It is assumed that the readers have mastered the concepts of
one-parameter Normal-Normal conjugate priors.
Calculus is not required for this section; however,
for those who are comfortable with calculus and would like to go
deeper, we shall present optional sections with more details
on the derivations.