---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---
---
## Publications

**[Finite-sample inference and nonstandard asymptotics with Monte Carlo tests and R](https://doi.org/10.1016/bs.host.2019.05.001)**  
with Jean-Marie Dufour
_Handbook of Statistics
Volume 41, 2019, Pages 3-31_
>We review the concept of Monte Carlo test as a simulation-based inference procedure which allows one to construct tests with provably exact levels in situations where the distribution of a test statistic is difficult to establish but can be simulated. The number of simulations required can be extremely small, as low as 19 to run a test with level 0.05. We discuss three extensions of the method: (1) a randomized tie-breaking technique which allows one to use test statistics with discrete null distributions, without further information on the mass points; (2) an extension (maximized Monte Carlo tests) which yields provably valid tests when the test statistic depends on a (finite) number of nuisance parameters; (3) an asymptotic version which allows one to get asymptotically valid tests without any need to establish an asymptotic distribution. As the method is computer intensive, we describe an R package (MaxMC) that allows one to implement this type of procedure. A number of special cases and applications are discussed.

## Works in Progress

**Judge Influence and Judicial Network**
>While researchers in the past years have tried to better understand the link between judges' individual characteristics and judges' overall influence, less work has been done to capture how social interactions affect  this relationship. This paper, through the framework and empirical strategy proposed by Battaglini et al (2018), tries to fill this gap. Using flow of law clerks between judges from 1995-2004 as a measure of social connections and total citations as a proxy for influence, I am able to identify significant effects from social interactions. I find that weighted Katz-Bonacich centrality is a robust predictor of judicial influence even after correcting for endogeneity. In addition, I show that social spillovers are not homogeneous across demographics. For instance, ethnic minorities and younger judges are not able to utilize their social connections as well as other judges.



<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
 -->
