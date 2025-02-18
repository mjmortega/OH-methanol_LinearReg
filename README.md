# **Kinetic Parameters Calculation for OH-CH<sub>3</sub>OH Gas-Phase Reaction**
---
## **Project Overview**
This project applies linear regression to calculate the kinetic parameters of the OH-CH<sub>3</sub>OH gas-phase reaction. Two methods are employed:
1. Using the ***sklearn*** library for linear regression.
2. Implementing gradient descent from scratch without using the ***sklearn*** library.

The inspiration for this project comes from the Machine Learning Specialization courses offered by DeepLearning.AI on Coursera. The project aligns with my background in chemical engineering and serves as a foundational step in learning and applying machine learning techniques.

## **Dataset Source**
The dataset used in this project is sourced from a scientific paper:
- McGillen, M. R., W. P. L. Carter, A. Mellouki, J. J. Orlando, B. Picquet-Varrault, and T. J. Wallington (2020): ‘Database for the kinetics of the gas-phase atmospheric reactions of organic compounds,’ Earth Syst. Sci. Data, 12, 1203–1216, [https://doi.org/10.5194/essd-12-1203-2020.](https://doi.org/10.5194/essd-12-1203-2020)
- Database version: [https://doi.org/10.25326/abq8-f406](https://doi.org/10.25326/abq8-f406)

## **Methodology**
1. **Sklearn Linear Regression:**
   - Utilizes the ***LinearRegression*** model from the ***sklearn*** library to fit the data and predict kinetic parameters.
2. **Gradient Descent from Scratch:**
   - Implements gradient descent algorithm manually to optimize the linear regression model without relying on ***sklearn***.
