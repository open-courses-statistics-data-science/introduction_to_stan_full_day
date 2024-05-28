# Introduction to Stan
This repository provides a half-day introduction to [Stan](https://mc-stan.org/).

The [lecture](presentations/introduction_to_stan.pdf) gives an introduction to [Hamiltonian Monte Carlo](https://www.youtube.com/watch?v=a-wydhEuAm0) (HMC) which forms the core foundation of Stan's inference algorithm; knowledge of HMC is also crucial to understanding how to code up Stan models. It then goes on to introduce the Stan language, walking through the coding up of Stan programmes and running them (from R).

The [problem set](problem_sets/introduction_to_stan_problem_sets.pdf) gives participants experience in coding up Stan programmes and performing posterior predictive checks of models using Stan. It also gives examples of how to fit discrete-parameter models in Stan. The data for the problem sets is [here](problem_sets/data). The answers to the problems are [here](problem_sets/introduction_to_stan_problem_sets_answers.pdf).

**Prerequisite knowledge:** programming experience in either R, Python or some other software which supports the use of Stan. Participants should also know the basics of Bayesian inference and how some of the simpler Markov chain Monte Carlo algorithms work. They should also have Stan installed and the software package necessary to call Stan from whatever software you use (e.g. for R, you need rstan installed; for Python, you need pystan installed); for installation instructions, consult the [Stan webpage](https://mc-stan.org/).
