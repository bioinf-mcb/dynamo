# 🦠 Dynamo: A Library for Microbiome Exploration 🦠🔬

![Build Status](https://img.shields.io/github/actions/workflow/status/paula078/dynamo_library/ci-unittest.yml?branch=main)
![Python Version](https://img.shields.io/badge/python-3.10+-blue.svg)

## Overview

`dynamo_library` is an advanced Python library designed for researchers and data scientists who work with longitudinal microbiome data, especially in the context of human gut microbiome dynamics. The library provides a robust, flexible, and user-friendly framework to analyze time-series data, offering deep insights into the temporal patterns and behaviors of microbial communities. 

This repository contains the source code used to generate figures for our manuscript. To utilize the methods described in the manuscript, please clone or download this repository from:
https://github.com/paula078/dynamo_library

The code is organized into classes for easier implementation. For detailed usage instructions, please refer to the documentation in the README.md file.

**Why use `dynamo_library`?**

- **Unlock the potential of time-series microbiome data**: Traditional cross-sectional approaches often fail to capture the dynamics of the microbiome. This library enables a detailed longitudinal analysis.
- **Comprehensive toolset**: Perform seasonality analysis, diversity assessments, and predictive modeling in one integrated package.
- **Designed for real-world research**: The library is a direct result of cutting-edge research on microbiome time-series data, published in *Microbiology Spectrum* ([10.1128/spectrum.04109-23](https://doi.org/10.1128/spectrum.04109-23)).
- **Future integration**: Future plans include seamless integration with **QIIME 2**, one of the most popular bioinformatics platforms for microbiome analysis.



## Features

`dynamo_library` offers a broad range of features for time-series analysis and microbiome research:

### 🌍 **Community-Level Microbiome Analysis**
Understand the broader structure of the microbiome with community-wide analysis, including **alpha diversity** calculations, which provide insights into the richness and evenness of microbial species in your samples. 

- **Alpha diversity**: Evaluate the overall health of the microbiome, as higher diversity is often linked to improved health outcomes.
- **Principal coordinate analysis (PCoA)**: Reveal distinct clusters for each subject’s microbiome.
- **Taxonomy**: Visualize taxonomy changes over time
- **Fourier Transform Analysis**: Automatically detect **seasonal patterns** in microbiome data, allowing for an understanding of how external factors affect the microbial community.
  
### 🔍 **Individual Species Analysis**
Track individual bacterial species over time to uncover their unique behaviors, stability, and responses to environmental changes.

- **Temporal stability**: Identify species that are stable over time versus those that fluctuate.
- **Correlation analysis**: Determine how different species interact with each other within the microbiome.
  
### 🔮 **Predictive Modeling with ARIMAX**
Forecast future changes in the microbiome using **ARIMAX models**, allowing you to predict how microbial communities may evolve under various conditions.

### 🧬 **Longitudinal Data Analysis**
`dynamo_library` is specifically designed for longitudinal studies, where data is collected from the same subjects over multiple time points. It allows users to track the stability and variability of microbial species within each subject, helping to identify which species are stable and which are more susceptible to environmental changes.


## Installation

You can install the latest version of `dynamo_library` from GitHub:

```bash
git clone https://github.com/paula078/dynamo_library.git
cd dynamo_library
pip install -r requirements.txt
```

## Citation
If you use `dynamo_library` in your research, please cite the following publication:

Microbiome time series data reveal predictable patterns of change
Z. Karwowska, P. Szczerbiak, T. Kosciolek.
Published in Microbiology Spectrum, 2024. DOI: 10.1128/spectrum.04109-23.
