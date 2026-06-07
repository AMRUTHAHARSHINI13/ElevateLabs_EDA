Exploratory Data Analysis (EDA) on Titanic Dataset
📌 Project Title

Exploratory Data Analysis (EDA) on Titanic Dataset using Python

🎯 Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights using statistical methods and visualizations.

🛠️ Tools & Technologies Used
Python 🐍
Pandas
Matplotlib
Seaborn
Jupyter Notebook (VS Code)
📂 Dataset

Dataset Name: Titanic-dataset.csv
Description: Contains information about Titanic passengers such as age, gender, class, survival status, etc.

🔄 Steps Performed
1. Data Loading
Loaded dataset using pandas.read_csv()
Displayed first few rows using head()
2. Data Exploration
Used .info() to understand data types and missing values
Used .describe() for statistical summary
Used .value_counts() for categorical analysis
3. Data Cleaning
Checked missing values using .isnull().sum()
Handled/identified missing data for analysis
4. Data Visualization

Created visualizations using Seaborn and Matplotlib:

Count plot of survival rate
Histogram of age distribution
Boxplot for outlier detection
Heatmap for correlation analysis
📊 Key Insights
Majority of passengers did not survive
Females had higher survival rates compared to males
Passengers in higher class (1st class) had better survival chances
Age distribution shows most passengers were young adults
Strong correlation observed between passenger class and survival
📁 Files in this Project
Titanic-dataset.csv (dataset)
notebook.ipynb (Jupyter notebook)
README.md (this file)
🚀 How to Run the Project
Open VS Code
Launch Jupyter Notebook (.ipynb file)

Install required libraries:

pip install pandas matplotlib seaborn
Run all cells step by step
View outputs and visualizations
📌 Conclusion

This project demonstrates how EDA helps in understanding datasets, finding patterns, and extracting useful insights before building machine learning models.