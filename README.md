# Absenteeism Project

## Overview
The project will adress ABSENTEEISM at a company during work time. The purpose of this project is to explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not? 

## Dependencies
- numpy==1.20.3
- pandas==1.3.3
- scikit-learn==0.24.2
- matplotlib==3.4.3
- seaborn==0.11.2
- jupyterlab==3.1.14

## Usage

```python

from absenteeism_module import *
model = absenteeism_model('model', 'scaler')

model.load_and_clean('Absenteeism_new_data.csv')

model.predicted_outputs()
```


## Data
### Absenteeism_data.csv
- **Description**: This dataset records instances of employee absenteeism from work, providing details on reasons for absence, employee demographics, and related factors. It enables analysis of absenteeism patterns and predictors.
- **Format**: CSV
- **Features**: List of features (columns) present in the dataset.
 - ID: Unique employee identifier.
 - Reason for Absence: Numerical code indicating the reason for absence.
 - Date: Date of absence.
 - Transportation Expense: Total transportation cost.
 - Distance to Work: Distance between residence and workplace.
 - Age: Employee's age.
 - Daily Work Load Average: Average daily workload.
 - Body Mass Index: Employee's BMI.
 - Education: Level of education.
 - Children: Number of children.
 - Pets: Number of pets.
 - Absenteeism Time in Hours: Duration of absence.


Certainly! Here's the updated README file focusing only on logistic regression:

---

## Results

After conducting exploratory data analysis, preprocessing the data, training the logistic regression model, and evaluating its performance, here are the key findings and results of our project:

### Exploratory Data Analysis (EDA)
- We analyzed the distribution of various features in the dataset and identified potential patterns and trends.
- Visualizations such as histograms, box plots, and scatter plots helped us understand the relationships between different variables.

### Data Preprocessing
- We performed data cleaning and feature engineering to prepare the data for logistic regression modeling.
- Techniques such as one-hot encoding, scaling, and normalization were applied to ensure the data's suitability for logistic regression.

### Model Training and Evaluation
- We trained a logistic regression model using the preprocessed data.
-  we evaluated the model's performance and achieved an accuracy of 0.75, indicating its effectiveness in predicting the target variable.


### Key Findings
- The logistic regression model provided valuable insights into the factors driving the outcome of interest.
- Features such as Reason type1 and Reason type3 were found to be the most influential in predicting the target variable.
- Further analysis revealed potential areas for improvement, such as feature selection or fine-tuning model hyperparameters.

---

Feel free to further customize this README file as needed for your project.
### Limitations and Future Work
- Despite the promising results, our analysis has certain limitations, including the availability and quality of data.
- Future work could involve incorporating more advanced machine learning techniques, exploring ensemble methods, or conducting additional experiments to validate our findings.

### Conclusion
- In conclusion, our data science project has provided valuable insights into the problem at hand and demonstrated the effectiveness of logistic regression in addressing it.
- We hope that our findings will contribute to further research and practical applications in this domain.

## Acknowledgements
[The Data Science Course: Complete Data Science Bootcamp 2024
](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp/)
