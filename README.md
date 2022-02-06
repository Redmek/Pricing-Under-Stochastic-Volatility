# Pricing-Under-Stochastic-Volatility
Simulation of the Heston Model

Volatility in financial markets is not constant, in direct contradiction to the BlackScholes paradigm. If we look at vanilla option prices with different strike prices and different maturities, we see that their implied volatility is different. Other one-factor models have been developed, for example, local volatility models where the volatility sigma(St, t) is a deterministic function of the underlying price and time, chosen to match observed European option prices exactly. With these models, the market remains complete and it is possible to find a smile structure. In parallel, multi-factor models have been developed, in particular stochastic volatility models where the volatility sigma(t) is modeled as a continuous Brownian semi-martingale always with the aim of reproducing the observed smile observed on the market. In this project we will study the simulaton of the Heston model.

![fig1](https://github.com/Redmek/Pricing-Under-Stochastic-Volatility/blob/main/Images/Delta_Heston.png)
