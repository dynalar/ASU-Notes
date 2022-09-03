# Two-Sample T-Test
---
## Quick Synopsis
- This is a test method that tests whether the unknown population means of two groups are equal or not.
- We test two data sets, that are RANDOMLY SAMPLED from two normal populations, and the two independent groups have EQUAL VARIANCES


![[Pasted image 20220903091211.png]]

Legend
---
$N$ = Normal Distribution
$\mu_{1}$ = Mean
${\sigma_{1}}^2$ = Variance

- Above, we are sampling two populations.
	- Both populations are assumed normal.
- The means are different. Variances are about the same.
- If we slide them together, they will look the same
- Sample 1: and Sample 2: are the observations for the populations
- Factor level 1 and 2 show the original and modified mortar concrete recipe.
- Are the sample sizes enough?

Equations - AKA Statistical Hypothesis
---
$H_{0} : \mu_{1} = \mu_{2}$ - If this is true, the distributions overlap, means are the same.
$H_{1} : \mu_{1} \neq \mu_{2}$ - If this is true, then alternative is two sided. Means are not the same.

The math formulas above tell us whether the means are the same or different between $\mu_{1}$ and $\mu_{2}$. 

## Estimation of Parameters
$\bar{y} = \frac 1n \displaystyle \sum_{i=1}^n y_{i}$    -- This estimates the populatiom mean $\mu$

$S^2 = \frac1{n-1}  \displaystyle \sum_{i=1}^n (y_{i} - \bar{y})^2$   -- This estimates the variance ${\sigma^2}$