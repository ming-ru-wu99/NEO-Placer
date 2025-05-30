# NEO Placer
## Paper Preprint (NEO placer.pdf in this repository) (2025/5/30)
Abstract—This paper presents the NEO (NEural Optimization-based) placer, a thermal-aware floorplanning/placement system
for 3D ICs, by combining a set of novel methods with the powerful auto-gradient capability of modern machine learning (ML)
frameworks. We employ a new pure neural network approach
featuring the minimalist design in wirelengths and overlaps and
the maximin (maximization of the minimum distance) and per-tile
activation designs in temperatures. We discover that exact HPWL
(half perimeter wire length) and overlap formulas can be used
for auto gradients in ML without employing the differentiable
weighted-average (WA) or log-sum-exp (LSE) approximation in
most modern analytic placers. We also propose a new formula for
the inter-block corner distance suitable for placing hotter blocks
further apart to indirectly reduce the maximum temperature,
Tmax. The ML thermal solver based on parallel per-tile activation
is applied for direct minimization of Tmax. Our placer is extended
to multiple chiplets for efficient analysis of vertical coupling in 3D
ICs. Experimental results verify the validity of our NEO placer
that outperforms the placer based on simulated annealing (SA)
by reducing more than 5% in Tmax.


### To preserve the anonymity required for the review process, please refrain from downloading or opening the PDF, as it contains author-identifying information.

### © 2025 Anonymous Authors. All rights reserved.
This work is provided for review and academic discussion only.  
No part of this work may be used commercially without explicit permission from the authors.
