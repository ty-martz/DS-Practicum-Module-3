# Project Description:

- The Sure Tomorrow insurance company wants to protect its clients' data. Your task is to develop a data transforming algorithm that would make it hard to recover personal information from the transformed data. This is called data masking, or data obfuscation. You are also expected to prove that the algorithm works correctly. Additionally, the data should be protected in such a way that the quality of machine learning models doesn't suffer. You don't need to pick the best model. Follow these steps to develop a new algorithm:
  - construct a theoretical proof using properties of models and the given task;
  - formulate an algorithm for this proof;
  - check that the algorithm is working correctly when applied to real data.
- We will use a simple method of data masking, based on an invertible matrix.

## Project instructions
- Download and look into the data.
- Provide a theoretical proof based on the equation of linear regression. The features are multiplied by an invertible matrix. Show that the quality of the model is the same for both sets of parameters: the original features and the features after multiplication. How are the weight vectors from MSE minimums for these models related?
- State an algorithm for data transformation to solve the task. Explain why the linear regression quality won't change based on the proof above.
- Program your algorithm using matrix operations. Make sure that the quality of linear regression from sklearn is the same before and after transformation. Use the R2 metric.

## Data description
- The dataset is stored in file /datasets/insurance_us.csv.
- Features: insured person's gender, age, salary, and number of family members.
- Target: number of insurance benefits received by the insured person over the last five years.
