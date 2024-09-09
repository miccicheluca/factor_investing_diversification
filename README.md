# Enhancing Performance Through Diversification: A Study of Factor-Based Portfolios
## Study Overview 
This study investigates the potential performance benefits of diversification within a factor-based portfolio framework. We compare the performance of a diversified portfolio to an equally weighted allocation of factor-based portfolios.

## Data Aquisition
We utilize factor-based portfolio data from [JKP Factors](https://jkpfactors.com/), focusing on US markets (*).

## Reading process

To see the results of this study, here's the parcour:

1. [HRP Explained](https://github.com/miccicheluca/factor_investing_diversification/blob/main/A%20Hierarchical%20Clustering%20(HC)%20approach.pdf): a guide to understand the basics of HRP allocation process
2. [A Hierarchical overview of the factor-based portfolios](https://github.com/miccicheluca/factor_investing_diversification/blob/main/notebook/hc_respect_factors_based_clustering.ipynb)
3. [An overview of all allocation models](https://github.com/miccicheluca/factor_investing_diversification/blob/main/notebook/hc_weighting_per_date.ipynb)
4. [Allocation process results](https://github.com/miccicheluca/factor_investing_diversification/blob/main/notebook/compare_allocation_pnl.ipynb)
5. [Portfolio properties](https://github.com/miccicheluca/factor_investing_diversification/blob/main/notebook/portfolio_properties.ipynb)

## Conclusion of this study

This study focused on factor-based portfolios, aiming to enhance the performance of an equally weighted basket by implementing a dynamic allocation strategy using Hierarchical Risk Parity (HRP).

As demonstrated in previous notebooks, risk-adjusted diversification through HRP has significantly improved portfolio metrics, with an average gain of 2% per year while reducing drawdowns and time under water.

While this study was limited to US factor-based portfolios, future research could extend the HRP approach to factor portfolios from other regions like Europe and Asia. This would not only leverage geographical diversification but also potentially further enhance performance metrics.

Another promising direction is to develop a model-based Reinforcement Learning agent capable of dynamically allocating weights across various allocation models (e.g., HRP [3, 6, 12, 24], HARP [3, 6, 12, 24]). This agent could adapt to changing market conditions, potentially optimizing portfolio performance.

This work is currently in progress.

Note:
(*) To see how each portfolio is build, check the [JKP Factors documentation](https://jkpfactors.s3.amazonaws.com/documents/Documentation.pdf")
