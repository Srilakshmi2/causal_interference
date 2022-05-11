### This module contains implementation of different causal interference models
1. Difference in difference
2. Synthetic control
3. Synthetic difference in difference
#### Background
Proposition 99 is an initiative statute & its primary effect is to impose a 25-cent per pack state excise tax on the sale of tobacco cigarettes within California, with approximately equivalent excise taxes similarly imposed on the retail sale of other commercial tobacco products, such as cigars and chewing tobacco.
#### Data overview
Used annual state-level panel data for the period 1970– 2000. Proposition 99 was passed in November 1988 and went into effect in January 1989, giving 19 years of preintervention data. Our sample period begins in 1970 because it is the first year for which data on cigarette sales are available for all control states. It ends in 2000 because at about this time anti-tobacco measures were implemented across many states, invalidating them as potential control units.
#### Difference in Difference (DID)
**Key Concept** <BR>
The DID is a powerful model which allows us to look at the effect of a policy intervention or experiment by taking into consideration:

* how a group mean changes before and after a policy intervention (treatment group) AND
* compare this change with the mean over time of a similar group which did not undergo the treatment (control group).
* All good difference-in-differences designs are based on some kind of natural experiment
  
#### The statistical model
In mathematical terms, we are interested in estimating 3 coefficients, as in the following equation:

  Y=β<sub>o</sub> + β<sub>1</sub>*Treatment + β<sub>2</sub>∗Post+β<sub>3</sub>∗Treatment∗Post + e

Where:

* Y is our outcome variable;
* Treatment is a dummy variable indicating the treatment (=1) and control (=0) group;
* Post is a dummy variable indicating pre (=0) and post (=1) treatment;
* Treatment * Post is a dummy variable indicating whether the outcome was observed in the treatment group AND it was observed after the intervention (=1), or any other case (=0).





  
