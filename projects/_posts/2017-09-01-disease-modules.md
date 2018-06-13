---
layout: project
title: "Identification of Disease Modules: DREAM challenge"
tagline: ""
handle: 
image: /ibse/assets/images/projects/
category: project
tags: [disease modules, DREAM, networks]
people: Beethika Tripathi, Karthik Azhagesan, B Ravindran, Himanshu Sinha & Karthik Raman
---
{% include JB/setup %}

Disease Module Identification was a part of DREAM challenge which was organized in late 2016. The objective of the challenge was crowdsourcing the community efforts to benchmark diverse community detection or graph clustering approaches across diverse types of genomic networks, in order to compare strengths and limitations of alternative approaches. The task was to identify disease-relevant modules for individual networks or by sharing information across multiple networks. The problem was hard because no biological information was supposed to used and module identification was supposed to be done purely on the basis of the network structure. The other main issue is related to the properties of the disease modules. The disease modules tend to be typically small in comparison to the size of the networks. Most of the community detection algorithms fail to identify small communities when the network is large. We have used the notion of identifying 'core communities' which are 'small and structurally well defined' communities. These are internally well connected as well as well separated from the rest of the network. This way of doing community detection showed significant improvement than 'off-the-shelf' community detection approaches.
