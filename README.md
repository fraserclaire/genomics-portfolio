# Genomics & Bioinformatics Portfolio

This repository contains a collection of bioinformatics projects focused on **next-generation sequencing (NGS) analysis**, **pipeline development**, and **interactive data visualization**.

The work presented here emphasizes reproducible workflows and the translation of complex biological data into interpretable insights.

---

## Overview

This portfolio brings together three core areas of bioinformatics:

* **Pipeline Development** — building scalable and reproducible workflows
* **Data Visualization** — creating tools for interactive and publication-ready figures
* **Evolutionary Analysis** — applying statistical and phylogenetic methods to biological data

---

## Featured Projects

### ONT Methylation Pipeline

An end-to-end pipeline for analyzing DNA methylation from Oxford Nanopore sequencing data.

* Processes raw signal data (POD5) through basecalling, methylation extraction, and aggregation
* Built using a modular workflow design for reproducibility and scalability
* Integrates tools such as Dorado, SAMtools, and Modkit

➡️ `projects/ont-methylation.qmd`

---

### NGS Figure Generator

An interactive tool for generating publication-ready figures from sequencing data.

* Supports volcano plots, heatmaps, and PCA visualizations
* Enables parameter tuning and iterative figure refinement
* Combines Python-based data processing with an interactive frontend

➡️ `projects/seq-visualizer.qmd`

---

### SARS-CoV-2 Evolutionary Analysis

A comparative genomics project examining viral evolution across populations.

* Integrates epidemiological trends, geographic comparisons, and phylogenetic analysis
* Includes selection analyses to identify sites under evolutionary pressure
* Explores how transmission dynamics and selection shape viral diversity

➡️ `projects/sars-cov2.qmd`

---

## Technologies & Tools

**Languages**

* Python, R, Bash

**Bioinformatics & Data Analysis**

* Nextflow, Seurat, GSEA
* BEAST, Mesquite
* Pandas, scikit-learn

**Visualization**

* Plotly, Matplotlib, Seaborn

**Workflow & Reproducibility**

* Docker, Linux-based environments

---

## Project Structure

```
portfolio/
├── index.qmd
├── projects/
│   ├── ont-methylation.qmd
│   ├── seq-visualizer.qmd
│   └── sars-cov2.qmd
├── images/
└── styles.css
```

---

## Running the Site Locally

To preview the portfolio site:

```bash
quarto preview
```

This will render the site locally and allow interactive exploration of the pages.

---

## License

Code in this repository is licensed under the MIT License.

Figures, analyses, and written content are intended for portfolio and demonstration purposes and should not be reused without permission.
