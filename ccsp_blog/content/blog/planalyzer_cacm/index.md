+++
title = "Dr. Tosch's work featured in CACM"
draft = false
date = 2021-09-01

[extra]
preview = "Sept2021-Cover-500x669.webp"
+++

[Dr. Emma Tosch](https://uvm.edu~/etosch)'s work on static analysis for online field experiments[^1] appears in the [September issue](https://cacm.acm.org/magazines/2021/9/255047-planalyzer/fulltext) of the [Communications of the ACM (CACM)](https://cacm.acm.org/), the premier journal of the [Association for Computing Machinery](http://acm.org).

<!-- more -->

[PlanAlyzer](https://github.com/KDL-umass/PlanAlyzer) is a linter for online field experiments written in the [Planout](https://github.com/facebook/planout) language. The aim of this work is to catch problems such as _selection bias_ earlier in the process of designing experiments, before resources have been spent collecting data that may not be useful. 


<embed
    src="system.jpg"
    width="100%"
    height="100%"
></embed>

Experimentation is an essential method for determining cause and effect in complex systems. Randomized field experiments are often the only suitable method available for making evidence-based decisions. While encoding experiments in a formal language can obviate some errors, it can also introduce new ones. Establishing the validity of experimental designs is important to security and privacy researchers. Experimentation is also a novel domain for security and privacy research: e.g., researchers might need to use sensitive information to appropriately assign experimental treatment and thus need to think about preserving privacy, or they might want to look at problems such as multiple comparisons or "p-hacking" through a security lens. 

In 2020, this work was one of three papers selected as a [SIGPLAN research highlight](https://www.sigplan.org/Highlights/Papers/) and was subsequently featured in the [SIGPLAN blog](https://blog.sigplan.org/2020/09/01/2019-sigplan-research-highlight-awards/). Special interest group (SIG) research highlights are chosen from published papers across every venue sponsored by the SIG. This work originally appeared in [OOPSLA 2019](https://2019.splashcon.org/details/splash-2019-oopsla/63/PlanAlyzer-Assessing-Threats-to-the-Validity-of-Online-Experiments); the original full publication can be found on the [ACM Digital Library](https://dl.acm.org/doi/pdf/10.1145/3360608) and [ArXiV](https://arxiv.org/abs/1909.13649).

[^1] Joint work with [Eytan Bakshy](https://eytan.github.io/), [Emery Berger](https://cs.umass.edu/~berger), [David Jensen](https://cs.umass.edu/~jensen), and [Eliot Moss](https://cs.umass.edu/~moss).