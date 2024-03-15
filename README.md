gsMAMS
==============
[![CRAN](http://www.r-pkg.org/badges/version/gsMAMS)](http://cran.rstudio.com/package=gsMAMS) 
[![Downloads](http://cranlogs.r-pkg.org/badges/gsMAMS?color=brightgreen)](http://www.r-pkg.org/pkg/gsMAMS)
 

**ggMAMS** R package provides a good platform for designing and planning trials with multiple treatment arms. The package provides functionality for designing trials with continuous, ordinal
and survival outcomes which offers great flexibility and makes it a comprehensive toolkit to handle different kinds of trials.


Installation
------------

#### Install from CRAN

The stable version of **gsMAMS**, v0.7.1, is available on CRAN:
```r
install.packages("gsMAMS")
library(gsMAMS)
```

Usage
------------

```r
#For designing a trial with continuous outcome.
design_cont(delta0 = 0.178,delta1 = 0.545,alpha = 0.05,beta = 0.1,K=3, frac = c(0.5,1))

#Generating operating characteristics of the trial.
op_power_cont(alpha=0.05,beta=0.1,K=3,frac=c(0.5,1),delta0=0.178, delta1=0.545,nsim=10000,seed=10)
```
For detailed usage of the package, please see the paper in the repository.

Issues and Contribution
-------------------------------------------

If you want to contribute to the code or file an issue, we prefer them to be handled via GitHub (link to the issues page for
`gsMAMS` [here](https://github.com/Tpatni719/gsMAMS/issues)). You can also contact us via email (see the DESCRIPTION file).