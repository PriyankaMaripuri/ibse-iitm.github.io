---
layout: paper
title: "Enumerating all possible biosynthetic pathways in metabolic networks"
year: "2018"
shortref: "Aarthi et al. Scientific Reports 2018"
nickname: Aarthi2018Pathways
journal: "Scientific Reports"
volume: 
issue: 
pages: 
authors: "Aarthi Ravikrishnan, Meghana Nasre and Karthik Raman"
image: /assets/images/papers/default-paper.svg
pdf: 
pdflink: 
github:
pmid: 
pmcid: 
f1000: 
figshare: 
doi: 10.1038/s41598-018-28007-7
category: paper
published: true
peerreview: true
review: false
tags: [Networks]
---
{% include JB/setup %}

# Abstract 

Exhaustive identification of all possible alternate pathways that exist in metabolic networks can provide valuable insights into cellular metabolism. With the growing number of metabolic reconstructions, there is a need for an efficient method to enumerate pathways, which can also scale well to large metabolic networks, such as those corresponding to microbial communities. We developed MetQuest, an efficient graph-theoretic algorithm to enumerate all possible pathways of a particular size between a given set of source and target molecules. Our algorithm employs a guided breadth-first search to identify all feasible reactions based on the availability of the precursor molecules, followed by a novel dynamic-programming based enumeration, which assembles these reactions into pathways of a specified size producing the target from the source. We demonstrate several interesting applications of our algorithm, ranging from identifying amino acid biosynthesis pathways to identifying the most diverse pathways involved in degradation of complex molecules. We also illustrate the scalability of our algorithm, by studying large graphs such as those corresponding to microbial communities, and identify several metabolic interactions happening therein. [MetQuest](https://github.com/RamanLab/metquest) is available as a Python package.
