# Honours Project – Cell Type Classification with scDeepInsight

This repository contains the code and experimental results for my **Honours Project**, which investigates **cell type classification** from single-cell RNA-sequencing (scRNA-seq) data using the **scDeepInsight** framework.

---

## Overview

This project evaluates **scDeepInsight** across multiple experimental settings, including:

- Single-dataset training  
- Cross-dataset generalization between the *McKellar* and *Oprescu* scRNA-seq datasets

The primary objective is to assess the *robustness and generalization performance* of deep learning–based cell type classification models on single-cell RNA sequencing data, with a particular focus on behavior under dataset shift.

---

## Methodology

This work builds upon the **scDeepInsight** framework introduced by:

**Jia et al. (2023)**  
*scDeepInsight: a supervised cell-type identification method for scRNA-seq data with deep learning*  
[Link to the Paper](https://academic.oup.com/bib/article/24/5/bbad266/7233965)  
[Original implementation on GitHub](https://github.com/shangruJia/scDeepInsight)

> **Note:** I did not create *scDeepInsight*. All credit for the original method and code belongs to the original authors.

---

## My Contributions

This repository focuses on extending and evaluating the existing framework through:

- Dataset-specific preprocessing and normalization  
- Adapting and running the **scDeepInsight** pipeline  
- Training and evaluation experiments across multiple datasets  
- Performance analysis, visualization, and discussion of results
