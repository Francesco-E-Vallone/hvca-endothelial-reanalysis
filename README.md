# HVCA endothelial re-analysis

Small re-analysis of the processed endothelial-cell object from the Human Vascular Cell Atlas.

Main notebook:

```text
analysis/analysis.ipynb
```

Rendered HTML:

```text
docs/analysis.html
```

## Contents

The notebook includes:

- metadata and annotation overview
- UMAP overview
- marker checks using existing labels
- organ-by-annotation overlap
- Leiden clustering sensitivity check

The analysis uses published annotations and does not claim new endothelial states or subpopulations.

## Data

The input `.h5ad` file is not tracked by Git.

Expected path:

```text
data/raw/hvca_ec.h5ad
```

Download the processed endothelial-cell object from the Human Vascular Cell Atlas data page and place it there.

## Environment

```bash
conda env create -f environment.yml
conda activate hvca-endothelial-reanalysis
```

