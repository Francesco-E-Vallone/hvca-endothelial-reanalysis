# A small reproducible re-analysis focused on annotation structure, marker logic, and interpretation limits

Using Human Vascular Cell Atlas data to understand how endothelial cell states are annotated and interpreted.

## Aim

This project uses processed Human Vascular Cell Atlas data to look at how endothelial cell states are annotated and interpreted.

I focus on four things: the metadata structure, the published annotation levels, canonical vascular marker genes, and the sensitivity of simple clustering choices.

This is not a reproduction of the full atlas paper and it is not a discovery analysis. The goal is to understand the dataset and keep the interpretation within what the analysis can actually support.

## What this project does

The project asks four simple questions:

1. What metadata and annotation levels are available in the dataset?
2. Do canonical vascular markers support the main published labels?
3. How do tissue labels relate to endothelial and vascular annotations?
4. How much does a simple clustering result change when basic parameters are changed?

## What this project does not do

This project does not process raw sequencing data.

It does not identify new endothelial states.

It does not validate biological mechanisms.

It does not claim disease relevance.

I use processed data and published labels, so the conclusions are descriptive.

## Data

Large data files are not included in this repository.

The analysis uses the processed endothelial-cell h5ad object from the Human Vascular Cell Atlas.

Expected local path:

```text
data/raw/hvca_ec.h5ad
