# Introduction
This R package was created in the first place to calculate more quickly and easily a lot of formulas (mean, variance, VaR, TVaR, stop-loss function, etc.) related to popular probability distributions, such as :  

- Uniform 
- Binomial
- Exponential
- Gamma
- Pareto
- 



# Formulas convention
I've tried to make the package pretty simple to use, the syntax is based on quite the same as some popular R package, like the [`stats` ](https://stat.ethz.ch/R-manual/R-devel/library/stats/html/00Index.html) or [`actuar`](https://cran.r-project.org/web/packages/actuar/index.html) packages :

|Formulas  | `code`|
|:-----------:|-----------------|
|Mean         |`E_<distribution>` |
|Variance     |`V_<distribution>` |
|stop loss     |`SL_<distribution>` |
|Limited expected value     |`Elim_<distribution>` |
|truncated mean     |`Etronq_<distribution>` |
|$VaR_\kappa$     |`VaR_<distribution>` |
|$TVaR_\kappa$     |`TVaR_<distribution>` |
|Mean Excess-loss    |`Mexcess_<distribution>` |


# Updates
|Date   | modification|
|:-----------:|:---------:|
|24/02/2018 | Intial commit of the package|

