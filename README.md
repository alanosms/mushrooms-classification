# Mushroom Classification: Edible or Poisonous
This project uses mushroom data to predict whether a species is edible (E) or poisonous (P) based on its characteristics. We use a decision tree classifier to make predictions.

## Project Description
The dataset contains information about various mushroom characteristics, such as cap shape, surface, and color, bruising presence, odor, among others. The target variable is the mushroom class, which indicates whether it is edible (E) or poisonous (P).

## Project Structure
- **Library Imports**: We use `pandas`, `numpy`, `seaborn`, `matplotlib`, and `plotly.express` for data manipulation and visualization, and `scikit-learn` for machine learning modeling.
- **Data Loading and Verification**: The dataset is loaded from a CSV file and verified to ensure data integrity.
- **Exploratory Data Analysis (EDA)**: Visualizations, such as bar charts for class distribution, are generated.
- **Data Preprocessing**: Conversion of categorical variables into dummy variables and separation of the target variable.
- **Data Split**: The dataset is divided into training and test subsets.
- **Model Training**: A decision tree classifier is trained with the training set.
- **Decision Tree Visualization**: The trained decision tree is visualized.
- **Predictions and Evaluation**: The model makes predictions on the test set and results are compared with actual values.

## Dataset Usage
The dataset used in this project can be found [here](https://www.kaggle.com/datasets/devzohaib/mushroom-edibility-classification).
