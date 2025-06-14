# Wine_Quality_Prediction
This is a classification project on a wine quality dataset.

# About Dataset
There are a total 11 columns in this dataset.

fixed_acidity

volatile_acidity

citric_acid

residual_sugar

chlorides

free_sulfur_dioxide

total_sulfur_dioxide

density

pH

sulphates

alcohol

quality -> score between 3 and 9 -> target for our dataset

# Process
I have done binary classification. I have divided the target into two classes. 
1 if quality score is greater than 6, else zero.

# Model
I have Used XGBoost and Random Forests as the model.

# Evaluation
For different probability threshold valued I have evaluated the model's accuracy, presision and recall scores.
