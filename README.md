# Group 4
## Project 4 Proposal

* Our Data Source
(https://www.kaggle.com/datasets/austinpowers/dubai-real-estate-transaction-first-semester-2023)
Rows: 81k

Columns: 22

* Our Group Members
  * Jae Zakarauskas
  * Joanna Gromek
  * Zunyan Guo
  * Peter Austin
 
Predicting housing prices in Dubai. We hope to use the dataset containing 80,000+ housing transactions dated January-June 2023 for Dubai, UAE. 


# ORDER OF OPERATIONS
## Data Retrieval and Preprocessing:
* Retrieve the CSV.
* Clean the data: drop "amount" and "transaction size" columns, filter out commercial properties. Bin square footage values.
* Determine outliers such as large amount of bedrooms, high sale prices.
* Normalize and standardize the data to ensure all features are on a similar scale. 

## Data Model Implementation:
* We will be performing a linear regression model and are also interested in exploring support vector regressions.
* Split the data into training and testing sets.
* Initialize, train, and evaluate the model using the training and testing data.
* Measure the model's classification accuracy (for classification) or R-squared (for regression) to ensure meaningful predictive power.

## Data Model Optimization:
* Document the model optimization process by making iterative changes to the model and observing the resulting changes in performance.
* Keep a record of the hyperparameters you experimented with and their corresponding performance metrics (e.g., accuracy, R-squared) in a CSV/Excel table or within the Python script itself.
* Perform techniques like hyperparameter tuning, feature selection, or model selection to improve the model's performance.

## Final Evaluation and Display:
* Python script to print or display the overall model performance, including the accuracy report or R-squared.
* Visualize the model's performance through plots / graphs.
* Slide deck for final presentation on Thursday, August 17.
