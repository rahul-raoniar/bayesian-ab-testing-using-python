# Bayesian A/B Testing and building an interactive widgets using ipywidgets

`Tools used`: python 3.9, numpy, pandas, math, scipy, random, matplotlib, seaborn and ipywidgets

`Table of Contents`:
* Bayesian A/B Testing
* Monte Carlo Simulation
* Interactive web application

`Step by step code implementation`:

1. Two variants of emails are sent to users. One without and one with image to randomly picked users
2. Beta distribution (continuous) has been utilise to identifying the probabilities of seeing a particular number of success (clicked) and failures (do not click)
3. The bayesian A/B testing simulated using a Monte Carlo Simulation to check in how many worlds the `B` variant is better than A variant.
4. Calculated how much better is each `B` variant than each variant `A`.
5. Generating an interactive app to illustrate the bayesian A/B testing using ipywidgets.
