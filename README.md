
# From Queries to Care: Exploring Health Information-Seeking Behavior via E-Epidemiology and Econometric Modeling




<p align="center">
  <img src="https://img.shields.io/badge/Stata-17%2F18-lightgrey?logo=stata" />
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python" />
  <img src="https://img.shields.io/badge/License-MIT-green?logo=github" />
  <img src="https://img.shields.io/badge/Version-1.0.0-orange" />
</p>



## 📝 Overview

Chronic diseases account for over 80% of the global disease burden, yet traditional epidemiological methods are resource-intensive and slow. This project proposes a novel **e-epidemiology framework** that integrates real-time digital health data with causal inference techniques for proactive disease monitoring and intervention.

![Workflow](figure4.png)  
*<sub>Figure: Schematic of the integrated e-epidemiology methodology.</sub>*

### 🌟 Key Highlights

- **Real-Time Surveillance:** Leverages daily health-related search data as proxies for disease activity and public concern.
- **Causal Analysis:** Employs vector autoregression (VAR), Granger causality, and impulse response modeling to uncover temporal and causal links.
- **Validation:** Digital signals show strong alignment with traditional epidemiological statistics.
- **Geographical Insights:** Identifies regional variations in medication search patterns.
- **Case Study:** In epilepsy, spikes in related searches precede interest in anxiety, migraine, brain, and heart health.
- **Scalable Framework:** Can be generalized to other chronic diseases and digital data sources.


## 📁 Project Directory Structure

```plaintext
.
├── envs1.yml
├── envs2.txt
├── code/
│   └── analysis/
│       ├── run.ipynb # main code
│       ├── pics/
│       └── result_appendix_12-13/
└── data/
    ├── baidu/
    │   ├── comorbidities/
    │   ├── GBD/
    │   └── organs/
    └── google/
        ├── ASMs/
        ├── comorbidities/
        └── GBD/
```


## 🚀 Setup Guide

###  Development System

- Windows 11

### 1. Install Stata

Install **Stata 17** or **Stata 18** from the official website:  
👉 [https://www.stata.com/](https://www.stata.com/)

### 2. Configure the Environment

Create a Conda environment using the provided `envs1.yaml`:
```bash
conda env create -f envs1.yaml
```

### 3. Run the Analysis

Open and execute the analysis notebook step by step:
- `code/analysis/run.ipynb`



## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.



## 📦 Version

**Current Version:** 1.0.0


## 📧 Contact

For questions, suggestions, or collaborations, please contact us:

- shaleihao@163.com
- hmq0930@163.com
- marco_hefan@foxmail.com

Or open an issue in this repository.



## 📚 Citation

If you use this framework or code, please cite our work:

```

```

