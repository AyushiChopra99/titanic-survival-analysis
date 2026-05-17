Titanic Survival Data Analysis & EDA

Overview
This project performs data cleaning and exploratory data analysis (EDA)
on the Titanic passenger dataset to identify key factors that influenced
survival rates using Python.


Tools & Technologies
- Python 3
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

 
Dataset
- Source: Kaggle — Titanic Dataset
- Link: https://www.kaggle.com/datasets/yasserh/titanic-dataset
- Rows: 891 passengers
- Columns: Survived, Pclass, Sex, Age, SibSp, Parch, Fare, Embarked


Data Cleaning Steps
- Filled 177 missing Age values with the median age
- Dropped Cabin column (77% null values)
- Removed 2 rows with missing Embarked values
- Dropped irrelevant columns: PassengerId, Name, Ticket
- Added AgeGroup column (Child, Teen, Young Adult, Adult, Senior)|


Key Findings
- Only 38.4% of passengers survived
- Female passengers had ~74% survival rate vs ~19% for males
- First class passengers had the highest survival rate (~63%)
- Children under 12 had better survival odds than adults
- Passengers with higher fares were more likely to survive
