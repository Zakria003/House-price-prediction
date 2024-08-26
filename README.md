# House Price Prediction: EDA, Feature Engineering, and Feature Selection

## Overview
This project involves exploratory data analysis (EDA), feature engineering, and feature selection for a house price prediction dataset. The goal is to preprocess and prepare the data for predictive modeling by understanding the dataset, creating meaningful features, and selecting the most relevant features for modeling.

## Dataset
The dataset used for this project is the [House Prices Dataset](https://www.kaggle.com/datasets/lespin/house-prices-dataset) from Kaggle.

## Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Installation
To run this project, ensure you have the required libraries installed. You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
<h2>Project Structure</h2>
    <p>The project is organized as follows:</p>
    <ul>
    <li><code>train.csv</code>: The original dataset used for analysis.</li>
    <li><code>X_train_cleaned.csv</code>: The cleaned and tailored version of <code>train.csv</code>, modified for further analysis.</li>
    <li><code>EDA.ipynb</code>: Jupyter Notebook containing the Exploratory Data Analysis (EDA) to identify key insights and preliminary findings.</li>
    <li><code>feature_engineering_2.ipynb</code>: Jupyter Notebook detailing the feature engineering process based on conclusions drawn from <code>EDA.ipynb</code>, including data modifications and enhancements. </li>
    <li><code>feature_selection_3.ipynb</code>: Jupyter Notebook focused on feature selection, narrowing down the number of features to improve model performance.</li>
</ul>

<h2>Exploratory Data Analysis (EDA)</h2>
<p>The main aim of the Exploratory Data Analysis (EDA) is to gain a deeper understanding of the dataset. The analysis focuses on the following aspects:</p>
<ol>
    <li><strong>Missing Values:</strong> Identify and analyze missing values and their impact on the target variable, <code>SalePrice</code>.</li>
    <li><strong>Numerical Variables:</strong> Separate numerical variables into continuous and discrete types, and analyze their distributions.</li>
    <li><strong>Categorical Variables:</strong> Examine the cardinality of categorical variables and their relationship with <code>SalePrice</code>.</li>
    <li><strong>Outliers:</strong> Identify outliers in numerical variables and assess their impact.</li>
    <li><strong>Relationship Analysis:</strong> Explore relationships between independent variables and the dependent variable, <code>SalePrice</code>.</li>
</ol>

<h2>Feature Engineering</h2>
<ul>
    <li><strong>Handling Missing Values:</strong> Replaced missing values with meaningful imputation based on their relationship with <code>SalePrice</code>.</li>
    <li><strong>Temporal Features:</strong> Extracted useful features from date-related variables, such as the difference in years between the sale year and other date-related features.</li>
    <li><strong>Transformations:</strong> Addressed skewed distributions and outliers to make the data more suitable for regression modeling.</li>
</ul>

<h2>Feature Selection</h2>
<p>Used Lasso Regression with <code>SelectFromModel</code> for feature selection to identify the most important features. The model was configured with an alpha value of 0.005 to select features with non-zero coefficients.</p>

<h2>Results</h2>
<p>The analysis and feature engineering led to a refined dataset with important features selected for modeling. Detailed results and visualizations can be found in the <code>eda_feature_engineering.ipynb</code> notebook.</p>

<h2>Contributing</h2>
<p>Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.</p>

<h2>Acknowledgements</h2>
<ul>
    <li>Dataset: <a href="https://www.kaggle.com/datasets/lespin/house-prices-dataset">House Prices Dataset</a></li>
    <li>Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn</li>
</ul>

<h2>Contact</h2>
<p>For questions or feedback, please reach out to <a href="mailto:zakriaimdad012+github@gmail.com">zakriaimdad012+github@gmail.com</a>.</p>
</body>
</html>
