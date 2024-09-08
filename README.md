# SummerSchool 23: Time Series Analysis & Generative AI

## Introduction

Welcome to the SummerSchool 23 course on Time Series Analysis and Generative AI at Hochschule Karlsruhe! This course aims to provide an in-depth understanding of two of the most transformative areas in artificial intelligence and data science: Time Series Analysis and Generative AI.

### Why Time Series Analysis?

Time series data are ubiquitous in real-world applications. Whether it's stock market data, climate trends, healthcare records, or sensor readings in industrial settings, the ability to analyze and make predictions based on time-series data is crucial. This course will offer you the tools to perform advanced analytics, feature engineering, and create predictive models.

### Why Generative AI?

Generative AI is at the frontier of artificial intelligence research and has been responsible for some of the most exciting developments in the field. From creating realistic images, videos, and voice recordings to generating text and even composing music, generative models have wide-ranging applications. Understanding the principles behind these models is vital for anyone interested in the future of AI.

## Course Details

- **Location**: Hochschule Karlsruhe
- **Duration**: 16 units a 1.5h
- **Instructor**: Lukas Theurer
- **Prerequisites**: Basic understanding of Machine Learning Concepts and Programming

## Modules

1. **Basics of Time Series Analysis**
   - Use-Cases
   - Components: Trend, Seasonality & Error
   - Decompoisiton Methods
   - Autocorellation



## Getting Started

To get started with the course materials, please clone the repository and follow the installation instructions in each module's README.

**Info**: If you are using a Mac with M1/2 Chip, you need to ensure that your conda environment is created using rosetta. Otherwise, there will be some issues with the forecasting libraries.

### Automatic setup (only x86)
```bash
git clone https://github.com/LackesLab/summerschool_23.git
```

```bash
conda env create -f environment.yml
conda activate summerschool
```

### Automatic Setup 

#### X86
```bash
conda create -n summerschool python=3.10
conda activate summerschool

pip install poetry
poetry install
```

#### Mac M1/M2
```bash
CONDA_SUBDIR=osx-64 conda create -n summerschool python=3.10
conda activate summerschool
conda config --env --set subdir osx-64

pip install poetry
poetry install
```

### Manual setup (Mac M1/M2)
```bash
CONDA_SUBDIR=osx-64 conda create -n summerschool python=3.11
conda activate summerschool
conda config --env --set subdir osx-64
conda install -c conda-forge -c pytorch u8darts-all jupyterlab
conda install -c conda-forge jupyterlab
conda install -c conda-forge statsmodels
```

### Manual / Pip install
```bash
git clone https://github.com/LackesLab/summerschool_23.git
```
1. Create a python environment with version `python=3.11`
2. Install the following packages:
``` text
jupyter
u8darts-all
statsmodels
pandas
numpy
plotly
matplotlib
```