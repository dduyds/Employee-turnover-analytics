## Understand the business scenario and problem

The HR department at Salifort Motors seeks to improve employee satisfaction and reduce turnover. They have collected employee data but need guidance on how to utilize it. The mission is to analyze this data to identify factors contributing to employee departures and build a predictive model for employee turnover. The ultimate goal is to enhance employee retention, which will save the company time and resources in hiring new staff.

## About the HR dataset

The dataset in this project contains 15,000 rows and 10 columns for the variables listed below. 

**Data source:** [Kaggle](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv).

Variable  |Description |
-----|-----|
satisfaction_level|Employee-reported job satisfaction level [0&ndash;1]|
last_evaluation|Score of employee's last performance review [0&ndash;1]|
number_project|Number of projects employee contributes to|
average_monthly_hours|Average number of hours employee worked per month|
time_spend_company|How long the employee has been with the company (years)
Work_accident|Whether or not the employee experienced an accident while at work
left|Whether or not the employee left the company
promotion_last_5years|Whether or not the employee was promoted in the last 5 years
Department|The employee's department
salary|The employee's salary (U.S. dollars)


## Summary of model results

**Logistic Regression**

The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 81% (all weighted averages), and accuracy of 83%, on the test set.

**Tree-based Machine Learning**

After conducting feature engineering, the random forest model achieved AUC of 94.6%, precision of 91.4%, recall of 91%, f1-score of 91.2%, and accuracy of 97%, on the test set. The random forest modestly outperformed the decision tree and logistic regression model.	


## Conclusion
The models and the feature importances confirm that employees at the company are overworked.
To retain employees, the following recommendations could be presented:
- Cap the number of projects that employees can work on.
- Consider promoting employees who have been with the company for at least four years, or investigate further why these employees are dissatisfied.
- Either reward employees for working longer hours or don't require them to do so.
- Inform employees about the company's overtime pay policies and clarify expectations around workload and time off.
- Hold company-wide and team discussions to understand and address the work culture.
