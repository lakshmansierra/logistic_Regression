# Logistic Regression
Logistic regression is a **classification algorithm** that `models the probability of a data point belonging to a particular class` using the **sigmoid function**.

```bash
Supervised Learning -> Classification Algorithm -> Binary Classification | Multi Classification
```

## Logistic Regression Equation

$$
y = \sigma(z) \in (0, 1) = \frac{1}{1 + e^{-z}}
$$

$$
z = \beta_0 + \beta_1 x_1 + \beta_2 x_2 + \cdots + \beta_n x_n
$$

- 𝜎 => sigmoid function to predict the probability of an observation being in the class
- β₀ => intercept (bias)
- β₁, β₂ ... => learned weights for each feature
- x₁, x₂ ... => feature values
