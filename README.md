
# In-depth Analysis of Waiter's Tips Dataset

This repository contains an advanced analysis of a waiter's tips dataset. The analysis includes exploratory data analysis (EDA), data preprocessing, and building various machine learning models to predict the tip amount. Advanced techniques such as stacking and ensembling are employed to enhance the predictions.

## Dataset

The dataset consists of the following columns:
- `total_bill`: The total bill amount.
- `tip`: The tip given.
- `sex`: The gender of the waiter.
- `smoker`: Whether the waiter was serving a smoking section or not.
- `day`: The day of the week.
- `time`: The time of day (Lunch or Dinner).
- `size`: The size of the party.

The dataset was meticulously recorded by a dedicated waiter over a few months while working at a restaurant, resulting in 244 documented tips.

The dataset can be found on **Kaggle**: [A Waiter's Tips](https://www.kaggle.com/datasets/jsphyg/tipping).

## Notebook Contents

The Jupyter notebook in this repository performs the following tasks:

### 1. Introduction
- Overview of the dataset and the objective of the analysis.

### 2. Exploratory Data Analysis (EDA)
- Distribution of tips.
- Relationship between total bill and tip.
- Tips by day of the week.

### 3. Data Preprocessing
- Handling missing values.
- Encoding categorical variables.
- Splitting the dataset into training and testing sets.

### 4. Model Training and Evaluation
- Linear Regression
- Random Forest
- Gradient Boosting

### 5. Advanced Models and Techniques
- AdaBoost
- Gradient Boosting
- HistGradient Boosting
- XGBoost
- LightGBM
- CatBoost

### 6. Stacking and Ensembling
- Combining predictions from multiple models using stacking.

### 7. Conclusion
- Summary of the analysis and findings.

## Results

The notebook provides detailed metrics for each model, including Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) values. The results demonstrate the effectiveness of advanced techniques in predicting the tip amount.

## Usage

To run the notebook:

1. Clone the repository:
   ```bash
   git clone https://github.com/debjit-mandal/waiters-tips.git
   ```

2. Navigate to the repository folder:
   ```bash
   cd waiters-tips
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook Analysis_of_Waiters_Tips.ipynb
   ```

## Acknowledgements

This dataset is a treasure trove of information from a collection of case studies for business statistics. Special thanks to Bryant and Smith for their diligent work:
- Bryant, P. G. and Smith, M (1995) Practical Data Analysis: Case Studies in Business Statistics. Homewood, IL: Richard D. Irwin Publishing.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

----------------------------------------------------------------