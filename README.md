# Predictive Modeling of House Prices in King County, USA

This project involves the application of various machine learning algorithms to predict house prices in King County, USA.

## Dataset

The dataset used in this project is derived from the King County House Sales dataset. The data includes house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. The dataset contains 21 different features and 21613 instances, each representing a house. These features include:

- Number of bedrooms and bathrooms
- Total square footage of living space
- Number of floors
- Whether the house has a waterfront
- View rating
- Overall condition and grade
- Square footage of the lot
- Square footage of above ground living space
- Square footage of basement
- Year built and year renovated
- Zipcode
- Latitude and longitude
- Price (target variable)

## Methodology

The project follows these steps:

1. **Data Exploration and Preprocessing**: This step includes understanding the dataset, handling missing or erroneous values, and preparing the data for modeling.

2. **Feature Selection**: Identifying and selecting important features using Recursive Feature Elimination (RFE) and other methods.

3. **Model Building**: Training various machine learning models including Linear Regression, Decision Trees, Random Forest, and Gradient Boosting.

4. **Model Evaluation**: Assessing the models' performance using metrics like RMSE (Root Mean Squared Error) and R-squared, and using cross-validation for a more reliable estimation of model performance.

5. **Hyperparameter Tuning**: Optimizing the models' parameters using GridSearchCV for improved performance.

6. **Regularization**: Implementing Ridge and Lasso regularization techniques to avoid overfitting and enhance model generalization.

## Results

The project yielded satisfactory results, with Gradient Boosting Regressor producing the best performance after hyperparameter tuning. Further improvements could potentially be obtained through more advanced feature engineering, use of more complex models, or ensemble methods.

## Usage

To replicate or build upon this project, follow these steps:

1. Clone this repository.
2. Install necessary Python packages: Pandas, Numpy, Scikit-Learn, Matplotlib, and Seaborn.
3. Run the Jupyter notebooks in the provided order.

## Dependencies

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## License

This project is licensed under the terms of the MIT license.

## Contributions

Contributions to this project are always welcome. To get started, you can check the [contributions guide](CONTRIBUTING.md).

## Contact

For any questions, comments, or discussions, please open an issue or contact me at @olusholayahaya@gmail.com.
