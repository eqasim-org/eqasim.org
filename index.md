---
hide-toc: true
---

# eqasim

The *eqasim framework* helps you set up agent-based transport simulations based on [MATSim](https://matsim.org/) in a standardized way.

```{image} _static/synpop.png
:alt: Flows from a synthetic population
:align: right
:width: 33%
```

**Synthetic populations** are an important input to agent-based transport simulations, and eqasim provides processes based on open data and software to generate households, persons, and daily activity chains for a variety of regions:

- Any region or department in [France](https://github.com/eqasim-org/eqasim-france)
- The [Sao Paulo](https://github.com/eqasim-org/sao_paulo) Metropolitan region
- Any place in [California](https://github.com/eqasim-org/california)
- All [Bavaria](https://github.com/eqasim-org/bavaria) or smaller parts such as Munich
- [Switzerland](https://gitlab.ethz.ch/ivt-vpl/populations/ch-zh-synpop) which is currently only partly built using open-data

Read more about {doc}`eqasim-synpop <synpop>`!

<video class="align-right" style="width: 33%;" autoplay="" muted=""> <source src="_static/simulation.mp4" type="video/mp4"> Video of an agent-based simulation </video>

**Agent-based simulations** allow to explore new technologies, modes of transport, public policies, social trends and more including their economic, ecological and social impacts. We provide a streamlined distribution of the [MATSim](https://matsim.org/) framework with a couple of individual improvements and simplifications to quickly bootstrap such an agent-based simulation for the cases cited above.

Read more about {doc}`eqasim-java <java>`!


```{toctree}
:hidden:

synpop
java
community
events
```
