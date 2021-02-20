# Theory on insurance modelling

### Quick intro
This kind of models are used to evaluate the risk of a customer with the purpose of setting the price of the insurance and minimize the risks for the business. The risk it´s predicted before the premium of the polize is set, these are set in relation to the risk of the customer. 

Different explanatory variables are used and are divided into two groups: **Subject variables**, concerning the person purchasing the insurance, and **object variables**, concerning the object to be insured

### Definition of risk
The chance that something harmful or unexpected could happen. It is defined as the expected value of the relationship between the loss and the exposure (period for which the insurance is valid). 

<img src="https://render.githubusercontent.com/render/math?math=\tau = \EX(\frac{L,e})"> - Pendiente

### Models 
Overall GLM models have a long tradition of use on premium setting, however currently there are other ML models that can be used to perform the same function of classifying this risks. 

Focusing on GLM models to calculate premiums there are different target variables: 
- Claim frequency = claims per exposure
- Claim severity = dollars / euros of loss per claim of ocurrence
- Pure premium = dollas / euros of loss per exposure
- Loss ratio = dollars / euros of loss per dollar of premium 

Overall the predictors can be of two types:
- Related to the driver
- Related to the vehicle

# Weights & Offsets 

# Sources 
https://towardsdatascience.com/basics-of-insurance-pricing-47243c2630b9

