---
layout: page
title: "ManyPrimates 1: Modeling Challenge"
permalink: /mp1/models
image: assets/images/pilot_phylo2.png
---

## What drives the evolution of short-term memory abilities?

As part of the [ManyPrimates 1 project](/mp1) we want to test evolutionary hypotheses about short-term memory. That is, we want to examine which external (social, ecological) species level variables account for differences in short-term memory abilities between species. 

The number of potential predictors and models to consider are endless and there is no a priori way of determining which models and predictors make sense and which do not. The only way is to think through each model and its implications. The outcome of this process depends on theoretical views about what drives cognitive evolution.

To remain theoretically neutral, we want the community to select the models for consideration. We therefore announce the first **ManyPrimates modeling challenge**. We encourage everyone to spell out the process they think drives the evolution of short-term memory abilities and submit it to the challenge as a formal model. All submitted models will enter into a model comparison.<sup>1</sup> The winning model(s) will be highlighted in the corresponding paper and the author(s) will be honored at the ManyPrimates symposium in July 2020. 

Please submit your model<sup>2</sup> either as a formula (e.g. y ~ x + z) and/or a graphical model ([DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph) or structural causal model) to [{{ site.email }}](mailto:{{ site.email }}) together with a brief verbal description of the causal structure<sup>3</sup> and relevant references (if applicable). In addition, please list all predictors you want to include and specify how they should be measured or from which databases they could be obtained. We will accept models until March 31st, 2020.

***

<p style="font-size: .75rem;">
<sup>1</sup> Models will be fit in a Bayesian framework and compared based on WAIC scores and weights - whenever a causal model is submitted, we will also compare models based on their testable implications (see e.g. Peters, Janzing & Schölkopf, 2017; Pearl, Glymour & Jewell, 2016).<br/>

<sup>2</sup> Only specify which species level external variables and their relation, all models will include a standard set of control predictors and will account for phylogeny.<br/>

<sup>3</sup> Please describe causal influences between predictors and outcome variables as well as causal relations between predictors (if there are multiple).<br/>
</p>