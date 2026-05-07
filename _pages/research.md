---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
## Publications
### [Wild Bootstrap Inference with Multiway Clustering and Serially Correlated Time Effects](https://www.tandfonline.com/doi/full/10.1080/07350015.2025.2546454)

(with K. Ulrich Hounyo) 2025  [MATLAB](https://drive.google.com/file/d/12FaOfkZU--zrd61438ZhZxyFV5HCBINf/view?usp=share_link)

<details>

<summary>Abstact</summary>

   This paper studies wild bootstrap-based inference for regression models with multiway clustering. Our proposed method is a multiway counterpart to the (one-way) wild cluster bootstrap approach introduced by Cameron et al. (2008). We establish the validity of our method for studentized statistics. Theoretical results are provided, accommodating arbitrary serial dependence in the common time effects -- an aspect excluded by existing two-way bootstrap-based approaches. Simulation experiments document the potential for enhanced inference with our novel approach. We illustrate the effectiveness of the method by revisiting empirical studies involving multiway clustered and correlated data.

</details>

### [Can Mutual Fund ‘Stars’ Really Pick Stocks? New Evidence From a Wild Bootstrap Analysis​](https://www.sciencedirect.com/science/article/abs/pii/S0927539825000957)

(with K. Ulrich Hounyo)
2025

<details>

<summary>Abstact</summary>

This paper introduces a novel approach called wild bootstrapping for analyzing mutual fund performance. Our proposed method preserves various characteristics of mutual fund databases, including entry/exit points for each fund (i.e., missing data) and cross-sectional information. We show that our proposed bootstrap tests have a near-optimal size and exhibit greater power compared to widely used standard bootstrap methods for evaluating mutual fund performance. Additionally, we present a novel approach to picking mutual funds that do not underperform others. Our empirical results indicate that a measurable fraction of funds outperform the market. Furthermore, we extend our methods to assess mutual fund market timing abilities.

</details>


## Working Papers 

### [Bootstrap Inference under General Two-way Cluster Dependence with Serially and Spatially Dependent Common Effects](https://arxiv.org/abs/2605.00709)

(with K. Ulrich Hounyo)
2025 [MATLAB](https://drive.google.com/file/d/1Do9v6XBE5gFe26wVe6dCtre-s35wEC91/view?usp=share_link)

<details>

   <summary>   Abstract</summary>

This paper develops bootstrap procedures for inference in linear regression models with two-way clustered data. We characterize the estimator's asymptotic behavior in five mutually exclusive and exhaustive regimes: three Gaussian and two non-Gaussian. We establish four impossibility results: heterogeneous score components preclude uniform consistency; uniform consistency also fails in one non-Gaussian (infeasible) regime; the infeasible regime is not uniformly distinguishable from a feasible one; and uniform validity over all feasible regimes rules out uniform conservativeness over the infeasible regime.

To address the feasible regimes, we propose a data-driven regime classifier and a projection-based wild bootstrap procedure. The procedure delivers uniformly valid inference across the four feasible regimes while allowing serial dependence along the second clustering dimension and spatial dependence along the first. This combination of regime adaptivity and flexible dependence is new to the two-way clustering literature. Monte Carlo simulations confirm the accuracy and flexibility of the proposed methods in settings with complex clustering structures.

</details>


### [Jackknife Variance Estimators for Two-Way Clustering with Serially Correlated Time Effects](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5046919)

(with K. Ulrich Hounyo) 
2026 [MATLAB](https://drive.google.com/file/d/1qDJG9H4pii5RpUt-jIYIPJ5H2E8hPTVy/view?usp=sharing)  [Stata](https://drive.google.com/file/d/1j4DYWiTqHxaZIPidARXHQGVdr7-jSJNy/view?usp=sharing)



<details>

   <summary>   Abstract</summary>

Chiang, Hansen, and Sasaki (2024) and Chen and Vogelsang (2024) developed cluster-robust variance estimators (CRVEs) for handling arbitrary serial dependence in linear regressions with two-way clustered panel data. However, conventional CRVEs often perform poorly in finite samples. We propose improved jackknife CRVEs to enhance inference accuracy. Through extensive simulations, we show that the novel jackknife CRVEs deliver remarkably precise inferences. This strong performance holds even in the presence of two-way  fixed effects. Notably, one of our new approaches significantly mitigates issues of undefined standard errors when CRVEs are not positive definite, ensuring robust and consistent inference across scenarios.

</details>




### [Two-way Clustering Robust Variance Estimator in Quantile Regression Models](https://arxiv.org/abs/2602.16376)

(with K. Ulrich Hounyo) 
2026 [MATLAB](https://drive.google.com/file/d/1KeFXdTPAXa3iXTwqTApt4SWIljcjDi4L/view?usp=sharing)  [Stata](https://drive.google.com/file/d/1i_sEuy3lDVZWswrktqWbKTBuFZWMfqxm/view?usp=sharing)


<details>

   <summary>   Abstract</summary>

We study inference for linear quantile regression with two-way clustered data. Using a separately exchangeable array framework and a projection decomposition of the quantile score, we characterize regime-dependent convergence rates and establish a self-normalized Gaussian approximation. We propose a two-way cluster-robust sandwich variance estimator with a kernel-based density ``bread'' and a projection-matched ``meat'', and prove consistency and validity of inference in Gaussian regimes. We also show an impossibility result for uniform inference in a non-Gaussian interaction regime.

</details>


### [Estimation and Inference for the $\tau$-Quantile of Individual-Specific Heterogeneous Coefficients](https://arxiv.org/abs/2605.01923)

(with Antonio F. Galvao and K. Ulrich Hounyo) 
2026 [MATLAB](https://drive.google.com/file/d/1CamFBjVdSqV1ETUoq71dgcf5pw4r_Ajx/view?usp=sharing)


<details>

   <summary>   Abstract</summary>

This paper proposes estimation and inference procedures for the quantiles of individual heterogeneous slope coefficients within panel data. We develop a two-step quantile estimation framework for analyzing heterogeneity in individual coefficients. Unlike conventional panel quantile regression, which focuses on outcome heterogeneity, our approach targets the $\tau$-quantile of the cross-sectional distribution of individual-specific slopes. We establish asymptotic theory under both stochastic and deterministic designs, with convergence rates $\sqrt{N}$ and $\sqrt{N\sqrt{T}}$, respectively. We also develop two corresponding bootstrap procedures for practical inference, and formally establish their validity. The suggested methods are of practical interest since they require weaker sample size growth conditions than standard fixed-effect quantile regression, and accommodate large $N$ settings. Numerical simulations and an application to mutual fund performance illustrate the proposed methods and the heterogeneity patterns they reveal across quantiles.

</details>




