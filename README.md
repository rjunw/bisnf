# Bayesian Importance Sampling (and Normalizing Flows)
### Supervisor: Scott Schwartz
### Yichen Ji, Eric Jiang, Haining Tan, Ryan Wang

## Current Experiments:
Yichen:
* [Conditional Density/Regression](https://colab.research.google.com/drive/1kTNrOWnhcYIy0qs6T-5MWSlA-yixdkj-?usp=sharing)

Eric:
* [learning rate experiments with swag](https://colab.research.google.com/drive/1EZHaQNj9VjZnLi4-VxExUQHNilZ6CmFN?usp=sharing)

Haining:
* [NF with SWAG on one moon data (Karpathy/nflows); SWAG vs gold standard on MVN](https://colab.research.google.com/drive/113Y0p8Y4Nwyi5UVL5xTdrQOt2mLMJjAm?usp=sharing)

Ryan:
* [Importance sampling to improve SWAG posterior uncertainty approximations of non-Gaussian posterior over parameters of a normalizing flow](https://colab.research.google.com/drive/1m_b9czxfToTuBxcc8JsSxotZ_s9w4rml?usp=sharing)
  * Current issues: IS weighting only very minutely improves uncertainty characterization in log densities (using KS-distance as a metric)
* [Linear regression, non-linear regression, variational regression?](https://colab.research.google.com/drive/18U8OZJdMc7zMy6tP5hdoT5VybyBHx2M5?usp=sharing)
  * Current issues: None atm; IS mean estimator uncertainty almost identitical with SWAG mean estimator; How to quantify uncertainty?
* [Characterizing uncertainty in the **two moons** dataset](https://colab.research.google.com/drive/1k9X0KVGJaTgPIKZfElhXZhO7Rv89Vssb?usp=sharing)
  * Current issues: No ground truth to compare SWAG and IS weighted
* [MNIST SWAG + IS](https://colab.research.google.com/drive/1IqJnRO_vP-sI_KB3USTmEbGBnvHx40gS?usp=sharing)
  * Current issues: None atm; IS doesn't improve performance; How to quantify uncertainty here?
