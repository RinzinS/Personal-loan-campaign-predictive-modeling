Machine Learning–Driven Customer Targeting for Personal Loan Campaigns

This project develops and compares multiple machine‑learning models to help Universal Bank identify customers most likely to accept a personal loan offer. The goal is to improve targeting efficiency, reduce marketing costs, and maximize campaign profitability through data‑driven decision‑making

Overview
Using the Universal Bank dataset, this project builds a full predictive‑analytics pipeline:
- 	Data cleaning and preprocessing
- 	One‑hot encoding and feature scaling
- 	Model training and validation
- 	Performance comparison across multiple algorithms
- 	Lift, gain, and profit analysis for business decision‑making
The final deliverable identifies the most effective model for ranking customers by loan‑acceptance likelihood.

Models Included
Five supervised learning models were developed and evaluated:
- K‑Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree Classifier
- Ensemble Majority Vote
- Ensemble Average Probability
Each model was assessed using both statistical and business‑oriented metrics.

Methodology
Data Preparation
- Removed non‑predictive fields (e.g., customer ID)
- One‑hot encoded categorical variables
- Standardized numerical features for KNN and Naive Bayes
- Binned continuous variables for Naive Bayes per project guidelines
- Split data into 60% training and 40% validation
  
Evaluation Metrics
- Accuracy, precision, recall, F1‑score
- Confusion matrix
- ROC curve & AUC
- Lift and cumulative gain charts
- Profit curve & optimal targeting fraction

Key Results
Best Overall Model (Accuracy + Lift)
Ensemble Average Probability
- Accuracy: 0.9725
- Lift (Top 10%): 9.26
- AUC: 0.9887
- Max Profit: $299,433
- Optimal Targeting: ~9.7% of customers

Best Model for Maximum Profit
Decision Tree
- Accuracy: 0.9819
- Lift (Top 10%): 9.04
- AUC: 0.9731
- Max Profit: $307,474
- Optimal Targeting: ~11% of customers

Business Recommendation
While the Decision Tree achieves the highest total profit, the Ensemble Average Probability model provides the strongest combination of:
- High accuracy
- Excellent lift
- Efficient targeting
- Strong ranking ability
Because it concentrates profitable customers earlier in the ranking and requires contacting fewer people, it is the recommended model for Universal Bank’s targeted loan‑marketing strategy.

Skills Demonstrated
- Predictive modeling
- Feature engineering
- Model comparison & evaluation
- Business analytics & profit optimization
- Ensemble learning
- Visualization (ROC, lift, gain charts)
- End‑to‑end machine‑learning workflow

Conclusion

This project demonstrates how machine‑learning models can significantly improve Universal Bank’s personal‑loan marketing strategy by identifying customers most likely to accept an offer. After comparing multiple algorithms using both statistical metrics and business‑oriented measures such as lift, gain, and profit, the Ensemble Average Probability model emerged as the most balanced and effective choice. It delivers high accuracy, strong ranking performance, and efficient targeting, allowing the bank to achieve near‑maximum profit while contacting fewer customers.
The results show that data‑driven targeting can reduce marketing costs, increase response rates, and support more profitable decision‑making. This modeling framework can be extended to future campaigns, additional products, or real‑time customer scoring, providing a scalable foundation for ongoing analytics initiatives.


