---
title: "Mixed Q-Functionals: Advancing Value-Based Methods in Cooperative MARL with Continuous Action Domains"
collection: publications
permalink: /publication/2024_arXiv_mixed-q-functionals
excerpt: ''
date: 2024-02-12
paperurl: https://arxiv.org/pdf/2402.07752
venue: 'arXiv.org'
citation: '<b>Y. Findik</b>, R. Azadeh. &quot;Mixed Q-Functionals: Advancing Value-Based Methods in Cooperative MARL with Continuous Action Domains.&quot; <i>arXiv preprint arXiv:2402.07752, February 2024</i>.'
---

Tackling multi-agent learning problems efficiently is a challenging task in continuous action domains. While value-based algorithms excel in sample efficiency when applied to discrete action domains, they are usually inefficient when dealing with continuous actions. Policy-based algorithms, on the other hand, attempt to address this challenge by leveraging critic networks for guiding the learning process and stabilizing the gradient estimation. The limitations in the estimation of true return and falling into local optima in these methods result in inefficient and often sub-optimal policies. In this paper, we diverge from the trend of further enhancing critic networks, and focus on improving the effectiveness of value-based methods in multi-agent continuous domains by concurrently evaluating numerous actions. We propose a novel multi-agent value-based algorithm, Mixed Q-Functionals (MQF), that enables agents to transform their states into basis functions. Our algorithm fosters collaboration among agents by mixing their action-values. We evaluate the efficacy of our algorithm in six cooperative multi-agent scenarios. Our empirical findings reveal that MQF outperforms four variants of Deep Deterministic Policy Gradient through rapid action evaluation and increased sample efficiency.

<img src="../../images/mixed-qf_neurips.png">