# Analysis of large single-cell RNA-seq datasets in R/Bioconductor

# Instructor(s) name(s) and contact information
Davide Risso (@drisso, risso.davide@gmail.com), Stephanie Hicks (@stephaniehicks)

# Workshop Description

The volume and rich complexity of single cell RNA-Sequencing (scRNA-seq) data requires sophisticated computational tools for integrative statistical analysis and comprehension. In this workshop, we will illustrate some questions that can be answered using scRNA-seq data and demonstrate through case studies and tutorials how to answer those questions using R / Bioconductor packages. This will include examples on accessing and loading in data, pre-processing and applying quality control, normalization, dimensionality reduction, and clustering. We will focus on large datasets and we will illustrate specific Bioconductor packages and computational strategies that can be helpful when dealing with massive data (hundreds of thousands to millions of cells). In particular, we will illustrate how to use packages that leverage the SingleCellExperiment, DelayedArray and HDF5Array frameworks to analyze data that may not fit entirely in memory.


## Pre-requisites

We expect basic knowledge of R syntax. Some familiarity with S4 objects may be helpful, but not required.
More importantly, participants should be familiar with the concept and design of RNA-sequencing experiments. Direct experience with single-cell RNA-seq is not required, and the main challenges of single-cell RNA-seq compared to bulk RNA-seq will be illustrated.

## Workshop Participation

This will be a hands-on workshop, in which each student, using their laptop, will analyze a provided example datasets. The workshop will be a mix of example code that the instructors will show to the students (available through this repository) and short exercises.

## _R_ / _Bioconductor_ packages used

1. _scater_: https://bioconductor.org/packages/scater
2. _scran_: https://bioconductor.org/packages/scran
3. _BiocSingular_: https://bioconductor.org/packages/BiocSingular
4. _mbkmeans_: https://github.com/drisso/mbkmeans (under review in Bioconductor)

## Time outline

1 hr workshop:

| Activity                                   | Time |
|--------------------------------------------|------|
| Intro to single-cell RNA-seq analysis      | 10m  |
| scater (Quality Control)                   | 10m  |
| scran (normalization)                      | 10m  |
| BiocSingular (dimensionality reduction)    | 10m  |
| mbkmeans (clustering)                      | 10m  |

# Workshop goals and objectives

## Learning goals

* describe the goals of single-cell RNA-seq analysis 
* identify the main steps of a typical single-cell RNA-seq analysis
* identify the main challenges of working with very large datasets 
* apply this workflow to carry out a complete analysis of other single-cell RNA-seq datasets

## Learning objectives

* compute and interpret low-dimensional representations of large single-cell datasets
* identify and remove sources of technical variation from the data
* identify sub-populations of cells (clusters) and evaluate their robustness
* identify specific approaches and best practices to use when working with large datasets

