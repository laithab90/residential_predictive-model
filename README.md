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

## Conclusion

This analytical study aims to develop a robust predictive model that can estimate the BVO/GO ratio for residential units. By considering various factors, especially geometric ones, the model aims to provide accurate estimates that can be invaluable in the real estate and construction sectors.

