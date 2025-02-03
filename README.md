# Computational Neuroscience Project

I'm a beginner in computational neuroscience and programming. In this project, I'm exploring neuron simulations using **Brian2**—a free and open-source simulator for spiking neural networks written in Python. I discovered Brian2 through its [documentation](http://brian2.readthedocs.io/) and have been following the "Introduction to Brian – Part 1: Neurons" tutorial.

## What I've Learned So Far

- **Brian2 Basics:**
  - Creating basic neuron simulations by defining differential equations.
  - Implementing spiking behavior by setting a threshold (e.g., when the neuron's variable exceeds a certain value, it fires a spike) and resetting the variable afterward.
  - Recording simulation data using `StateMonitor` and `SpikeMonitor` to capture the evolution of the neuron's variable and spike timings.
  - Plotting simulation results with matplotlib to visualize the evolution of neuron states.
  - Adding refractory periods to the neuron model so that after a spike, the neuron remains inactive for a short period.
  - Simulating multiple neurons and creating raster plots to visualize the spiking activity across a population.
  - Incorporating noise into the neuron models to simulate more realistic behavior.

## References

I learned these concepts from the Brian2 documentation and by following the "Introduction to Brian – Part 1: Neurons" tutorial, which can be found at [Brian2 Documentation](http://brian2.readthedocs.io/).

Additionally, the Brian2 developers suggest that if you use Brian2 in published research, you cite the following paper:

Stimberg, M, Brette, R, Goodman, DFM. “Brian 2, an Intuitive and Efficient Neural Simulator.” *eLife* 8 (2019): e47314. doi: [10.7554/eLife.47314](https://doi.org/10.7554/eLife.47314).

## Future Plans

In the coming days, I plan to expand this project by:
- Exploring more advanced neuron models (including dynamic thresholds and synaptic interactions).
- Enhancing data analysis and visualization techniques.
- Integrating additional computational neuroscience tools and methods into my simulations.

This repository is a personal learning portfolio that I will update regularly as I progress in my studies.

---

*Note: This project is a work in progress, and I welcome feedback and suggestions as I continue to learn and experiment.*
