# portfolio-opt
Implementation of modern portfolio optimization (mean-variance portfolio optimization) using Monte Carlo simulation and sequential least squares programming (scipy package) in Python


In general, portfolio optimization is the process of creating a portfolio of assets, for which your investment has the maximum return and minimum risk.
## Modern Portfolio Theory
**Modern Portfolio Theory**, or also known as mean-variance analysis is a mathematical process which allows the user to maximize returns for a given risk level. Or in other terms, minmize risk for a given return level.

It was introduced in a 1952 doctoral thesis by Harry Markowitz. It assumes that an investor wants to maximize a portfolio's expected return contingent on any given amount of risk. For portfolios that meet this criterion, known as efficient portfolios, achieving a higher expected return requires taking on more risk, so investors are faced with a trade-off between risk and expected return.

In portfolio theory, the riskiness of an asset is often measured by the ***variance*** (or standard deviation) of its returns. Variance is an important indicator of how volatile this investment will be (how returns can fluctuate). Risk-averse investors do not want their wealth to fluctuate wildly.

## Theory
**portfolio return:**

![plot](https://github.com/ebrahimpichka/portfolio-opt/blob/main//img1-ret.png)

**portfolio variance:**

![plot](https://github.com/ebrahimpichka/portfolio-opt/blob/main//img2-var.png)

![plot](https://github.com/ebrahimpichka/portfolio-opt/blob/main//img3-var.png)

matrix form:

![plot](https://github.com/ebrahimpichka/portfolio-opt/blob/main//img4-mat.png)

**efficient portfolio for any particular level of return optimzation problem:**

![plot](https://github.com/ebrahimpichka/portfolio-opt/blob/main//img6-opt.png)
