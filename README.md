# Exploratory-Data-Analysis-EDA-and-Visualization
Exploratory Data Analysis (EDA) and Visualization
Titanic Survival Exploration – EDA Project
This project performs a detailed Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, trends, and relationships between passenger features and survival outcomes.

The analysis includes data cleaning, visualization, and summary insights that lay the groundwork for building predictive models in future steps.

📂 Dataset Source
Dataset: Titanic – Machine Learning from Disaster
Source: https://www.kaggle.com/c/titanic/data
File used: train.csv

🧰 Steps Performed
Loaded and inspected the dataset using pandas.
Identified and handled missing values (e.g., Age, Embarked, Cabin).
Conducted univariate analysis of key features such as Sex, Age, Fare, and Pclass.
Performed bivariate analysis to understand survival patterns.
Visualized relationships using seaborn and matplotlib
Created age groups and explored categorical survival relationships.
Generated a correlation matrix for numerical features.
Documented findings in a final summary section.

📈 Key Findings (Summary)
Female passengers had a much higher survival rate than males.
1st class passengers survived at higher rates than those in lower classes.
Children and younger passengers had better chances of survival.
Passengers who embarked at Cherbourg showed higher survival probability.
Features like Sex, Pclass, Age, and Embarked are important for building predictive models.
(See the notebook's final markdown cell for a full summary.)

▶️ How to Run This Notebook
Clone or download this repository.
Ensure you have Python 3.x installed.
Install the required libraries using pip:
pip install pandas numpy matplotlib seaborn jupyterlab
Launch Jupyter Lab or Notebook in the project directory:
jupyter lab
Open Titanic_EDA.ipynb and run all cells sequentially.
