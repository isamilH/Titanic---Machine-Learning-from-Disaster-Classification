# Titanic---Machine-Learning-from-Disaster-Classification
This project is a solution to the Titanic survival prediction problem from the Kaggle competition "Titanic: Machine Learning from Disaster." The goal is to predict the survival of passengers based on various features such as their age, gender, ticket class, and more. 

## Dataset
Both the training and test datasets contain the following features:
    - PassengerId: Unique identifier for each passenger.
    - Survived: Target variable (0 = No, 1 = Yes) [Only in train.csv].
    - Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
    - Name: Passenger's name.
    - Sex: Gender of the passenger.
    - Age: Age of the passenger in years.
    - SibSp: Number of siblings/spouses aboard.
    - Parch: Number of parents/children aboard.
    - Ticket: Ticket number.
    - Fare: Passenger fare.
    - Cabin: Cabin number.
    - Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Project Structure
The notebook is divided into the following sections:
1. Exploratory Data Analysis (EDA)

    Initial exploration of the dataset, including visualizations to understand the relationships between features and survival rate.
    Key Insights:
        Survival Counts: A breakdown of the number of survivors versus non-survivors.
        Survival by Sex: Analysis of the survival rate by gender.

2. Data Cleaning and Preprocessing

    Handling missing values in features such as Age, Cabin, and Embarked.
    Feature engineering: creating new features or transforming existing ones to improve the model's performance.

3. Model Development

    Training machine learning models to predict the survival of passengers.
    Model evaluation and tuning for improved performance.
## Dependencies
    Python 3.x
    Pandas
    NumPy
    Scikit-learn
    Matplotlib
    Seaborn


