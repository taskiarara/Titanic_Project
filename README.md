# Applying Classification Models on Titanic Dataset
## Description
This project aims to apply several classification models on Titanic dataset and find out which gives the best accuracy. This dataset contains information about passengers, including age, sex, ticket class, and family information.
## Titanic Dataset
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others (W Cukierski, 2012).
## Dataset
The dataset used comes from Kaggle and can be found [here](https://www.kaggle.com/c/titanic/data). The dataset consists of two main files:
- `train.csv`: Data to train the model.
- `test.csv`: Data for testing the model.
### Key Features
- **Survived**: Survival status (0 = not survived, 1 = survived)
- **Pclass**: Ticket class (1, 2, 3)
- **Name**: Passenger name
- **Sex**: Sex
- **Age**: Age in years
- **SibSp**: # of siblings / spouses aboard the Titanic
- **Parch**: # of parents / children aboard the Titanic
- **Fare**: Fare paid
- **Embarked**: Departure location (C = Cherbourg, Q = Queenstown, S = Southampton)
## Methodology
1. **Data Collection**: Downloaded the dataset from Kaggle.
2. **Pre-processing Data**:
   - Filled the missing values in the `Age` and `Embarked` columns with the median and mode values.
   - Converted categorical variables to numeric using Label Encoding.
   - Performed binning on the `Age` and  `Fare` columns.
3. **Splitting Data**: Split the dataset into training data and testing data.
4. **Modelling**: Using classification algorithms such as:
     - Random Forest
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Naive Bayes
     - Decision Tree
5. **Model Evaluation**: Calculating the accuracy of the model

## Result
Random Forest is the best model with an accuracy value of 84%.
