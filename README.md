# WM9QE-ASAI
WMG MSc Applied Artificial Intelligence: Applied Statistics to Artificial Intelligence

# Applied Statistics for Artificial Intelligence (MSc AAI, WMG)

Welcome to the **Applied Statistics for Artificial Intelligence** repository.
This repository consolidates all **MATLAB teaching materials, tutorials, datasets, and scripts** used in the **Applied Statistics for AI** module within the **MSc in Applied Artificial Intelligence** programme at **WMG, University of Warwick**.

It provides practical examples, reusable code, and guided notebooks designed to help students **understand, implement, and visualise statistical concepts in AI workflows**.

---

## Module Overview

**Applied Statistics for Artificial Intelligence** introduces students to statistical foundations that underpin modern AI and machine learning systems.
Through a blend of theory and practice, students learn to:

* Understand and apply descriptive and inferential statistics.
* Implement various **sampling techniques** for data collection and quality assurance.
* Explore **data distributions** and hypothesis testing in the context of AI.
* Generate and validate **synthetic data** using statistical and simulation approaches.
* Develop statistical reasoning and evaluate data-driven AI models critically.

---

## 📂 Repository Structure (TBD) Example below.

```
Applied-Statistics-for-AI/
│
├── README.md                         ← You are here
│
├── datasets/                         ← Example datasets used in tutorials
│   ├── iris.csv
│   ├── patient_data.csv
│   └── ...
│
├── sampling_techniques/              ← MATLAB scripts for data sampling
│   ├── section2_srs_sampling.m
│   ├── section3_stratified_sampling.m
│   ├── section4_cluster_sampling.m
│   └── compare_sampling_methods.m
│
├── distribution_analysis/            ← Scripts and live scripts for distributions
│   ├── gaussian_distribution.mlx
│   ├── hypothesis_testing.mlx
│   ├── correlation_regression.mlx
│   └── ...
│
├── synthetic_data/                   ← Distribution- and simulation-based examples
│   ├── distribution_based.mlx
│   ├── simulation_based_projectile.m
│   ├── synthetic_data_validation.mlx
│   └── ...
│
├── lab_tutorials/                    ← Structured lab exercises (Live Scripts)
│   ├── Lab1_DescriptiveStats.mlx
│   ├── Lab2_SamplingMethods.mlx
│   ├── Lab3_Distributions.mlx
│   ├── Lab4_SyntheticData.mlx
│   └── ...
│
├── figures/                          ← Exported figures and diagrams for teaching
│   ├── gaussian_2d.png
│   ├── sampling_bias_visual.png
│   └── ...
│
└── utilities/                        ← Reusable MATLAB functions and helpers
    ├── compute_SE_MOE_CV.m
    ├── plot_distributions.m
    ├── generate_synthetic_data.m
    └── ...
```

---

## MATLAB Live Script Tutorials

Each **.mlx** file includes:

* Conceptual explanations (with LaTeX equations).
* Step-by-step code demonstrations.
* Graphical outputs for interpretation.
* Short tasks or challenges for independent learning.

Examples:

* `distribution_based.mlx` — explores fitting data to statistical distributions and sampling synthetic observations.
* `simulation_based_projectile.m` — generates physics-based simulation data for AI model training.
* `section3_stratified_sampling.m` — demonstrates stratified sampling with comparisons of SE, MOE, and CV metrics.

---

## Topics Covered

| Unit | Topic                                  | Key Concepts                                      |
| ---- | -------------------------------------- | ------------------------------------------------- |
| 1    | Introduction to Statistics for AI      | Populations, Samples, Random Variables            |
| 2    | Descriptive Statistics & Visualisation | Mean, Variance, Skewness, Histograms              |
| 3    | Sampling Techniques                    | SRS, Stratified, Cluster, Systematic, Reservoir   |
| 4    | Probability Distributions              | Normal, Binomial, Poisson, Uniform                |
| 5    | Statistical Inference                  | Hypothesis Testing, Confidence Intervals          |
| 6    | Correlation and Regression             | Covariance, Linear Models, R²                     |
| 7    | Synthetic Data Generation              | Distribution-based and Simulation-based Methods   |
| 8    | Data Validation & Bias                 | K-S Test, MMD, Privacy, Fairness, Drift Detection |

---

## Requirements

**Software:**

* MATLAB **R2023b** or later
* Statistics and Machine Learning Toolbox

**Recommended Hardware:**

* Minimum 8 GB RAM
* For simulation tasks: CPU ≥ 2.0 GHz (multi-core)
* Optional: GPU support for large synthetic datasets

---

## Getting Started

1. **Clone this repository**

   ```bash
   git clone https://github.com/WMG-AI/Applied-Statistics-for-AI.git
   cd Applied-Statistics-for-AI
   ```

2. **Open MATLAB and set the working directory**

   ```matlab
   cd('path_to_downloaded_repo')
   ```

3. **Explore tutorials**

   * Open `.mlx` files to follow guided explanations.
   * Run `.m` files section by section to observe results interactively.

---

## Learning Resources

**Essential Reading**

* Montgomery, D. C., & Runger, G. C. (2020). *Applied Statistics and Probability for Engineers*. Wiley.
* Field, A. (2021). *Discovering Statistics Using MATLAB*. Sage.

**Recommended**

* Bishop, C. M. (2006). *Pattern Recognition and Machine Learning*. Springer.
* Hastie, T., Tibshirani, R., & Friedman, J. (2017). *The Elements of Statistical Learning*. Springer.
* Gelman, A. et al. (2020). *Bayesian Data Analysis*. CRC Press.

---

## Academic Context

This repository supports teaching within:

* **MSc Applied Artificial Intelligence** (Course Director: Dr. Leonardo Alves)
* **WMG, University of Warwick**

It complements the module’s lecture slides, live labs, and independent study materials available on **Moodle**.

---


## License

This repository is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.
You are free to use, adapt, and share for **educational and non-commercial purposes** with attribution.

---

## Contact

For queries, suggestions, or feedback:
**Dr. Leonardo Alves**
Assistant Professor & Course Director, MSc Applied Artificial Intelligence
WMG, University of Warwick
📧 [leonardo.alves@warwick.ac.uk](mailto:leonardo.alves@warwick.ac.uk)

---

Would you like me to tailor this README for **Warwick’s internal repository structure** (e.g., include Moodle integration links, WMG branding line, or module code like “ASAI-M01”)? I can format it for direct GitHub publishing with Warwick-style headers and licensing text if desired.

