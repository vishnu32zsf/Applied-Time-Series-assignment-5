# Applied-Time-Series-assignment-5

## (1)
(a) Generate data of size N = 600 for the process : AR(3) = c(0.2,0,0.1)

(b) Build appropriate AR, MA and ARMA models for the generated time series using AIC as model order selection criterion.

(c) Among the best AR, MA and ARMA models obtained in step (b), choose the model which has minimum AIC value.

(d) Repeat the steps (a), (b) and (c) for 100 different noise realizations. How many times does the identified model match with the true process?

(e) Finally, repeat steps (a), (b), (c) and (d) by choosing the sample size as N = 100.


## (2)
(a) For the data given in sarima_data.Rdata, fit a model by the classical approach of decomposing the series into seasonal, trend and stationary components (use the stl routine in R to achieve this decomposition). Fit an ARMA model to the stationary series.

(b) For the same data set, build an appropriate SARIMA model in a systematic manner.


### (3) 
A RV X follows a uniform distribution over the interval [0, θ]. Suppose it is intended to estimate the parameter θ from N independent observations of X using the MLE approach.

(a) Set up the likelihood function for the parameter using N observations.

(b) Determine the theoretical ML estimate of θ.

(c) Plot the likelihood function for the data given in mle_unif.Rdata and determine the optimal estimate of θ.

(d) Compute the theoretical bias in ML estimate.

(e) Finally, do you foresee any challenge if the data were to be instead distributed over [0, θ).


### (4)
(a) Show that there exists no efficient estimator for estimating the parameter λ of a WN process with exponential distribution: f (λ) = λe −λy

(b) For the same process, show that the inverse of the parameter 1/λ can be estimated efficiently.




