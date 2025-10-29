# Car Price Prediction Using Linear Regression

This project demonstrates how to build a car price prediction model using Linear Regression in Python. The workflow includes data cleaning, preprocessing, model training, evaluation, and visualization. The implementation is provided in the [car_price.ipynb](car_price.ipynb) Jupyter notebook.

## Dataset

The notebook uses the `CarPrice_Assignment.csv` dataset. This dataset contains various features of cars, including technical specifications and the target variable: `price`.

## Workflow Overview

1. **Data Loading & Exploration**
    - Loads the CSV file using pandas.
    - Displays sample rows and checks for missing values and datatypes.

2. **Data Cleaning**
    - Removes unnecessary columns like `CarName` and `car_ID`.
    - Converts categorical text columns (e.g., `doornumber`, `cylindernumber`) to numerical values.
    - Encodes categorical features using one-hot encoding.

3. **Preprocessing**
    - Splits the dataset into features (`X`) and target (`y`).
    - Performs a train-test split.
    - Scales features for better model performance.

4. **Model Building**
    - Trains a Linear Regression model on the training data.

5. **Model Evaluation**
    - Predicts car prices on the test set.
    - Calculates metrics: R² score and Mean Squared Error.
    - Visualizes actual vs. predicted values and residuals.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Place `car_price.ipynb` and `CarPrice_Assignment.csv` in the same directory.
2. Open the notebook in Jupyter:
    ```bash
    jupyter notebook car_price.ipynb
    ```
3. Run the cells sequentially to reproduce the workflow and results.

## Results

- The notebook provides an R² score and Mean Squared Error to evaluate the performance of the Linear Regression model.
- Visualization plots help understand the prediction accuracy and error distribution.

## Visualization Samples

- **Actual vs. Predicted Scatter Plot**: Shows how close model predictions are to real prices.
- **Residuals Histogram**: Visualizes the distribution of prediction errors.

## Author

- [Your Name Here] (replace with your actual name or GitHub handle)

## License

This project is open source and available under the [MIT License](LICENSE).
