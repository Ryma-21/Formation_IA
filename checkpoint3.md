## selecting the most important features (feature selection):

after exploring the dataset and visualizing the relationship between house price and some of the features, i concluded that the most important features are :

- **sqft_living**: The total square footage of the living area.
- **sqft_lot**: The total square footage of the land area.
- **view**: A representation of the quality of the view from the property.
- **condition**: An indicator of the overall condition of the property.
- **grade**: An indicator of the overall quality of construction and design.
- **lat**: The latitude of the property's location.
- **long**: The longitude of the property's location.

## comparing multi-linear regression to the linear model

### Measuring the performance of linear regression using the testing set :

Mean Squared Error: 126159322289.59604

R-squared: 0.007927964053504155

### Measuring the performance of multi-linear regression using the testing set :

Mean Squared Error: 42552529243.43991

R-squared: 0.6653820458522424

---

**Note**: the model with the lower MSE and the higher R-squared value is generally considered better in terms of predictive accuracy and explanatory power

---

### conclusion 1

from the MSE and R-squared values the multi-linear predictive results are closer to the real prices and so the multi-linear model is better

## comparing Polynomial regression regression to the linear model and multi-linear

### Measuring the performance of linear regression using the testing set :

Mean Squared Error: 126159322289.59604

R-squared: 0.007927964053504155

### Measuring the performance of multi-linear regression using the testing set :

Mean Squared Error: 42552529243.43991

R-squared: 0.6653820458522424

### Measuring the performance of polynomial regression using the testing set :

Mean Squared Error: 29990631810.90986

R-squared: 0.7641643390278048

#### observation

MSE and R-squared values of poynomial regression model are lowest

### conclusion 2

the prdictive prices of the polynomial regression model are the closest to the real prices, and so the polynomial model is the best one from the three models, followed by the multi-linear model then the linear.
