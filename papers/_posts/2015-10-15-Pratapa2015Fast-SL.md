---
layout: paper
title: "Fast-SL: an efficient algorithm to identify synthetic lethal sets in metabolic networks."
year: "2015"
shortref: "Pratapa et al. Bioinformatics 2015"
nickname: Fast-SL
journal: "Bioinformatics"
volume: 31
issue: 20
pages: 3299–3305
authors: "Pratapa A, Balachandran S, Raman K."
image: /ibse/assets/images/papers/default-paper.svg
pdf: 
pdflink: https://academic.oup.com/bioinformatics/article-pdf/31/20/3299/17087781/btv352.pdf
github: 
pmid: 26085504
pmcid: 
f1000: 
figshare: 
doi: 10.1093/bioinformatics/btv352
category: paper
published: true
peerreview: true
review: false
tags: [synthetic lethals, metabolic networks]
---
{% include JB/setup %}

# Abstract 

Motivation: Synthetic lethal sets are sets of reactions/genes where only the simultaneous removal of all reactions/genes in the set abolishes growth of an organism. Previous approaches to identify synthetic lethal genes in genome-scale metabolic networks have built on the framework of flux balance analysis (FBA), extending it either to exhaustively analyze all possible combinations of genes or formulate the problem as a bi-level mixed integer linear programming (MILP) problem. We here propose an algorithm, Fast-SL, which surmounts the computational complexity of previous approaches by iteratively reducing the search space for synthetic lethals, resulting in a substantial reduction in running time, even for higher order synthetic lethals.

Results: We performed synthetic reaction and gene lethality analysis, using Fast-SL, for genome-scale metabolic networks of _Escherichia coli_, _Salmonella enterica_ Typhimurium and _Mycobacterium tuberculosis_. Fast-SL also rigorously identifies synthetic lethal gene deletions, uncovering synthetic lethal triplets that were not reported previously. We confirm that the triple lethal gene sets obtained for the three organisms have a precise match with the results obtained through exhaustive enumeration of lethals performed on a computer cluster. We also parallelized our algorithm, enabling the identification of synthetic lethal gene quadruplets for all three organisms in under 6 h. Overall, Fast-SL enables an efficient enumeration of higher order synthetic lethals in metabolic networks, which may help uncover previously unknown genetic interactions and combinatorial drug targets.
