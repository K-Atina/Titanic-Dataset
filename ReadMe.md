# Titanic Survival Analysis

## Overview
- This first project conducts an analysis of the Titanic dataset to explore patterns and observations on passenger survival rates.
- The dataset contains information on passengers' demographic data, such as sex, age, class, and family size, and their respective survival status. Through conducting exploratory data analysis (EDA), I investigate the relationships among various features and their influence on survival chances.
- This analysis offers important data on the determinants of survival in the Titanic disaster, including passenger class, gender, age, and travel status.

## Objective
- The primary objective of this project is to analyze and explain the connection between various variables and survival in the Titanic.
- Through the examination of significant factors such as class, gender, age, and family size, I aim to identify the factors that most greatly influenced survival probabilities.

## Data Sources

The data utilized in this project is the Titanic Dataset, which was accessed directly from Seaborn.
```python
dataSet=sns.load_dataset('titanic')
```

## Project Structure

- **Titanic Dataset**:
The dataset contains columns like:

1. **survived**: Passenger survived (0 = No, 1 = Yes).
2. **pclass**: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
3. **sex**: The sex of the passenger.
4. **age**: Age of passenger in years. Contains some missing values.
5. **sibsp**: Siblings/spouses on board the Titanic.
6. **parch**: Parents/children on board the Titanic.
7. **fare**: Passenger fare.
8. **embarked**: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).
9. **class**: Copy of 'pclass' (for plotting by Seaborn).
10. **who**: Specifies if the passenger is a male, female, or child.
11. **adult_male**: Indicates whether the passenger is an adult male (True/False).
12. **deck**: The deck the passenger was on (missing for the majority of passengers).
13. **embark_town**: The name of the town where the passenger boarded.
14. **alive**: Indicator of whether or not the passenger survived (Yes/No, from 'survived').
15. **Alone**: This shows if the passenger was alone (True/False).

#### **Jupyter Notebook**:
- The major analysis and visualizations are displayed in the Jupyter notebook: [Titanic.ipynb](Titanic_Dataset.ipynb) with step-by-step analysis along with visual output.

## Requirements

In order to execute this project locally, it is essential to ensure that the following Python packages are installed: pandas, seaborn, matplotlib, and numpy.

To install, use `pip`.

```bash
pip install pandas seaborn matplotlib numpy
```

## Methodology for running the Analysis
1. Clone or download this repository onto your local computer.
2. Install the required libraries using the above commands.
3. Open the Jupyter notebook named `Titanic_Dataset.ipynb`.
4. Run each cell in sequence to carry out the exploratory data analysis.

## Insight after analysis of dataset
The following was noted:
- **Passenger Class**: The upper-class passengers (1st class) survived significantly more than 2nd and 3rd-class passengers.
- **Gender**: Women had a higher survival rate than men, which can suggest the potential preference of women and children during the disaster.
- **Age**: The highest survival rate was among children, perhaps due to the preferential saving of young lives. On the other hand, adults and young adults, particularly in third class, suffered the highest casualties.
- **Solo travelers** experienced a reduced survival rate when compared with passengers who boarded the Titanic in family groups, indicating that family groups may have enjoyed a survival edge.

In conclusion:
- This first venture into the Titanic dataset yields significant discoveries regarding the determinants of survival in the Titanic disaster.
- The major determinants like class, gender, age, and family were seen to play a vital role in influencing survival conditions.
- The study offers further insight into the prevailing socio-economic and logistic conditions at the time of the disaster. 

## Potential future "developments"
- Future work can include the use of predictive machine learning modeling e.g. logistic regression in a bid to further understand the different features that are associated with survival rates and predict survivability.
- In addition, more detailed statistical analysis can be conducted to tackle the more complex relationships between these features. 
- Lastly, implement better better techniques of hnadling missing  values to increase accuracy when predicting.


## Reach out at:

**Github** : [github.com/K-Atina](https://github.com/K-Atina)

