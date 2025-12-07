# A Collection of Causal Literature

A curated reading list of papers on causal inference, causal machine learning, and selected classic works in statistics and ML.

## Table of Contents

- [Books](#books)
- [Heterogeneous Treatment Effects](#heterogeneous-treatment-effects)
- [Sensitivity Analysis](#sensitivity-analysis)
- [Proximal and Multivariate Causal Inference](#proximal-and-multivariate-causal-inference)
- [Spatial Confounding](#spatial-confounding)
- [Panel Data](#panel-data)
- [Causal Representation Learning and Invariance](#causal-representation-learning-and-invariance)
- [Misc](#misc)

## Books

- [Applied Causal Inference Powered by ML and AI](https://causalml-book.org/) - Chernozhukov, Hansen, Kallus, Spindler, Syrgkanis (2024)

- [A First Course in Causal Inference](https://arxiv.org/pdf/2305.18793.pdf) - Ding (2023)

- [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) - Hernán, Robins (2020)

- [Causal Inference in Statistics: A Primer](https://www.wiley.com/en-us/Causal+Inference+in+Statistics%3A+A+Primer-p-9781119186847) - Pearl, Glymour, Jewell (2016)

- [Causal Inference for Statistics, Social, and Biomedical Sciences](https://www.cambridge.org/core/books/causal-inference-for-statistics-social-and-biomedical-sciences/71126BE90C58F1A431FE9B2DD07938AB) - Imbens, Rubin (2015)

- [Data Analysis Using Regression and Multilevel/Hierarchical Models](https://www.cambridge.org/highereducation/books/data-analysis-using-regression-and-multilevel-hierarchical-models/32A29531C7FD730C3A68951A17C9D983#overview) - Gelman, Hill (2006)

## Heterogeneous Treatment Effects

- [Double Debiased Machine Learning Nonparametric Inference with Continuous Treatments](https://www.tandfonline.com/doi/full/10.1080/07350015.2025.2505487#abstract) - Colangelo and Lee (2025, JBES)

- [Towards Optimal Doubly Robust Estimation of Heterogeneous Causal Effects](https://arxiv.org/pdf/2004.14497.pdf) - Kennedy (2023)
  
- [Quasi-Oracle Estimation of Heterogeneous Treatment Effects](https://arxiv.org/pdf/1712.04912.pdf) - Nie and Wager (2020)
  
- [Bayesian Regression Tree Models for Causal Inference: Regularization, Confounding, and Heterogeneous Effects (with Discussion)](https://projecteuclid.org/journals/bayesian-analysis/volume-15/issue-3/Bayesian-Regression-Tree-Models-for-Causal-Inference--Regularization-Confounding/10.1214/19-BA1195.full) - Hahn, Murray, Carvalho (2020)
  
- [Meta-learners for Estimating Heterogeneous Treatment Effects using Machine Learning](https://arxiv.org/pdf/1706.03461.pdf) - Künzel, Sekhon, Bickel, Yu (2019)
  
- [Automated versus Do-It-Yourself Methods for Causal Inference: Lessons Learned from a Data Analysis Competition](https://projecteuclid.org/journals/statistical-science/volume-34/issue-1/Automated-versus-Do-It-Yourself-Methods-for-Causal-Inference/10.1214/18-STS667.full) - Dorie et al. (2019)
  
- [Estimation and Inference of Heterogeneous Treatment Effects using Random Forests](https://www.tandfonline.com/doi/full/10.1080/01621459.2017.1319839) - Wager and Athey (2018)
  
- [Estimating individual treatment effect: generalization bounds and algorithms](https://proceedings.mlr.press/v70/shalit17a.html) - Shalit, Johansson, Sontag (2017)
  
- [Double/Debiased Machine Learning for Treatment and Structural Parameters](https://arxiv.org/pdf/1608.00060.pdf) - Chernozhukov, Chetverikov, Demirer, Duflo, Hansen, Newey, Robins (2017)
  
- [Bayesian Nonparametric Modeling for Causal Inference](https://www.tandfonline.com/doi/abs/10.1198/jcgs.2010.08162) - Hill (2011)

## Sensitivity Analysis
  
- [Sensitivity Analysis of Individual Treatment Effects: A Robust Conformal Inference Approach](https://www.pnas.org/doi/10.1073/pnas.2214889120) - Jin, Ren, Candès (2023, PNAS)

- [Long Story Short: Omitted Variable Bias in Causal Machine Learning](https://arxiv.org/abs/2112.13398) - Chernozhukov, Cinelli, Newey, Sharma, Syrgkanis (2024)

- [Making Sense of Sensitivity: Extending Omitted Variable Bias](https://academic.oup.com/jrsssb/article/82/1/39/7056023) - Cinelli and Hazlett (2020, JRSS-B)

- [Sensitivity Analysis for Inverse Probability Weighting Estimators via the Percentile Bootstrap](https://academic.oup.com/jrsssb/article/81/4/735/7048357) - Zhao, Small, Bhattacharya (2019, JRSS-B)

- [Sensitivity Analysis in Observational Research: Introducing the E-Value](https://www.acpjournals.org/doi/full/10.7326/M16-2607) - VanderWeele and Ding (2017, Ann Intern Med)

- [A Distributional Approach for Causal Inference Using Propensity Scores](https://www.tandfonline.com/doi/abs/10.1198/016214506000000023) - Tan (2006, JASA)

- [Assessing Sensitivity to an Unobserved Binary Covariate in an Observational Study with Binary Outcome](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/j.2517-6161.1983.tb01242.x) - Rosenbaum and Rubin (1983, JRSS-B)

- [Smoking and Lung Cancer: Recent Evidence and a Discussion of Some Questions](https://academic.oup.com/jnci/article/22/1/173/912572) - Cornfield et al. (1959, JNCI)

## Proximal and Multivariate Causal Inference

- [Semiparametric Proximal Causal Inference](https://www.tandfonline.com/doi/full/10.1080/01621459.2023.2191817) - Cui et al. (2024, JASA)

- [An Introduction to Proximal Causal Learning](https://arxiv.org/pdf/2009.10982.pdf) - Tchetgen Tchetgen, Ying, Cui, Shi, Miao (2020)
  
- [A Selective Review of Negative Control Methods in Epidemiology](https://link.springer.com/article/10.1007/s40471-020-00243-4) - Shi, Miao, Tchetgen Tchetgen (2020, Curr. Epidemiol. Rep.)

- [Identifying Causal Effects With Proxy Variables of an Unmeasured Confounder](https://arxiv.org/pdf/1609.08816.pdf) - Miao, Geng, Tchetgen Tchetgen (2018, Biometrika)

- [On Multi-Cause Causal Inference with Unobserved Confounding:
Counterexamples, Impossibility, and Alternatives](https://proceedings.mlr.press/v89/d-amour19a.html) - D’Amour (2019, AISTATS)

- [The Blessings of Multiple Causes](https://www.tandfonline.com/doi/full/10.1080/01621459.2019.1686987) - Wang and Blei (2019, JASA)

## Spatial Confounding

- [A Causal Inference Framework for Spatial Confounding](https://arxiv.org/pdf/2112.14946.pdf) - Gilbert, Datta, Casey, Ogburn (2023)

- [Spatial+: A novel approach to spatial confounding](https://onlinelibrary.wiley.com/doi/full/10.1111/biom.13656) - Dupont, Wood, Augustin (2022)

- [A Review of Spatial Causal Inference Methods for Environmental and Epidemiological Applications](https://onlinelibrary.wiley.com/doi/full/10.1111/insr.12452) - Reich et al. (2021)

- [Mitigating Unobserved Spatial Confounding when Estimating the Effect of Supermarket Access on Cardiovascular Disease Deaths](https://arxiv.org/pdf/1907.12150.pdf) - Schnell, Papadogeorgou
 (2020)

## Panel Data

- [Estimating the effects of a California gun control program with Multitask Gaussian Processes](https://arxiv.org/pdf/2110.07006.pdf) - Ben-Michael, Arbour, Feller, Franks, Raphael (2023)

- [On the Assumptions of Synthetic Control Methods](https://proceedings.mlr.press/v151/shi22b.html) - Shi, Sridhar, Misra, Blei (2022)

- [Theory for identification and Inference with Synthetic Controls: A Proximal Causal Inference Framework](https://arxiv.org/pdf/2108.13935) - Shi et al. (2021)

- [Using Synthetic Controls: Feasibility, Data Requirements, and Methodological Aspects](https://pubs.aeaweb.org/doi/pdfplus/10.1257/jel.20191450) - Abadie (2021)

- [A Penalized Synthetic Control Estimator for Disaggregated Data](https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1971535) -  Abadie and L'hour (2021)

- [The Augmented Synthetic Control Method](https://www.tandfonline.com/doi/full/10.1080/01621459.2021.1929245?scroll=top&needAccess=true) - Ben-Michael, Feller, Rothstein (2021)

- [Inferring causal impact using Bayesian structural time-series models](https://arxiv.org/pdf/1506.00356.pdf) - Brodersen et al. (2015), [CausalImpact package](https://google.github.io/CausalImpact/CausalImpact.html)
  
- [Synthetic Control Methods for Comparative Case Studies: Estimating the Effect of California’s Tobacco Control Program](https://www.tandfonline.com/doi/abs/10.1198/jasa.2009.ap08746) - Abadie, Diamond, Hainmueller (2010)

## Causal Representation Learning and Invariance

- [Desiderata for Representation Learning: A Causal Perspective](https://arxiv.org/pdf/2109.03795.pdf) - Wang and Jordan (2021)

- [Toward Causal Representation Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9363924) - Schölkopf et al. (2021)

- [Counterfactual Invariance to Spurious Correlations: Why and How to Pass Stress Tests](https://arxiv.org/pdf/2106.00545.pdf) - Veitch, D'Amour, Yadlowsky, Eisenstein (2021)

- [A Meta-Transfer Objective for Learning to Disentangle Causal Mechanisms](https://arxiv.org/pdf/1901.10912.pdf) -  Bengio et al. (2019)

- [Causal Inference by using Invariant Prediction: Identification and Confidence Intervals](https://academic.oup.com/jrsssb/article/78/5/947/7040653) - Peters, Bühlmann, Meinshausen (2016)

## Misc

- [Prediction-Powered Causal Inferences](https://arxiv.org/abs/2502.06343) - Cadei et al. (2025, NeurIPS)
 
- [Bayesian causal inference: a critical review](https://royalsocietypublishing.org/doi/full/10.1098/rsta.2022.0153) - Li, Ding, Mealli (2022)

- [A Crash Course in Good and Bad Controls](https://journals.sagepub.com/doi/full/10.1177/00491241221099552) - Cinelli, Forney, Pearl (2022)
  
- [Algorithmic Fairness: Choices, Assumptions, and Definitions](https://www.annualreviews.org/doi/pdf/10.1146/annurev-statistics-042720-125902) - Mitchell et al. (2021)
   
- [The Central Role of the Propensity Score in Observational Studies for Causal Effects](https://academic.oup.com/biomet/article/70/1/41/240879) - Rosenbaum and Rubin (1983)
