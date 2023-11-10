# Code repository: Dynamic Regulation of Innate Lymphoid Cell Development During Ontogeny

This repository contains single-cell RNA-seq data processing codes of the paper **Dynamic Regulation of Innate Lymphoid Cell Development During Ontogeny**. 

## Contents:

- Cell_Preprocessing_Steps
- Cell_Integration
- Cell_Dynamics
- SCENIC_GRN
- TSC_GRN
- Cell_Identity_Mapping
- DEG_Enrichment_and_CellMapping

## Data Availablity:

The single-cell RNA sequencing data are available at GSA (https://ngdc.cncb.ac.cn/gsa/) with accession number CRA011319. Please feel free to contact us if you have any data analysis issues. (chensj16 ##AT## tsinghua ##DOT## org ##DOT## cn)

## Prerequisite

The analyses were conducted under a R-4.1.1 python-3.7 environment. We used SeuratV4 and scanpy-1.8.2 to perform most scRNA-seq analyses. We suggested using docker for the SCENIC analysis.
