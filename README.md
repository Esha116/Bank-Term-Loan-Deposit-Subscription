# Bank-Term-Loan-Deposit-Subscription
The project focuses on improving marketing strategies and increasing deposit rates through data-driven insights.

## Tools and Techniques:
Python in Google Colab 

## Business Context:
Assist banks in boosting term deposit subscriptions by predicting customer behavior.

## Dataset: 
Kaggle Bank Marketing Campaign dataset with 11,162 client records and 17 features.

## Data Preparation:
- Converted categorical variables into binary values and applied one-hot encoding for non-numeric features.
- Normalized features for stable convergence during training.
- Split data into 80% training and 20% testing datasets, ensuring effective model evaluation.

## Modeling:
- Implemented a neural network with multiple layers using ReLU activation and the Adam optimizer.
- Applied regularization techniques, including dropout and L2 weight decay, to improve model generalization.
- Utilized BCEWithLogitsLoss for binary classification tasks.

## Results:
- Achieved a validation accuracy of 85.6% and an AUC score of 0.9149, outperforming comparable models.
- Generated actionable insights into customer behavior to optimize targeted marketing campaigns.

## Deployment:
- Proposed the integration of model predictions with human judgment for decision-making.
- Enabled future scalability for other banking products or services.
