---
permalink: /diffusionbayes/
title: "DiffusionBayes.jl"
excerpt: "About the software DiffusionBayes.jl."
---
[DiffusionBayes.jl](https://github.com/JuliaDiffusionBayes/DiffusionBayes.jl) is an open source, user-friendly and efficient software written in [Julia](https://julialang.org/) for conducting statistical analysis for diffusion processes.

All [Case studies](/case-studies/) have been conducted with this software.


[DiffusionBayes.jl](https://github.com/JuliaDiffusionBayes/DiffusionBayes.jl) is in fact an umbrella package that collects multiple modular packages, each responsible for a different aspect of working with diffusion processes. It comprises of the following:
- [DiffusionDefinition.jl](https://juliadiffusionbayes.github.io/DiffusionDefinition.jl/dev/)
  - makes it possible to define diffusion processes and sample from their laws
- [ObservationSchemes.jl](https://juliadiffusionbayes.github.io/ObservationSchemes.jl/dev/)
  - provides a systematic way of encoding discrete-time observations for stochastic processes
- [GuidedProposals.jl](https://juliadiffusionbayes.github.io/GuidedProposals.jl/dev/)
  - is responsible for defining and sampling conditioned diffusion processes
- [ExtensibleMCMC.jl](https://juliadiffusionbayes.github.io/ExtensibleMCMC.jl/dev/)
  - a modular implementation of the Markov chain Monte Carlo (MCMC) algorithms
- [DiffusionMCMC.jl](https://juliadiffusionbayes.github.io/DiffusionMCMC.jl/dev/)
  - Markov chain Monte Carlo (MCMC) algorithms for doing inference for diffusion processes
- [ExtensibleMCMCPlots.jl](https://juliadiffusionbayes.github.io/ExtensibleMCMCPlots.jl/dev/)
  - plotting extensions for [ExtensibleMCMC.jl](https://juliadiffusionbayes.github.io/ExtensibleMCMC.jl/dev/)
- [DiffusionMCMCPlots.jl](https://juliadiffusionbayes.github.io/DiffusionMCMCPlots.jl/dev/)
  - plotting extensions for [DiffusionMCMC.jl](https://juliadiffusionbayes.github.io/DiffusionMCMC.jl/dev/)
- [DiffusionAnim.jl](https://juliadiffusionbayes.github.io/DiffusionAnim.jl/dev/)
  - Pedagogical animations with [Makie.jl](https://github.com/JuliaPlots/Makie.jl)


Each individual package may be used on its own---simply follow the links to view the full documentation for each package.

However, for the majority of users it is most convenient to use [DiffusionBayes.jl](https://github.com/JuliaDiffusionBayes/DiffusionBayes.jl) as an entry point. The page contains (not yet, will in the future) explanations about interrelations of costituent packages and how to get started depending on what the intended use of this software is. [DiffusionBayes.jl](https://github.com/JuliaDiffusionBayes/DiffusionBayes.jl) imports all functionalities that the individual packages do and is thus the easiest to work with; however, some constituent packages have relatively heavy dependencies, so advanced users might prefer to load only packages they need. See [DiffusionBayes.jl](https://github.com/JuliaDiffusionBayes/DiffusionBayes.jl) for more info.