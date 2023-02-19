# Sampling Assignment

#### Kriti Singhal

#### 102017079

## Introduction

In this assignment, first the dataset called "Creditcard_data.csv" is read and then oversampling using SMOTE is performed in order to make the datset balanced. The distribution of the data before and after oversampling is shown below.

<br>

### Before Oversampling

![Before Oversampling](./before_smote.png)

<br>

### After Oversampling

![After Oversampling](./after_smote.png)

<br>
<br>

After balancing the data is then sampled using the following methods:

1. Simple Random Sampling
2. Systematic Sampling
3. Stratified Sampling
4. Cluster Sampling

<br>

## Model Building

After performing the sampling methods, the data is then split into training(80%) and testing data(20%). The following models are then built on the training data for each sample:

1. Logistic Regression
2. Random Forest
3. Decision Tree
4. SVM
5. KNN
6. Naive Bayes

Based on the accuracies obtained, the below 5 models were selected for further analysis:

1. Logistic Regression
2. Random Forest
3. Decision Tree
4. KNN
5. Naive Bayes

<br>

## Results

After training the models on the training data, the models were then tested on the testing data. The accuracies obtained are shown below:

<!-- Table of accuracies -->

|                     | Sample1      | Sample2      | Sample3      | Sample4      | Sample5     |
| ------------------- | ------------ | ------------ | ------------ | ------------ | ----------- |
| Logistic Regression | 0.909091     | 0.947712     | 0.945        | 0.882353     | 0.95000     |
| Random Forest       | **0.974026** | **0.996732** | **0.988972** | 0.935897     | 0.971526    |
| Decision Tree       | 0.909091     | 0.983660     | 0.955        | **0.941176** | **0.98125** |
| KNN                 | 0.766234     | 0.856209     | 0.870        | 0.794118     | 0.88750     |
| Naive Bayes         | 0.844156     | 0.872549     | 0.835        | 0.833333     | 0.93125     |

<br>

## Conclusion

As shown in the table above, Random Forest has the highest accuracy for all the samples.
