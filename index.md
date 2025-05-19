---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Abstract 

The PAC-Bayesian framework offers a flexible and powerful approach to assessing the generalization of machine learning models, combining ideas from probability (with concentration inequalities), information theory, and learning theory.  Unlike classical generalization bounds-which often yield vacuous guarantees in modern (over-parameterized) setting-PAC-Bayesian analysis leverages tools from concentration inequalities and information theory to derive data-dependent and non-vacuous bounds that remain meaningful in practice. This tutorial will start with a brief overview of standard generalization tools-such as Rademacher complexity and algorithmic stability-before introducing PAC-Bayesian theory from first principles. We will present key results with simple proofs to highlight the core mechanisms behind PAC-Bayes bounds. Beyond theory, we will emphasize the algorithmic relevance of PAC-Bayesian bounds.  Rather than treating them as purely analytical tools, we will show how they can be turned into learning objectives. This leads to self-bounding algorithms: models are learned by directly minimizing a generalization bound, resulting in built-in guarantees. Recent advances in this direction will be highlighted, along with practical case studies involving robustness, fairness, and model selection. The tutorial emphasizes the practical value of PAC-Bayesian theory, especially with the current major concerns in artificial intelligence, where trustworthy and certifiable machine learning models are critical. Whether the attendees are new or familiar with PAC-Bayesian theory, this session will provide a fresh look at how to design efficient, certifiable models using learning theory.
