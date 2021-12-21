# Simulation-and-Analysis-of-Stock-Pricing-Techniques

In this project, we have simulated and analysed three Mathematical Models for Stock Price Predictions:- 
* **Geometric Brownian Motion**
* **Merton-Jump Diffusion** 
* **Heston Process** 

The three models have been compared by applying them on two datasets:- 
* **Apple Stock Price Dataset**
* **Intel Stock Price Dataset**

A Geometric Brownian Motion (GBM), also known as Exponential Brownian Motion, is a continuous-time stochastic process in which the logarithm of the randomly varying quantity follows a Brownian motion (also called a Wiener process) with drift. However, GBM is not a completely realistic model since volatility is assumed to be constant and path taken is assumed to be continuous i.e. no jumps are considered. A more realistic model should consist of jump component to better simulate true nature of a process. The best-known model of this type in finance is the Merton-Jump Diffusion model. This model superimposes a jump component on a diffusion component. Heston model is a mathematical model describing the evolution of the volatility of an underlying asset. It is a stochastic volatility model, which assumes that the volatility of the asset is not constant, nor even deterministic, but follows a random process. 

Monte Carlo Simulations:
* Geometric Brownian Motion (GBM)

![image](https://user-images.githubusercontent.com/42888030/146948946-5257849a-c0c1-4b7d-b1c9-22ed5676d102.png)
![image](https://user-images.githubusercontent.com/42888030/146949282-720679ff-b05e-4bf0-a6bb-5f882318811e.png)
![image](https://user-images.githubusercontent.com/42888030/146949439-bff3c61d-4c83-40ec-bb2c-7e251c471c9a.png)
