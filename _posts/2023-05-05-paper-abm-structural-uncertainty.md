---
title: "New Paper on Structural Uncertainty and Agent-Based Modeling"
subtitle: "Structural model choices regularly overshadow parametric uncertainty in agent-based simulations of household flood risk outcomes"
author: Vivek Srikrishnan
tags: news
category: people
layout: post
---

We have [a new paper](https://www.sciencedirect.com/science/article/pii/S019897152300042X) in [Computers, Environment, and Urban Systems](https://www.sciencedirect.com/journal/computers-environment-and-urban-systems) on the role of structural uncertainty in agent-based models (ABMs), specifically in the context of modeling household flood risk aversion. This paper was authored with several collaborators at Pacific Northwest National Laboratory, namely Jim Yoon, Heng Wan, Brent Daniel, and David Judi, and was funded as part of the Department of Energy's [Integrated Coastal Modeling](https://icom.pnnl.gov/) project.

The key question we sought to understand was the degree to which choices about the structure of agent decision rules pre-determined the range of possible outcomes that the model could produce. Structural uncertainty, which reflects the uncertainty in the mathematical and/or rule-based representation of processes, is [one of the central categories of uncertainties relevant to simulation models](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021EF002644). While meta-analyses can synthesize findings across these particular models, directly assessing the role of structural uncertainty can be difficult due to complex ABM dynamics and the lack of a common simulation setting. 

In this paper, we used a common model setup to look at three different model structural variations, related to changes in how agents respond to information about flood risk. We show:

* Structural changes in how flood risk changes agents' preferences about household location can greatly influence the variability in observed outcomes such as floodplain population and housing values;
* It is unlikely that careful calibration will fully avoid this problem, as different outputs of interest vary in different ways across model structures; calibration may align outputs for a particular metric used for calibration[^1], but create overconfidence about other modeled outcomes.

We conclude by suggesting that this strong influence of model structure on ABM outcomes emphasizes the need to view ABMs as tools to understand the implications of particular theories about decision-making and social evolution (in the tradition of ABMs as simulation tools for [generative social science](https://doi.org/10.1002/(SICI)1099-0526(199905/06)4:5<41::AID-CPLX9>3.0.CO;2-F)), rather than over-interpreting projections from any particular ABM.

[^1]: That is, assuming that a model structure is capable of reproducing the observations used to calibrate it!