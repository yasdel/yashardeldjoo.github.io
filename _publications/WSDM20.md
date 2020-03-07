---
title: "Adversarial Machine Learning in Recommender Systems (AML-RecSys)"
collection: publications
permalink: /publication/WSDM20
date: 2020-01-01
venue: 'Proceedings of the 13th ACM Conference on Web Search and Data Mining'
citation: '<b>Yashar Deldjoo</b>, Tommaso Di Noia, Felice Antonio Merra <i>Proceedings of 13th ACM Conference on Web Search and Data Mining </i><b>(WSDM'20)</b>.'

---

[[DOI]](https://doi.org/10.1145/3336191.3371877)  [[PDF]](http://yasdel.github.io/files/WSDM20.pdf)  [[bibtex]](https://github.com/yasdel/yasdel.github.io/tree/master/_publications/WSDM20.bib)



## Abstract

Recommender systems (RS) are an integral part of many online services aiming to provide an enhanced user-oriented experience.Machine learning (ML) models are nowadays broadly adopted in modern state-of-the-art approaches to recommendation, which
are typically trained to maximize a user-centred utility (e.g., user
satisfaction) or a business-oriented one (e.g., protability or sales
increase). They work under the main assumption that users’ histor-
ical feedback can serve as proper ground-truth for model training
and evaluation. However, driven by the success in the ML commu-
nity, recent advances show that state-of-the-art recommendation
approaches such as matrix factorization (MF) models or the ones
based on deep neural networks can be vulnerable to adversarial
perturbations applied on the input data. These adversarial samples
can impede the ability for training high-quality MF models and can
put the driven success of these approaches at high risk. As a result,
there is a new paradigm of secure training for RS that takes into ac-
count the presence of adversarial samples into the recommendation
process.

We present adversarial machine learning in Recommender Systems
(AML-RecSys), which concerns the study of eective ML techniques
in RS to ght against an adversarial component. AML-RecSys has
been proposed in two main fashions within the RS literature: (i)
adversarial regularization, which attempts to combat against ad-
versarial perturbation added to input data or model parameters of
a RS and, (ii) generative adversarial network (GAN)-based models,
which adopt a generative process to train powerful ML models. We
discuss a theoretical framework to unify the two above models,
which is performed via a minimax game between an adversarial
component and a discriminator. Furthermore, we explore various
examples illustrating the successful application of AML to solve
various RS tasks. Finally, we present a global taxonomy/overview
of the academic literature based on several identied dimensions,
namely (i) research goals and challenges, (ii) application domains
and (iii) technical overview.