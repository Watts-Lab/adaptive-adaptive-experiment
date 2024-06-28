# Adaptive adaptive experiments
### Adaptive experiments in which the design space adapts over time

A simplified description of an adaptive experiment is a setting in which design space features are used to decide which treatments are conducted in the space of possible experiments. The experiment sampling adapts to the results of trials via techniques like Bayesian optimization of a Gaussian process set up to maximize knowledge about the entire space of possible experiments. However, this setup is contingent on the commensurability of the underlying space as it evolves. In practice, this constraint is significant — as we develop our understanding of the world, the design space of possible experiments doesn't just get bigger; it changes in fundamental ways. 

This project aims to provide techniques to continue to learn close to optimally by running future experiments, even when the underlying design space has changed between experiments in a way that means earlier trials are no longer directly commensurable or informative.
