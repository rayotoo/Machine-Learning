## GPU-Implemented-ancestry-Implementation
[![LICENSE](https://img.shields.io/github/license/rayotoo/GPU-Implemented-ancestry-Implementation-?style=flat-square&color=green)](https://github.com/rayotoo/GPU-Implemented-ancestry-Implementation-/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/rayotoo/GPU-Implemented-ancestry-Implementation-?style=flat-square)](https://github.com/rayotoo/GPU-Implemented-ancestry-Implementation-/issues)
[![GitHub stars](https://img.shields.io/github/stars/rayotoo/GPU-Implemented-ancestry-Implementation-?style=flat-square&color=important)](https://github.com/rayotoo/GPU-Implemented-ancestry-Implementation-/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/rayotoo/GPU-Implemented-ancestry-Implementation-?style=flat-square&color=blueviolet)](https://github.com/rayotoo/GPU-Implemented-ancestry-Implementation-/network/members)

# Introduction
GPU vs CPU. 
This study aims to harness the strength of GPU when dealing with heavy computations. The advantage of GPUs over CPUs lies in the fact that GPU have relatively more cores as compared to CPUs. As a result, task that can be run parallel tend to be processed faster on GPUs than CPUs.

# Ancestry inference
Systematic analysis of the patterns in which genetic variants are shared among individuals and populations provides detailed accounts of population history. 

NB: Although most common variants are shared across the world, rarer variants are typically restricted to closely related populations
The ancestry will be inferred using the SNPs of from the whole genome sequence.


# Data set
The data set used for this study was obtained from the 1000 Genome’s project.
  + Data has been provided in the data directory in this reposotory. 
  + NB: Only Chr1 was considered and a compressed file for its data is provided.

# Machine Learning Algorithms
Some selected machine learning algorithms were implemented on the dataset and their respective performances were evaluated and compared against each other in terms of performance.


# Conclusion
At the end of this study;
  + Some machine learning algorithms were identified (RF, SVM, KNN and MLP) among others that were run on the test data to be “relatively better” performers.
  + The top 100 most important SNPs (SNP ids) related to ancestry on chromosome 1 were identified.

# Future directions to improve performance
  + More chromosomes will  be included in training subsequent models.
  + More functions for GPU processing will be included.
  + A model that can predict an individual’s ancestry based on a relatively small subsection of their DNA will be developed.
