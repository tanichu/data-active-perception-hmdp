# data-active-perception-hmdp

This repository is for providing data used in the experiment 1 of the following paper.

Taniguchi, Tadahiro, Toshiaki Takano, and Ryo Yoshino. "Multimodal hierarchical Dirichlet process-based active perception." arXiv preprint arXiv:1510.00331 (2015).
https://arxiv.org/abs/1510.00331

./modality-data/training/

  vdata.csv ... Visual information for each object (m^v).
  asdata.csv ... Auditory information obtained by shaking each object (m^as).
  ahdata.csv ... Auditory information obtained by hitting each object (m^ah).
  hdata.csv ... Haptic information for each object (m^h).

  The n-th row show BoF representation for the n-th object.

./modality-data/test/

  object#{j}\_#{m}.csv
  
  The index #{j} represents the index of an object.
  the index #{m} represents the index of a modality.
  Each text file contains BoF obtained by each action.
  
  

