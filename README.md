# Telecom-Churn-Prediction-Case-Study

# Problem Statement

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another.
In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. 
Customer retention has now become more important than customer acquisition.
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.


# Goal

Analyze customer-level data of a leading telecom firm

Build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
 
# Business Recommendations

If the local incoming minutes of usage (loc_ic_mou_8) is lesser in the month of August than any other month, then there is a higher chance that the customer is likely to churn

Target the customers, whose minutes of usage of the incoming local calls and outgoing ISD calls are less in the action phase (mostly in the month of August).

Target the customers, whose ‘outgoing others’ charge in July and ‘incoming others’ in August are less.

Also, the customers having value based cost in the action phase increased, are more likely to churn than the other customers. Hence, these customers may be a good target to provide offers.

Customers whose monthly 3G recharge in August is more, are likely to be churned.

Customers having decreasing STD incoming minutes of usage for operators T to fixed lines of T for the month of August are more likely to churn.

Customers with decreasing monthly 2g usage for August are most probable to churn.
Customers having decreasing incoming minutes of usage for operators T to fixed lines of T for August are more likely to churn.

‘roam_og_mou_8’ variables have positive coefficients (0.7135). That means for the customers, whose roaming outgoing minutes of usage is increasing are more likely to churn.

