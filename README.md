# Linear-Regression-Model-Selection

### The goal was to determine the optimal degree of the polynomial that fits the data best to prevent overfitting or underfitting. 

- A housing price dataset that included features such as the size of the house, number of bedrooms, number of floors, and age of the house was split into three subsets: the training set, the validation set, and the test set.
- The training set was used to train and fit linear regression models with polynomial terms of increasing degrees. A range of degrees, starting from 1 (simple linear regression) to 10 was taken.
- The validation set was used to assess the performance of each model, allowing us to select the degree that provided the best trade-off between bias and variance. By evaluating the models on the validation set, the degree with the lowest validation error was achieved.
- Finally, we applied the selected degree to the test set to obtain a final assessment of the model's performance and generalization capabilities.

