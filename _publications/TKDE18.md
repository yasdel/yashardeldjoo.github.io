---
title: "Next Generation Indexing for Genomic Intervals "
collection: publications
permalink: /publication/TKDE18
date: 2018-09-19
venue: 'IEEE Transactions on Knowledge and Data Engineering'
citation: 'Vahid Jalili, Matteo Matteucci, Jeremy Goecks, <b>Yashar Deldjoo</b>, Stefano Ceri <i>IEEE Transactions on Knowledge and Data Engineering 2018</i>.'

---

[[DOI]](https://ieeexplore.ieee.org/document/8468044/)  [[PDF]](http://yasdel.github.io/files/Di4TKDE.pdf)  [[bibtex]](https://github.com/yasdel/yasdel.github.io/tree/master/_publications/TKDE18.bib)


## Abstract

Di4 (1D intervals incremental inverted index) is a multi-resolution, single-dimension indexing framework for efficient, scalable, and extensible computation of genomic interval expressions. The framework has a tri-layer architecture: the semantic layer provides orthogonal and generic means (including the support of user-defined function) of sense-making and higher-lever reasoning from region-based datasets; the logical layer provides building blocks for region calculus and topological relations between intervals; the physical layer abstracts from persistence technology and makes the model adaptable to variety of persistence technologies, spanning from small-scale (e.g., B+tree) to large-scale (e.g., LevelDB). The extensibility of Di4 to application scenarios is shown with an example of comparative evaluation of ChIP-seq and DNase-Seq replicates. Performance of Di4 is benchmarked for small and large scale scenarios under common bioinformatics application scenarios. Di4 is freely available from https://genometric.github.io/Di4.
