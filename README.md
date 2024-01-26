# DL-Based Option Pricing Model Calibration
Inspiration from "Deep Learning Calibration of Option Pricing Models: Some Pitfalls and Solutions- Audrey Itkin"
#Introduction
In this project, we delve into the calibration of option pricing models using Deep Learning (DL) approaches. Recently, this methodology has garnered significant attention in the financial sector. Our paper addresses certain shortcomings in existing methodologies and proposes solutions to enhance both the performance and accuracy of calibration.

We focus on three main areas of improvement:
Activation Functions: Advocating the use of C^2 (twice differentiable) activation functions.
No-Arbitrage Conditions: Incorporating these conditions as penalties in the training of the pricing Artificial Neural Network (ANN).
Direct Calibration: Utilizing an inverse map approach for direct calibration of model parameters, extended to account for no-arbitrage.
