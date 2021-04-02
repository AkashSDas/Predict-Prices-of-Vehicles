# predict-prices-of-vehicles

Here [vehicle_prices](https://www.kaggle.com/akashsdas/vehicle-prices) is used to perform `EDA`, find features by `feature engineering` that affects `price` of vehicles and create a `regression` model that can predict price of vechicles.

**While doing this we'll go through**

- Feature engineering on `categorical` and `continuous` features
- Dealing with `multi-collinearity` issues
- Dealing with `outliers`

## Table of contents

- [Getting started](#getting-started)
- [Findings](#findings)
- [Model performance](#model-performance)
- [License](#license)

## Getting started

The [notebook](https://www.kaggle.com/akashsdas/predict-prices-of-vehicles) is available on Kaggle to work in the same environment where this notebook was created i.e. use the same version packages used, etc...

## Findings

**Correlation matrix**

![corr](./docs/imgs/corr.png)

**Multi collinearity issue**

![](./docs/imgs/multi-collinear-issue.png)

**Price distribution**

![](./docs/imgs/price.png)

**Correlation matrix for vehicle prices**

![](./docs/imgs/price-corr.png)

To see more go to the [notebook](./notebook.ipynb).

## Model performance

**Learning curve**

![](./docs/imgs/learning-curve.png)

**RMS error and R2 square metrics**

![scores](./docs/imgs/scores.png)

**Actual Vs Predicted values**

![actual-vs-prediction](./docs/imgs/result1.png)
![actual-vs-prediction](./docs/imgs/result2.png)

## License

[APACHE LICENSE, VERSION 2.0](./LICENSE)
