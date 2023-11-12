# PRODIGY_DS_02

Data analysis and visualization project using Python.

## Assignment Overview

I conducted exploratory data analysis (EDA) on a dataset in this assignment. The primary tasks included:

- Data loading and preprocessing, including handling missing values.
- Encoding categorical variables.
- Creating various data visualizations to explore and understand the dataset.

## Dataset

The dataset used for this assignment is <b>Titanic - Machine Learning from Disaster</b>. It contains Overview
The data has been split into two groups:<br><br>

<b>training set (train.csv)</b><br>
<b>test set (test.csv)</b><br><br>
The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like..

## Code Structure

The repository is organized as follows:

- PRODIGY_DS_02: The main Python script containing the data analysis and visualization code.
- train.csv and test.csv: The dataset files used for the analysis.
- README.md (this file): Provides an overview of the assignment and instructions.

## Instructions

To run the code in this assignment, follow these steps:

1. Clone this repository to your local machine using Git:

   ```bash
   git clone <repository-url>
   ```

Navigate to the repository folder: cd <repository-folder>
Install the required Python libraries if you haven't already. 
You can use pip: pip install pandas numpy matplotlib seaborn
Run the main script: python assignment_script.py.

## Results

Here are some key insights and findings from the analysis:

- *Survival Pie Chart*: The pie chart illustrating survival percentages shows that a significant portion of passengers did not survive, while a smaller percentage survived. This highlights the tragic nature of the Titanic disaster.

- *Passenger Class Distribution*: The box plot of 'Fare' by 'Pclass' demonstrates that passengers in first-class paid higher fares on average, followed by second-class and third-class passengers. This aligns with the expectation that higher-class passengers pay more for their tickets.

- *Gender Distribution*: The pie chart for gender distribution indicates that there were more male passengers than female passengers on the Titanic.

- *Age Distribution*: The age distribution histogram shows that the majority of passengers were between the ages 1 to 70 years, with a peak in the particular age group of 25 to 28 years.

- *Sibling/Spouse (SibSp) Distribution*: The box plot of 'Age' by 'SibSp' suggests that passengers with a higher number of siblings or spouses on board tended to be younger on average.

- *Parent/Children (Parch) Distribution*: The box plot of 'Age' by 'Parch' indicates that passengers with a higher number of parents or children on board tended to be younger on average.

- *Fare Distribution*: The fare distribution histogram illustrates that most passengers paid relatively low fares, with a few outliers who paid significantly higher fares.

- *Embarked Distribution*: The count plot of 'Embarked' shows the distribution of passengers across different ports of embarkation, with the majority embarking.

- *Survival Percentage by Passenger Class*: The bar plot of survival percentage by passenger class highlights that first-class passengers had the highest survival rate, followed by second-class and third-class passengers.

These findings provide a broad understanding of the Titanic dataset and serve as a starting point for further analysis or modeling.
