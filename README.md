
# Application of Thompson Sampling In Web Advertisement Filtering Wiki

Welcome to the wiki page for the bachelor thesis project "Application of Thompson Sampling In Web Advertisement Filtering"! This repository is a comprehensive resource for explicitly understanding the work done.

## Table of Contents

1. **Introduction**
2. **Project Overview**
3. **Installation**
4. **Contact**

## 1. Introduction

Digital marketing has demonstrated a significant growth in popularity during the last decade due to the huge variety of possibilities and flexibility the online advertisement platforms offer. However, profitability and competitiveness in such an environment require efficient resource management and adaptation to the fast-changing customer behavior and interests. Effective advertisement allocation and optimal spending control form the primary problem this work seeks to resolve. The thesis considers the aforementioned setup as one that can be solved as the Multi-Armed Bandit problem using the Thompson Sampling algorithm. The work utilizes the modified principles of the aforementioned approaches to construct the advertisement filtering algorithm and evaluate its performance on real-life data.

## 2. Project Overview

The bachelor thesis titled "Application of Thompson Sampling In Web Advertisement Filtering" explores the implementation of the Thompson Sampling technique within the Multi-Armed Bandit framework to effectively manage online advertisement placements. Key files include:

- `config.json` contains all the necessary setups for data processing, model training, and evaluation of key processes. 
- `model.ipynb` is responsible for classifier model training, tuning and evaluation.
- `process.ipynb` processes the raw data for further utilization.
- `filtering-algorithm.ipynb` is responsible for filtering algorithm evaluation & the experimental part, described in the thesis.

Due to a Non-Disclosure Agreement (NDA), the actual data used in the project cannot be openly published. As such, only the structure of the data is provided in the `raw/` and `processed/` directories to give an idea of the data formatting without revealing sensitive information.

- `models/model_parameters.pkl` saves the trained models.
- `raw/` contains an example of raw data structure.
- `processed/` contains an example of a processed data structure.


## 3. Installation

To set up the project locally, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/notnormasatall/web-ads-filtering-with-ts.git
   ```
2. Navigate to the project directory:
   ```
   cd web-ads-filtering-with-ts
   ```

## 4. Contact

For any inquiries or further discussion regarding the project, feel free to reach out through the repository's Issues section or directly via email: taras.rodzin@gmail.com

