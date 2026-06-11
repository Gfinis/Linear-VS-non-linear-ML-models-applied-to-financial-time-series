# Linear-VS-non-linear-ML-models-applied-to-financial-time-series
The code looks to test if linear models outperform non-linear models when applied to financial time series data. The models tested are linear [OLS, Ridge, Lasso, Elastic Net], and non-linear [Random Forrest, Gradient Boosting, SVR]. The models were default, no extra regularization or hyperparameter tuning. The models were graded based on IC, hit rate, and portfolio sharpe. Backtesing showed each models performace realtive to a buy-hold strategy. 

# Conclusion
While no single model outperformed a buy-hold strategy, the non-linear models on average outperformed the linear models. The random forrest model performed the best, with a suprising IC of 0.073 and sharpe of 1.18. 


This code was mostly generated using claude code
