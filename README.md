# Optimization Methods for Machine Learning
In this project, I have implemented various optimization methods from scratch using Python to enhance the training of machine learning models. These optimization methods play a crucial role in finding the optimal parameters of a model and improving its performance.

## Overview
 Machine learning models are often trained by minimizing a cost function, which is achieved through optimization algorithms. This project showcases the implementation of the following optimization methods:

1- Gradient Descent (GD): A classic optimization algorithm that iteratively updates model parameters in the direction of the steepest descent of the cost function.

2- Stochastic Gradient Descent (SGD): A variation of GD that randomly selects a single training sample for each iteration, making it computationally efficient for large datasets.

3- Mini-Batch Gradient Descent (MiniBatch GD): A hybrid approach that combines aspects of both GD and SGD by updating model parameters using a small batch of training samples.

4- Momentum-based Gradient Descent: Introduces momentum to GD, enabling faster convergence by accumulating past gradients to dampen oscillations.

5- Nesterov Accelerated Gradient (NAG): A variation of momentum-based GD that improves convergence near the minimum by considering the look-ahead gradients.

6- AdaGrad (Adaptive Gradient Algorithm): An adaptive learning rate algorithm that individually adjusts the learning rate for each parameter based on its historical gradient.

7- RMSProp (Root Mean Square Propagation): Another adaptive learning rate method that mitigates the diminishing learning rates of AdaGrad.

8- Adam (Adaptive Moment Estimation): A popular combination of momentum and RMSProp, which adapts the learning rates and momentum values for each parameter.
