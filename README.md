# AI-ML-INTERNSHIP-DAY-1

# Task 1: Data Cleaning & Preprocessing

## 🧠 Objective

To practice and understand how to clean and preprocess real-world data in preparation for machine learning models.

## 📚 Dataset

- *Source*: [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- *Accessed via*: kagglehub Python library

## 🛠 Tools & Libraries Used

- Python
- pandas
- numpy
- matplotlib / seaborn
- sklearn (for encoding and scaling)
- kagglehub (to access Kaggle dataset programmatically)

## 🔍 Steps Performed

1. *Import Dataset*
   - Downloaded dataset using kagglehub
   - Loaded into pandas DataFrame

2. *Initial Exploration*
   - Used .info(), .describe(), .head() to explore data
   - Checked for null values

3. *Dropped Columns*
   - Removed columns: PassengerId, Name, Ticket, Cabin due to high missing values or irrelevance

4. *Handled Missing Data*
   - Filled Age with mean
   - Filled Embarked with mode (S)

5. *Outlier Removal*
   - Used boxplots to visualize outliers in Age and Fare
   - Removed rows with Age > 70 and Fare > 300

6. *Encoding*
   - Used OneHotEncoder to convert categorical Sex and Embarked columns

7. *Feature Scaling*
   - Applied StandardScaler to Age and Fare columns for normalization
