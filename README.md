# Why are petrol prices so expensive? 
During Sydney's second lockdown in 2020, retail fuel prices were soaring. Seeing as I was in lockdown and had a lot of spare time, I wanted to investigate and see whether I could build a model that could accurately describe and potentially forecast Sydney petrol prices to maximise fuel savings using R. 

The following time series model used to fit to the data were: NAIVE, ETS and ARIMA models. I succeeded building all 3 models with the ARIMA model being the most accurate. 

At the moment I am attempting to build a more technical model using regressors for a dynamic regression model. As mentioned by the ACCC in (https://www.accc.gov.au/consumers/petrol-diesel-lpg/about-fuel-prices#what-affects-fuel-prices-) potential regressors I have access to data include: 1) AU/US FX rates AND 2) Terminal Gas Prices (TGP). Currently, two additional regressors I am attempting to fit in the model will be 1) the lags of FX rates and 2) the lags of TGP. 

NOTE: the fpp3 package will be required for the code to run  
