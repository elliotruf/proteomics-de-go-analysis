# Proteomics Fold-change-based Expression Comparison and GO Enrichment Analysis

Exploratory analysis of total proteome and phosphoproteome datasets performed as part of my MSc in Applied Bioinformatics & Genomics.

This project implements a reproducible R workflow for identifying protein expression changes and interpreting functional changes through Gene Ontology (GO) enrichment.

Note: Due to the exploratory 1:1 sample design, fold-change thresholds were used to identify candidate differentially expressed proteins rather than statistical testing.

## Workflow
- Data preprocessing and cleaning
- Fold-change-based expression comparison
- Ranked hit lists of proteins and phosphosites
- Gene Ontology enrichment analysis
- Data visualisation

## Features
- Optional sensitivity analysis enabling parallel analyses at different fold-change thresholds.

## Tools
R, tidyverse, janitor, clusterProfiler, pheatmap, ggplot2

## Status
⚠️ Work in progress
