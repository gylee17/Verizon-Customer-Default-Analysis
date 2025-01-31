# Verizon Customer Default Prediction

### Overview
Verizon sells phones on a contract basis, and customer defaults result in financial losses. This project develops a predictive model to assess default risk and optimize acceptance policies.

### Model Selection
We evaluated Logistic Regression, Random Forest, and XGBoost based on accuracy, precision, default rate, and financial impact.

Model	                  Accuracy	    Precision	    Default Rate	    Profit (Per 1M Customers)
Logistic Regression	     90.8%	        64.4%	        6.77%	             $151.3M
Random Forest	           91.6%	        66.2%	        5.58%	             $162.1M
XGBoost	                 91.4%	        66.6%	        5.98%	             $158.7M

Random Forest yields the highest profitability by reducing default losses.

### Business Impact
- Higher profit: +$58.2M net financial gain (56% increase).
- Lower default losses: -$66.7M by better customer selection.
- Safer revenue strategy: More selective acceptance improves financial stability.

### Key Recommendations
- Stricter Monitoring: Assess age and credit history for contract terms.
- Higher Down Payments: Reduce default risk but set a reasonable threshold.
- Proactive Engagement: Contact high-risk customers for financing options.
- Age-Specific Terms: Additional down payments or guardian signatures for younger users.
- Credit-Based Risk Mitigation: Charge premiums or conduct background checks for low-score customers.
