---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}

## Understanding nitrogen transport pathways related to grain protein content in wheat [Spring 2019]  
* Identifying gene regulatory pathways that transport nitrogen from senescing leaves to grain with goal of understanding mechanisms affecting grain protein content trait.  
* Performed WGCNA based gene clustering for seed gene expression data on computing cluster and GO analysis.  
* Collected and cleaned publicly available alignment files (CRAM) from multiple SRA projects. using globus command line, extracted reads mapping to UMAMI genes using SAMtools for verifying gene models (shell).  
* Performed exploratory analysis of UMAMI gene expression in Arabidopsis to verify orthologs and identify phylogenetically conserved expression patterns (R).  

**Key achievement: Identified two modules involved in activating storage molecules including starch, lipids and protein, discovered multiple TFs as possible key candidate genes among modules involving amino acid transporters.**  


## Gaussian Graphical model with fused lasso penalty for learning causal transcriptional regulations of Sorgoleone biosynthesis genes in Sorghum [Fall 2020]  
* Inferring transcriptional regulation of sorgoleone biosynthesis to understand herbivory resistance in sorghum roots with goal of developing biological herbicides.  
* Used HISAT2/featureCounts/DEseq2 to map, count and extract differentially expressed genes from RNAseq data.  
* Verified the algorithm was able to extract causal gene interactions for sorghum circadian genes.  
* Used root and leaf development data from stay green sorghum to identify TF regulators of sorgoleone genes.  

**Key achievement: Identified 21 potential regulators of sorgoleone biosynthesis genes. Verified TF-gene regulations using TF motifs from plant transcription factor database and comparative genomics. Manuscript under preparation.**  


## Zeroinfl: Zero Inflated Poisson regression (ZIP) in Python (with Eric Chuu)[Spring 2018]  
* •	Modeled a process switching between perfect state with no errors and imperfect one with Poisson distributed errors using ZIP regression based on pscl (R) and statsmodels (python) packages.   
* The algorithm provided better fit to model systemic departure from Poisson regression than generalized linear regression model (GLM) (quasi-Poisson, negative binomial) and generalized linear mixed models.  
* Implemented logit, probit, complementary log log, Cauchy and log link functions for GLM fit using object-oriented programming.  
* Wrote functions for likelihood, log-likelihood, gradient and max likelihood estimation using BFGS optimization, with expectation maximization-based initialization.  
* Wrote functions summary for pretty-printing results including p-value, standard error, z-statistics and predict for using fitted model for prediction.  
* The functionality was extended to include zero inflated negative binomial and zero inflated geometric regressions.  

**Key achievement: Provided fully functional zero inflated regression functionality in Python.**   


## Adaboost based face detection using Voila Jones framework [Fall 2019]
* Implemented five stage Adaboost classifier in python with decision stump as weak learner for detecting face images using vertical, horizontal and diagonal Haar features. Code vectorization was extensively used for speedup.  
* Observed the effect of changes in false negative and false positive penalties on empirical accuracy.  

**Key achievement: Achieved 3.5x improvement in training time at the cost of 2.25% reduction in empirical accuracy by filtering robust features.**  


## Minimum description length based Boolean network learning [Spring 2020]  
* Used cost function consisting of sum of the error and model-description entropies as analogues of resubstitution-error and VC dimension for model-complexity regularization, for learning gene networks from Boolean time series.  
* Used model and noise codelengths as universal sufficient statistics decomposition of total codelength under normalized log-likelihood model by partitioning the parameter space such that adjacent partitions are separated by fixed Kullback-Leibler distance.  
* The code was tested and verified on Boolean time series data generated using BoolNet package in R.  

**Key achievement: The MATLAB code based on Dougherty et al. paper was released for open source use.**  


## Gaussian Mixture Modeling for Cancer Heterogeneity [Fall 2016]  
* Used gaussian mixture modelling to model cancer heterogeneity as mixture of Boolean networks.  
* Expectation maximization was then used to estimate the proportion of each subpopulation.  

**Key achievement: Results were published in IEEE/ACM TCBB journal.**  
