---
layout: page
title: "ManyPrimates 1: Modeling Challenge"
permalink: /mp1/models
image: assets/images/pilot_phylo2.png
---

ManyPrimates is a collaborative network of researchers interested in primate cognition. We collect large datasets on primate cognition in order to investigate how cognitive abilities vary across species. These datasets are the basis for studying cognitive evolution in a quantitative way. 

Our first project - [ManyPrimates 1 (MP1)](/mp1) - tests short-term memory. The final dataset will include data from 400+ primates from 30+ species. As part of MP1 we want to test evolutionary hypotheses about short-term memory. That is, we want to examine which external (social, ecological) species level variables account for differences in short-term memory abilities between species. 

The number of potential predictors and models to consider are endless and there is no a priori way of determining which models and predictors make sense and which do not. The only way is to think through each model and its implications. The outcome of this process depends on theoretical views about what drives cognitive evolution.

To remain theoretically neutral, we want the community to select the models for consideration. We therefore announce the first **ManyPrimates modeling challenge**. We encourage everyone to spell out the process they think drives the evolution of short-term memory abilities and submit it to the challenge as a model.<sup>1</sup> All submitted models will enter into a model comparison.<sup>2</sup> The winning model(s) will be highlighted in the corresponding paper and the author(s) will be honored at the [ManyPrimates symposium](/symposium). 

There are different ways you can submit a model:

1. As a formula (e.g. `y ~ x + z`). This kind of submission makes it easy for us to translate the model to a statistical model. When submitting a formula, please make sure that you specify all variables in it. Example: `smt ~ tree_density`. This model assumes that short-term memory abilities (`smt`) in/decrease with tree density in the species natural habitat (`tree_density`). 
2. As graphical model ([DAG](https://en.wikipedia.org/wiki/Directed_acyclic_graph) or structural causal model). In addition to the formula, a causal model allows us to test additional causal implications.
3. As a verbal description: Here you simply spell out your model verbally. Example: “*Primates whose natural habitat has a lot of trees have better short-term memory*”. If you submit a verbal description, we will work together with you to translate it into a formula and/or a causal model.

If you submit a formula or a graphical model, please also include a short verbal description of the causal structure<sup>3</sup> and relevant references (if applicable). Models can include many variables and also interaction terms. In any case, it’s important that you specify how your predictors will be measured and how the necessary data can be obtained. In the example above, this could be “*number of trees per square mile*” with a link to a database that lists this information for all primates. 

Please submit your model to [{{ site.email }}](mailto:{{ site.email }}).

***

<p style="font-size: .75rem;">
<sup>1</sup> Only specify the species level <emph>external</emph> variables and their relations; all models will include a standard set of control predictors and will account for phylogeny.<br/>

<sup>2</sup> Models will be fit in a Bayesian framework and compared based on WAIC scores and weights - whenever a causal model is submitted, we will also compare models based on their testable implications (see e.g. Peters, Janzing & Schölkopf, 2017; Pearl, Glymour & Jewell, 2016).<br/>

<sup>3</sup> Please describe causal influences between predictors and outcome variables as well as causal relations between predictors (if there are multiple).<br/>
</p>