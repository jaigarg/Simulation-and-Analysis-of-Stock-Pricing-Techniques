# Simulation-and-Analysis-of-Stock-Pricing-Techniques

In this project, we have simulated and analysed three Mathematical Models for Stock Price Predictions:- 
* **Geometric Brownian Motion**
* **Merton-Jump Diffusion** 
* **Heston Process** 

The three models have been compared by applying them on two datasets:- 
* **Apple Stock Price Dataset**
* **Intel Stock Price Dataset**

<p align= "justify">A <strong>Geometric Brownian Motion (GBM)</strong>, also known as Exponential Brownian Motion, is a continuous-time stochastic process in which the logarithm of the randomly varying quantity follows a Brownian motion (also called a Wiener process) with drift. However, GBM is not a completely realistic model since volatility is assumed to be constant and path taken is assumed to be continuous i.e. no jumps are considered. A more realistic model should consist of jump component to better simulate true nature of a process. The best-known model of this type in finance is the <strong>Merton-Jump Diffusion model</strong>. This model superimposes a jump component on a diffusion component. <strong>Heston Process Model</strong> is a mathematical model describing the evolution of the volatility of an underlying asset. It is a stochastic volatility model, which assumes that the volatility of the asset is not constant, nor even deterministic, but follows a random process. </p>

**Monte Carlo Simulations**:
* Geometric Brownian Motion (GBM)

![image](https://user-images.githubusercontent.com/42888030/146948946-5257849a-c0c1-4b7d-b1c9-22ed5676d102.png)

* Merton Jump Diffusion Process

![image](https://user-images.githubusercontent.com/42888030/146949755-70c66fbb-b93e-45b9-b029-2dc961dea69e.png)

* Heston Process

![image](https://user-images.githubusercontent.com/42888030/146949805-c3763730-2c4d-4e43-a5a5-5ba794b1179c.png)

**Comparative Results**:
* Apple Stock Price Prediction

![image](https://user-images.githubusercontent.com/42888030/146949918-cf8c14ba-aacd-4ca1-b803-3ec2c6af0d74.png)

* Intel Stock Price Prediction

![image](https://user-images.githubusercontent.com/42888030/146950016-e1738d9a-e5e1-45ba-bc30-8126eaa566d7.png)
