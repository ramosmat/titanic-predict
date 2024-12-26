# Titanic Survival Prediction

This repository contains a machine learning project aimed at predicting the survival of passengers aboard the Titanic. Using data from the famous [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data), the project demonstrates the application of data science techniques to build predictive models.

## Dataset

The dataset used in this project includes the following features:

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **SibSp**: Number of siblings/spouses aboard.
- **Parch**: Number of parents/children aboard.
- **Ticket**: Ticket number.
- **Fare**: Fare paid for the ticket.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Key Libraries

The following Python libraries were used in this project:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For machine learning model implementation and Preprocessing values.

## Machine Learning Models

Several machine learning models were trained and evaluated to predict survival:

- **Logistic Regression**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**

## Project Workflow

1. **Data Preprocessing**:
   - Handling missing values (imputing missing ages and embarked ports).
   - Encoding categorical variables (converting 'Name, 'Sex' and others into numerical form).

2. **Exploratory Data Analysis (EDA)**:
   - Visualizing survival rates across different passenger classes, genders, and embarkation points.

3. **Feature Engineering**:
   - Selecting the most relevant features for modeling.

4. **Model Training and Evaluation**:
   - Splitting data into training and testing sets.
   - Training models using the training set and evaluating performance using accuracy test.

5. **Results**:
   - The Random Forest Classifier achieved the best performance, with an accuracy of **85.07%** on the test dataset.

## Results Summary

The analysis revealed significant insights:
- Female passengers had a higher survival rate compared to male passengers.
- Passengers in the 1st class were more likely to survive than those in 2nd or 3rd class.
- Younger passengers had a higher chance of survival.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/ramosmat/titanic-predict.git
   ```

2. Navigate to the project directory:
   ```bash
   cd titanic-predict
   ```

3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook script.ipynb
   ```

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Contributions are always welcome!