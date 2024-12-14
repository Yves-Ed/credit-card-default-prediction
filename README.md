# Credit Card Default Prediction

## Project Overview
This project involves analyzing and predicting credit card default risk using historical customer data. The goal is to identify the key factors influencing defaults and provide actionable business insights to improve risk management.

### Key Highlights
- **Domain**: Credit Risk Analysis
- **Tools Used**: Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Objective**: Build a predictive model to assess default risk and provide strategic recommendations.
- **Model Performance**: ROC AUC: 0.7824

## Business Questions Addressed

### 1. Primary Default Factors
- What factors are most indicative of default risk?
- Key Findings:
  - Payment history is the strongest predictor (e.g., `PAY_0` is most significant).
  - Recent bill amounts strongly influence default probability.
  - Higher credit limits correlate with lower default risk.

### 2. Credit Limit Relationships
- How do credit limits vary across demographic segments?
- Key Findings:
  - Middle-aged, married individuals tend to receive the highest credit limits.
  - Higher credit limits are associated with lower default rates.
  - Education level has a moderate impact on credit limit decisions.

### 3. Repayment Trends
- Are there patterns in repayment behavior that indicate default risk?
- Key Findings:
  - Early payment delays are strong predictors of future default.
  - Distinct repayment patterns exist across age and marital status groups.

## Strategic Recommendations

### Risk Assessment Enhancement
- Implement an early warning system based on payment delays.
- Weight recent payment history heavily in risk models.
- Monitor the bill amount to credit limit ratio for high-risk customers.

### Credit Limit Strategy
- Adjust limits based on payment history and demographic factors.
- Implement age-specific credit limit policies.
- Introduce a graduated increase system based on consistent payment behavior.

### Customer Segmentation
- Develop targeted strategies for high-risk age groups.
- Create monitoring programs for first-time delay customers.
- Implement segment-specific communication strategies.

## Predictive Model

### Model Details
- **Algorithm**: Random Forest Classifier
- **Performance Metric**: ROC AUC (0.7824)
- **Feature Importance**:
  - Payment History (`PAY_0`, `PAY_2`, etc.)
  - Recent Bill Amounts
  - Credit Limit

## Data Source
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)
- **License**: Public domain

## How to Run the Notebook

### Prerequisites
- Install Python 3.8 or above.
- Install the following libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Steps
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Credit_Card_Default_Predictor.ipynb
   ```
3. Follow the steps in the notebook to:
   - Load and preprocess the dataset.
   - Analyze data and visualize trends.
   - Build and evaluate the predictive model.

## Next Steps
- Integrate real-time payment monitoring systems.
- Develop segment-specific intervention strategies.
- Automate early warning systems for default risk.

## Author
Yves Edouard (https://github.com/Yves-Ed) | Data Analyst Enthusiast | Open to Collaborations

---

Feel free to contribute or suggest improvements to this project!
