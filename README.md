Hyperdimensional Computing for Tumour Metabolic Network Classification
Abstract
In the era of big data biology, genome-scale metabolic models (GEMs) have become invaluable tools for understanding cellular metabolism across diverse organisms. These models provide a comprehensive view of metabolic networks, encompassing the complex interplay of enzymes, metabolites, and reactions. However, comparing and analysing these intricate models in a biologically meaningful manner remains a challenging task.

To address this, we introduce the application of Hyperdimensional Computing (HDC) graph encoders to classify cancer subtypes using tumour metabolic networks (TumorMet). We benchmarked native single-pass HDC classification against traditional machine learning estimators (Support Vector Machines and Logistic Regression) trained on hypervector feature embeddings, and evaluated retraining schemes designed to improve native accuracy.

We demonstrate that HDC efficiently embeds the hierarchical structure and constituent characteristics of these biological graphs into hypervectors for downstream learning tasks. Our findings show that HDC-generated embeddings successfully classify tumour subtypes, offering a robust alternative to established baselines. While native centroid-based classification currently encounters performance plateaus due to noise accumulation within dense metabolic graphs, the representational power of HDC as a feature embedding is highly effective.

Ultimately, HDC emerges as a highly promising, scalable framework for network-based oncology, highlighting a clear pathway for future optimisation techniques to achieve fully transparent, "white-box" biological classification.

Objectives
The main objective of this project was to evaluate published HDC-based graph encoders for metabolic network analysis using machine learning and/or phylogenetics.

Project Goals
Reimplement published HDC-based graph encoders in Julia.
Test the reimplementation using:
Machine learning on tumour metabolic network datasets, or
Phylogenetic analysis on subsets of KEGG metabolic networks.
Evaluate the effect of architectural configurations on encoder performance.
The project structure allowed students to select three out of five available tasks, providing flexibility to explore specific interests. Possible extensions included information retrieval applications and the development of novel graph encoders.

Workflow
Project Workflow

Figure 1. Schematic workflow of the project.

A. Metabolic networks are encoded into hypervectors using HDC graph encoders and subsequently applied to downstream learning tasks.

B. The project can focus either on:

evaluating graph encoders across additional downstream applications, or
investigating the impact of architecture and encoding configurations on performance.
Conclusions
In this exploratory study, we present the first application of Hyperdimensional Computing to classify cancer subtypes using tumour metabolic networks. Our objective was to adapt the HDC framework for efficient encoding and classification of structurally and topologically complex biological graphs.

Successfully encoding these biological networks into hypervectorsinterplay between the chosen Vector Symbolic Architecture (VSA), dimensionality, feature density, and retraining strategy. Since expanding hyperdimensional space directly increases computational cost, balancing these parameters is essential for maximising predictive performance while preserving HDC's computational efficiency.

Although HDC proved to be a robust and scalable alternative to the baseline approaches, native centroid-based classification frequently struggled to match the predictive performance of conventional machine learning methods. As a result, the strongest current application of HDC lies in its ability to generate informative feature embeddings for downstream classifiers.

To preserve the inherent transparency of native HDC systems, iterative retraining schemes were explored. However, they did not improve performance, potentially due to noise accumulation in dense metabolic graphs. Future work should therefore focus on spatial optimisation techniques to mitigate background noise before or during retraining.

Overall, our findings highlight both the challenges and opportunities of combining biological insight with the symbolic, distributed representations of Hyperdimensional Computing. This approach represents a promising avenue towards scalable, interpretable, and biologically meaningful network-based cancer classification.

Skills & Technologies
Hyperdimensional Computing (HDC)
Graph Representation Learning
Computational Biology
Cancer Bioinformatics
Genome-Scale Metabolic Models (GEMs)
Julia
Machine Learning
Support Vector Machines (SVM)
Logistic Regression
Network Analysis
Feature Engineering
Scientific Computing
