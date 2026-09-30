---
title: "Research"
date: 2026-09-30
draft: false
showDate: false
showReadingTime: false
showAuthor: false
---

## Research Overview

My research is in **theoretical nuclear astrophysics**, with a focus on understanding the origins of heavy elements in the universe through nucleosynthesis processes occurring in extreme astrophysical environments such as neutron star mergers and core-collapse supernovae.

I combine nuclear theory, astrophysical simulations, and machine learning to connect properties of exotic nuclei with observable r-process signatures. My work uses nuclear mass models, beta-decay and reaction-rate calculations, reaction-network modeling, and data-driven methods to understand how nuclear uncertainties shape the elemental abundances observed in the Solar System and in metal-poor stars. 

## Research Interests

<div class="research-interest-grid">
<div class="research-interest-copy">

**Nucleosynthesis And R-Process Observables**

The rapid neutron-capture process (r-process) produces roughly half of the elements heavier than iron, including gold, platinum, thorium, and uranium. It occurs in extremely neutron-rich environments, where nuclei capture neutrons faster than they undergo beta decay. The resulting abundance pattern depends on both the astrophysical conditions and the nuclear properties that govern these reactions. I compare predicted patterns with the Solar System abundance pattern and observations of metal-poor stars to investigate the conditions that produced them.

</div>
{{< research-figure src="img/r-process.png" alt="Simulated r-process abundance distribution across the nuclear chart" caption="The abundance distribution across the nuclear chart, with an inset showing the resulting r-process abundance pattern compared to solar." >}}
</div>

<div class="research-interest-grid">
<div class="research-interest-copy">

**Metal-Poor Stars And Enrichment Fingerprints**

Metal-poor stars formed from gas containing relatively little iron and other elements heavier than helium. Their compositions preserve traces of earlier nucleosynthesis and offer clues about the stars and explosive events that enriched their birth material. I simulate element production under different astrophysical and nuclear-physics assumptions and compare the results with observed abundance patterns, including that of HD 222925, to identify plausible enrichment histories and constrain the nuclear inputs.

</div>
{{< research-figure src="img/pic_metal_poor_star.png" alt="HD 222925 abundance pattern compared with MDN and PF model predictions" caption="Observed elemental abundances in HD 222925 are compared with predictions from selected mass models using MDN and PF methods. The comparison shows how stellar abundance patterns can preserve clues to earlier enrichment and test nuclear physics." >}}
</div>

<div class="research-interest-grid">
<div class="research-interest-copy">

**Exotic Nuclear Properties**

Many nuclei important to heavy-element production are short-lived and difficult to study directly in the laboratory, yet they are created in extreme astrophysical environments. Their masses and decay rates shape nucleosynthesis pathways and final element abundances. I develop and evaluate predictions for these exotic nuclei, including machine-learning models of their masses and beta-decay half-lives. I use these predictions in r-process simulations and compare the resulting abundance patterns with astrophysical observations to constrain nuclear properties beyond current experimental reach.

</div>
{{< research-figure src="img/pic_nuclear_properties.png" alt="Nuclear chart showing measured and predicted nuclear properties" caption="The nuclear chart highlights measured nuclides and regions where fission, decay, and capture properties must be predicted." >}}
</div>

<div class="research-interest-grid">
<div class="research-interest-copy">

**Nuclear Reaction Networks**

Nucleosynthesis networks represent how thousands of nuclei are connected through neutron capture, photodissociation, beta decay, alpha decay, and fission. These reactions compete as explosive ejecta expand and cool. To understand how each nucleus contributes to the evolving abundance pattern, I developed GrRproc, a graph-based r-process network that tracks material flow between nuclei over successive time steps. This helps identify which reactions and pathways govern the production of specific elements.

</div>
{{< research-figure src="img/pic_reaction_network.png" alt="Reaction-network diagram connecting nuclei across two time steps" caption="A schematic of the reaction network linking nuclear populations from one simulation time step to the next." >}}
</div>

<div class="research-interest-grid">
<div class="research-interest-copy">

**Machine Learning And Uncertainty Quantification**

Measurements of nuclei far from stability are scarce, and different nuclear models can produce substantially different predictions. I use Mixture Density Networks to represent model predictions and multi-objective optimization to identify solutions on the Pareto front. By comparing these predictions with astrophysical observables, I assess and constrain uncertainties in nuclear properties and their impact on nucleosynthesis.

</div>
{{< research-figure src="img/pic_ml_uq.png" alt="Neutron separation energy predictions for Z = 50 with experimental data and model uncertainty" caption="For Z = 50, predicted neutron separation energies are compared with AME2020 measurements, alongside uncertainty estimates from two groups of ML models." >}}
</div>

<div class="research-interest-grid">
<div class="research-interest-copy">

**Modeling Kilonova Observables**

Neutron-star mergers eject hot, neutron-rich matter whose radioactive decay powers a kilonova. I use simulated light curves to investigate how uncertainties in nuclear properties, particularly beta-decay rates, affect the predicted brightness over time.

</div>
{{< research-figure src="img/pic_lc.png" alt="Simulated kilonova luminosity over time, with a one-sigma uncertainty band and variation across seeds" caption="The mean simulated luminosity and one-sigma uncertainty band show how beta-decay and seed variations (training data sets) affect a neutron-star-merger kilonova over time." >}}
</div>

<!-- ## Current Projects

*Add descriptions of your current projects here.* -->

<!-- ## Collaborators

- [Rebecca Surman](https://surman.nd.edu/) — University of Notre Dame
- [Dan Kasen](https://kastatic.net/) — UC Berkeley
- [Gail McLaughlin](https://physics.sciences.ncsu.edu/people/gcmclaug/) — NC State University
- [Bradley Meyer](https://sites.google.com/view/bfmeyer) — Clemson University -->
