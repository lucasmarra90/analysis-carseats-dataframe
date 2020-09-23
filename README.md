# analysis-carseats-dataframe
Predictive analysis of the Carseats dataset (library ISLR from R) using tidymodels.

The response variable was the variable *Advertising*

4 regression models were tested:
  - *Linear regression*
  - *Random Forest*
  - *KNN*
  - *XGBoost*

In all models were used the tidymodels packages:
 - **RSample** for the split of the dataset between Training/Validation
 - **Recipes**to create and process the as matrices used for modeling
 - **Parsnip** for modeling
 - **Yardstick** for evaluating the predictive performance of each model

This activity was part of the the Advanced Program in Data Science and Decision at Insper.
