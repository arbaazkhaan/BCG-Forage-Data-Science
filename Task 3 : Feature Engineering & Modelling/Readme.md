# Feature Engineering & Modelling

### Sub-Task 1 - Feature Engineering:
**Recreating the Feature:**
- Load the provided notebook `feature_engineering.ipynb` and execute the cells related to creating the feature: "the difference between off-peak prices in December and January the preceding year."

**Improving Feature Predictive Power:**
1. Consider Time-Series Aspects: Analyze trends in off-peak prices across different months and years. Perhaps create additional features capturing trends or seasonal patterns. 📈📅
2. Interaction with Other Features: Explore if this feature interacts or correlates significantly with other engineered features. Create interaction terms if necessary. ↔️🔄
3. Lagged Features: Generate lagged versions of this feature (e.g., differences between prices of different months in preceding years) to capture more historical patterns. ⏮️
4. Domain Insights: Engage with domain experts to gain insights into potential factors affecting price fluctuations between December and January and incorporate that knowledge into feature engineering. 🧠🔍
5. Dimensionality Reduction: Employ techniques like PCA if there's high dimensionality in the dataset after feature creation to retain essential information. 🛠️📉

Now for Sub-Task 2:

### Sub-Task 2 - Building Predictive Model and Evaluation:
**Model Building - Random Forest:**
- Train a Random Forest Classifier using the cleaned and engineered dataset. 🌲🤖
- Split the data into training and testing sets.
- Train the model on the training set and evaluate its performance on the testing set.

**Evaluation:**
1. Metrics Selection: Depending on the class imbalance and the business context, choose appropriate evaluation metrics like accuracy, precision, recall, F1-score, ROC-AUC, etc. 📊🎯
2. Model Performance Analysis: Identify where the model underperforms and why. Assess if there are specific areas where the model struggles to predict churn accurately. 📉🧐
3. Advantages and Disadvantages: Document the pros and cons of using a Random Forest for this use case in terms of interpretability, accuracy, scalability, etc. 👍👎

**Business Metrics and Model Performance:**
- Linking Financial Metrics: If possible, relate the model performance to financial implications such as customer savings with the introduction of a discount proposition. This might involve making assumptions about customer behavior and response to the discount. 💰💡

This approach should cover model building, evaluation, and considering the impact on the business metrics for churn prediction. It's crucial to balance model performance evaluation with real-world implications for the business.
