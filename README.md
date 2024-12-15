# Regression-with-an-Insurance-Dataset
Welcome to the 2024 Kaggle Playground Series! We plan to continue in the spirit of previous playgrounds, providing interesting an approachable datasets for our community to practice their machine learning skills, and anticipate a competition each month. 

Your Goal: The objectives of this challenge is to predict insurance premiums based on various factors.

Evaluation
Submissions are evaluated using the Root Mean Squared Logarithmic Error (RMSLE).

Submission File
For each id row in the test set, you must predict the continuous target Premium Amount. The file should contain a header and have the following format:

| ID       | Premium Amount |
|----------|----------------|
| 1200000  | 1102.545       |
| 1200001  | 1102.545       |
| 1200002  | 1102.545       |
| etc.     | etc.           |


Dataset Description
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Insurance Premium Prediction dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.

Files
train.csv - the training dataset; Premium Amount is the continuous target
test.csv - the test dataset; your objective is to predict target Premium Amount for each row
sample_submission.csv - a sample submission file in the correct format
