---
layout: post
date: 2024-11-04 07:59:00-0400
title: New arXiv paper; Target search on networks-within-networks with applications to protein-DNA interactions
inline: false
related_posts: false
---


## Target search on networks-within-networks with applications to protein-DNA interactions, 
Lucas Hedström, Seong-Gyu Yang, and Ludvig Lizana

[arXiv:2411.02660](https://arxiv.org/abs/2411.02660)

We present a novel framework for understanding node target search in systems organized as hierarchical networks-within-networks. Our work generalizes traditional search models on complex networks, where the mean-first passage time is typically inversely proportional to the node degree. However, real-world search processes often span multiple network layers, such as moving from an external environment into a local network, and then navigating several internal states. This multilayered complexity appears in scenarios such as international travel networks, tracking email spammers, and the dynamics of protein-DNA interactions in cells. Our theory addresses these complex systems by modeling them as a three-layer multiplex network: an external source layer, an intermediate spatial layer, and an internal state layer. We derive general closed-form solutions for the steady-state flux through a target node, which serves as a proxy for inverse mean-first passage time. Our results reveal a universal relationship between search efficiency and network-specific parameters. This work extends the current understanding of multiplex networks by focusing on systems with hierarchically connected layers. Our findings have broad implications for fields ranging from epidemiology to cellular biology and provide a more comprehensive understanding of search dynamics in complex, multilayered environments.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/networks-infographics.jpg" title="infographics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Alluvial diagram illustrating how the node stability in the Hi-C networks changes between different chromosome scales. Most flow lines connect the same stability category (red to blue colors) or one nearby. This indicates that stability is a conserved property through the chromosomes' folding hierarchies (e.g., bottom, dark red). The bar charts on the left and right show the enrichment of the chromatin state. The three leftmost bars represent chromatin associated with active genomic regions (defined by histone modifications and DNA-binding proteins). This alluval argues that similar mechanisms drive the cross-scale folding on select parts of the chromosome.
</div>


{% raw %}

```
@article{hedstrom2024target,
  title={Target search on networks-within-networks with applications to protein-DNA interactions},
  author={Hedstr{\"o}m, Lucas and Yang, Seong-Gyu and Lizana, Ludvig},
  journal={arXiv preprint arXiv:2411.02660},
  year={2024}
}
```

{% endraw %}
