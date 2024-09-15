# DTU_MLCO327_Assignment_BostonHousingDataset

This repository contains a project focused on predicting house prices based on various features such as location, size, number of bedrooms, and more, using Linear Regression. The dataset used is the Boston Housing dataset.

## Project Details

- **Objective**: Predict house prices based on multiple features to understand and model housing prices in Boston.
- **Dataset**: Boston Housing Dataset
- **Model**: Linear Regression

## Libraries Used

- [Scikit-learn](https://scikit-learn.org/stable/modules/linear_model.html#ordinary-least-squares) for implementing Linear Regression
- [Pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html) for data manipulation and analysis
- [Seaborn](https://seaborn.pydata.org/) for visualization
- [Matplotlib](https://matplotlib.org/) for plotting

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/house-price-prediction.git
    ```
2. Navigate into the project directory:
    ```bash
    cd house-price-prediction
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Prepare the dataset by downloading it from [Kaggle](https://www.kaggle.com/c/boston-housing) and placing it in the `data` directory.
2. Run the Jupyter notebook or Python script to train the model and evaluate its performance:
    ```bash
    jupyter notebook House_Price_Prediction.ipynb
    ```
    or
    ```bash
    python house_price_prediction.py
    ```

## Results

- **Root Mean Squared Error (RMSE)**: Measures the average error between predicted and actual values.
- **R² Score**: Indicates the proportion of variance in the dependent variable that is predictable from the independent variables.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Boston Housing Dataset](https://www.kaggle.com/c/boston-housing) for providing the data used in this project.
- [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/linear_model.html#ordinary-least-squares) for details on Linear Regression.
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html) for data handling techniques.
