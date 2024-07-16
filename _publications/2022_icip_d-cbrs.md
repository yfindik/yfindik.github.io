---
title: "D-CBRS: Accounting for Intra-Class Diversity in Continual Learning"
collection: publications
permalink: /publication/2022_icip_d-cbrs
excerpt: ''
date: 2022-10-16
venue: 'IEEE International Conference on Image Processing (ICIP)'
paperurl: 'https://arxiv.org/pdf/2207.05897'
citation: '<b>Y. Findik</b>, F. Pourkamali-Anaraki. &quot;D-CBRS: Accounting for Intra-class Diversity in Continual Learning.&quot; <i>The 29th IEEE International Conference on Image Processing (ICIP), October 2022</i>.'
---

Continual learning – accumulating knowledge from a sequence of learning experiences – is an important yet challenging problem. In this paradigm, the model’s performance for previously encountered instances may substantially drop as additional data are seen. When dealing with class-imbalanced data, forgetting is further exacerbated. Prior work has proposed replay-based approaches which aim at reducing forgetting by intelligently storing instances for future replay. Although Class-Balancing Reservoir Sampling (CBRS) has been successful in dealing with imbalanced data, the intraclass diversity has not been accounted for, implicitly assuming that each instance of a class is equally informative. We present Diverse-CBRS (D-CBRS), an algorithm that allows us to consider within class diversity when storing instances in the memory. Our results show that D-CBRS outperforms state-of-the-art memory management continual learning algorithms on data sets with considerable intra-class diversity.

<img src="../../images/D-CBRS.png">