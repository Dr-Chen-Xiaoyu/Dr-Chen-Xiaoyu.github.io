---
title: "Cerebellum-inspired neural network of supervised learning with tensor-based sparse coding for multi-class classification"
collection: publications
category: manuscripts
permalink: /publication/cerebellum-inspired-neural-network
excerpt: "A cerebellum-inspired model combines tensor-based sparse coding with supervised multiclass learning."
date: 2026-08-18
venue: "PLOS Computational Biology"
# paperurl: "https://doi.org/10.1371/journal.pcbi.1014595"
citation: >-
  Zhou, R., Zhou, D., Li, S., &amp; <strong>Chen, X.</strong> (2026).
  Cerebellum-inspired neural network of supervised learning with tensor-based sparse coding for multi-class classification.
  <i>PLOS Computational Biology, 22</i>(8), Article e1014595.
  <a href="https://doi.org/10.1371/journal.pcbi.1014595">https://doi.org/10.1371/journal.pcbi.1014595</a>
---

**Authors**<br>
Runguang Zhou, Douglas Zhou, Songting Li, and **Xiaoyu Chen**

## Abstract

Under the Marr-Ito-Albus framework, the cerebellum performs supervised learning in Purkinje cells upon the unsupervised sparse representations generated within granule cells, contributing fundamentally to associative learning in motor control. However, the specific mechanisms through which cerebellar circuitry and plasticity rules enable supervised learning, and properties of the sparse coding induced by cerebellar architectural constraints, remain poorly characterized. To address this, we first established a sparse coding mechanism inspired by anatomical and physiological properties of the granular layer, including input-sharing connectivity from mossy fibers, Golgi-cell-mediated localized feedback inhibition for winner-take-all sparsification, and activity-dependent bias adjustments. This sparse coding, implemented via efficient tensor-based computations, preserves local neighborhood structures as revealed in a geometric interpretation. Furthermore, we demonstrated that error signals transmitted via climbing fibers to Purkinje cells, integrated with intrinsic plasticity, drive efficient learning of the sparse representations for multi-class classification, leading to accurate population coding for judgments in the cerebellar nuclei. The resultant cerebellum-inspired neural network model achieved a test accuracy of 90.50 ± 0.10% on Fashion-MNIST, performance comparable to a backpropagation-trained single-hidden-layer feedforward neural network, while providing more than  5x computational acceleration. The model further exhibited proof-of-principle closed-loop control capability in simplified motor tasks, including balancing a cart-attached pole and controlling a robotic arm to reach targets. Our study delineates cerebellum-inspired sparse coding and supervised learning mechanisms, and demonstrates robust performance of the cerebellum-inspired neural network across multiple task domains. These results suggest that cerebellum-inspired architectures would provide useful design principles for lightweight neural networks in resource-limited and latency-critical applications.