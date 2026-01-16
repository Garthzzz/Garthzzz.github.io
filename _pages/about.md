---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Statistics M.A. student (Machine Learning track) at **Columbia University**, contributing to multiple research projects across climate science, computational biology, and quantitative finance. I hold dual bachelor's degrees in Mathematics and Physics from **UC Santa Barbara**.

Before graduate school, I worked as a **Derivatives Analyst at SDIC Securities** in Shanghai, where I backtested trading strategies and built Python tools for exotic options like Snowball structures. That experience grounded my research in real-world applications—quantitative rigor must translate into informed decision-making.

## Research Focus

My research centers on developing **physics-informed symbolic regression** algorithms that discover interpretable equations from noisy, high-dimensional data. The core idea is **PySR-guided E-WSINDy**: using PySR's genetic programming to discover equation structures, then using E-WSINDy's weak-form sparse regression to refine coefficients with rigorous uncertainty quantification. The weak-form integral formulation provides noise robustness by transferring derivatives from noisy data to smooth test functions.

The current framework implements a complete pipeline:
- **Physics-informed feature engineering**: Buckingham Pi dimensional analysis and power-law symmetry detection
- **Dual-track model selection**: PySR for structure discovery + E-WSINDy for sparse regression with a 5-layer augmented feature library
- **Three-layer uncertainty quantification**: structural, parametric, and predictive uncertainty

See the full implementation: [Physics-Informed-Symbolic-Regression](https://github.com/Garthzzz/Physics-Informed-Symbolic-Regression)

At Columbia's [LEAP Center](https://leap.columbia.edu/), I work with Dr. Kara Lamb on applying these methods to warm rain microphysics—discovering interpretable equations for autoconversion and accretion processes from high-dimensional LES simulation data.

What excites me most is the **cross-domain generalizability** of these methods. The same algorithmic innovations that help us understand cloud microphysics can be adapted—with appropriate modifications for low signal-to-noise environments—to predict financial returns or model clinical outcomes. We have made progress applying this framework to finance: given the extremely low SNR characteristic of financial data, we incorporated task-aware wavelet denoising and replaced point estimates with interval-valued coefficients to honestly reflect uncertainty. See our [Financial Symbolic Regression project](https://github.com/Garthzzz/Financial-Symbolic-Regression-with-Uncertainty-Quantification) for more details.

Beyond symbolic regression, I also contribute to several other research projects at Columbia: weakly supervised learning for remote sensing imagery (Prof. Tian Zheng), treatment discontinuation modeling in the CATIE antipsychotic trial (Prof. Kiyohito Iigaya, Zuckerman Institute), and mental imagery phenotype analysis (Dr. Alfredo Spagna).

## Research Interests

- **Applied Focus**: I am drawn to research that bridges methodological innovation with real-world impact—developing algorithms that not only advance theory but solve practical problems
- **Symbolic Regression & Equation Discovery**: Noise-robust algorithms (E-WSINDy, constrained SR), uncertainty quantification, physics-informed constraints
- **Machine Learning**: Weakly supervised learning, dimensionality reduction, clustering, factor analysis
- **Applications**: Climate science, quantitative finance, computational biology, clinical trials

## Beyond Academics

Outside of research, I'm a sports enthusiast—I love soccer, basketball, hiking, and cycling.

In soccer, I served as Captain of CCST Future during the Spring 2025 season—a team under the Columbia Chinese Student Soccer Team designed for beginners and hobbyists. I create space for newcomers to find their footing in a new city, organizing training for players of varying skill levels and fostering an environment where competition coexists with mutual support. I am also a committee member and player for CCST's competitive main squad, where I coordinated logistics off the field and competed on it—winning the **Penn Cup Championship** together in March 2025.

I'm also an NBA fan and a devoted Memphis Grizzlies supporter. Dissatisfied with existing advanced metrics, I developed my own player impact model in 2025: the [Bayesian Enhanced Baseline-and-Residual Model (BEBRM)](https://github.com/Garthzzz/nba-BEBRM). Unlike traditional metrics that rely heavily on box-score statistics or pure on/off differentials, BEBRM integrates non-traditional data sources (defensive matchup outcomes, hustle stats, Synergy play-type efficiencies) into a Bayesian prior baseline, then applies iterative possession-level residual corrections. The model provides explicit uncertainty quantification through credible intervals—particularly valuable for evaluating players with limited sample sizes.

![CCST Penn Cup Champions](/images/penncup.jpg)


## Contact

Feel free to reach out at [zhangzhengze2018@gmail.com](mailto:zhangzhengze2018@gmail.com)
