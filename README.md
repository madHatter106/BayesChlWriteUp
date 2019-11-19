[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/madHatter106/BayesChlWriteUp/master?filepath=Step-3-1-Modeling-1.ipynb)

<h1><center>Bayesian Chlorophyll Project</center></h1>

 
    The purpose of this project is to compare various models predicting chlorophyll (hereafter <u>Chla</u>) using the well established Bayesian inference framework in conjunction with principles of Information Theory. All models examine here make use, in one form or another, of remote sensing reflectance (<u>Rrs</u>) at 443, 490, 510, 555 nm. These models include:
* NASA's "empirical OC<sub>4</sub>, a polynomial regression model where the input is 
* Multivariate linear regression, where Rrs at multiple bands are inputs
* Simple linear model similar to OC<sub>4</sub> but where the MBR input is left at order 1.
* Hierarchical partially pooled model with base formulation similar to that of the above but where the impact of grouping by blue band used in the ratio is taken to account.
* Multivariate linear model where the inputs are the eigenvectors resulting from a Principle Components Analysis of the Rrs bands.

<img src="resources/MY1DMM_CHLORA_2002-07.JPEG">
