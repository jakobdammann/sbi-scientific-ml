# sbi-scientific-ml

Repository of my talk on Simulation Based Inference for the seminar Scientific Machine Learning 2026. 
This repository consists of the presentation, code used for generating plots and showing an example as well as my written report on the topic.

### Abstract
Simulation-Based Inference (SBI) offers a novel machine-learning-based approach to solve inverse problems. 
Hereby, a neural network learns to map observed data to a posterior distribution over model parameters.
By using simulations, SBI does not require any likelihood evaluation which otherwise often is computationally costly or has to be approximated.
This can allow SBI to outperform classical Bayesian inference methods in inference speed and posterior accuracy.
However, common problems like model misspecification, neural inaccuracies or miscalibrated posteriors can limit the utility of SBI if they are not circumvented.
This report presents basic SBI methodology, in particular Neural Posterior Estimation, discusses its advantages, limitations and reviews two exemplary applications for SBI: detecting planetary events from gravitational microlensing and inferring black hole merger parameters from gravitational waves.
