---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---
---
## Chapters

**[Finite-sample inference and nonstandard asymptotics with Monte Carlo tests and R](https://doi.org/10.1016/bs.host.2019.05.001)**  
with Jean-Marie Dufour
_Handbook of Statistics
Volume 41, 2019, Pages 3-31_
>We review the concept of Monte Carlo test as a simulation-based inference procedure which allows one to construct tests with provably exact levels in situations where the distribution of a test statistic is difficult to establish but can be simulated. The number of simulations required can be extremely small, as low as 19 to run a test with level 0.05. We discuss three extensions of the method: (1) a randomized tie-breaking technique which allows one to use test statistics with discrete null distributions, without further information on the mass points; (2) an extension (maximized Monte Carlo tests) which yields provably valid tests when the test statistic depends on a (finite) number of nuisance parameters; (3) an asymptotic version which allows one to get asymptotically valid tests without any need to establish an asymptotic distribution. As the method is computer intensive, we describe an R package (MaxMC) that allows one to implement this type of procedure. A number of special cases and applications are discussed.

## Works in Progress

**Judge Influence and Judicial Network**
>I establish a set of stylized facts regarding the consumption insurance role of homeownership.  Using the Panel Study of Income Dynamics, I first show that the decline in nondurable consumption among owners during periods of low earnings is less than one-third the size of the consumption decrease of renters under equivalent circumstances.  Next, I demonstrate that increased borrowing collateralized by the primary residence, or equity extraction, can account for the aforementioned consumption response of owners.  Conditioning on an owner's initial stock of liquid savings is crucial: the consumption responses of equity extractors and non-extractors among the subset of owners with relatively high levels of liquid assets do not exhibit any significant difference.  These findings suggest that the self-insurance role of homeownership is more salient for liquidity constrained owners.

<!-- **Fiscal procyclicality and maturity of sovereign debt in emerging market economies**
>How does the growing ability of emerging market economies to borrow long term affect the behavior of fiscal policy over the business cycle? This paper develops a dynamic stochastic general equilibrium model of a small open economy that features optimal fiscal policy, unsecured long-term debt, and default risk and calibrates the model to match features of the Chilean economy. Preliminary results indicate that, when debt matures after one period, the optimal tax rate is negatively correlated with output fluctuations. When debt is of long duration, the sign on this correlation is reversed. Long-term debt results in lower welfare in almost all states of the economy, however, which is likely due to the debt dilution problem.
 -->
<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->
