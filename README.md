GO-BVO Predictive Model

## Overview

This is an analytical study focused on creating a predictive model to estimate the ratio of Bruttovloeroppervlakte (BVO) "gross floor area" to Gebruiksoppervlakte (GO) "net floor area" for residential units situated in 20-70m high towers. This estimation is based on various factors, including geometric factors. The GO metric is pivotal in the construction and real estate domain, as residences are priced based on their GO square meters.

## Data Collection & Features

- **Dataset Composition**: The dataset is manually constructed, comprising 5 residential projects with an average of 200 apartments each.
- **Features**: The dataset includes numerous features:
  - Basic metrics like BVO, GO, number of apartments per floor, number of floors in the building, and more.
  - Geometric features that articulate the geometric differences between apartments, such as angle count, angle average, complexity score, and concavity clusters.
  
## Methodology

1. **Data Concatenation**: Datasets from different projects are merged, NaN values are handled, and the BVO/GO ratio is computed.
2. **Test Data**: A distinct dataset is utilized for testing to assess the model's performance on completely unfamiliar data.
3. **Correlation Analysis**: The main focus lies on understanding the correlation between different features and the BVO/GO ratio to refine the predictive model.
4. **SVR Model Development**: Support Vector Regression (SVR) was chosen as the modeling approach. SVR is particularly suited for this task as it's designed to find a hyperplane that best divides a dataset into classes, making it apt for regression tasks where the aim is to predict a continuous output. The model's hyperparameters were tuned to ensure optimal performance on the dataset.

## Conclusion

The primary goal of this analytical study is to develop a robust predictive model that can accurately estimate the BVO/GO ratio for residential units. By considering diverse factors, especially geometric ones, the model seeks to provide invaluable insights for the real estate and construction sectors.


