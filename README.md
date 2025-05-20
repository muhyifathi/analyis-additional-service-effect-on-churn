How to Measure Impact of some Variables on Churn Rate ?
use case : churn in a fictional telco company

Measuring effect to churn rate or any other outcome variable like fraud, employe attrition, employee performance can be tricky. Because it's usually an observational data. The data is very heterogenous.

For example, in this case we want to measure effect from some additional service usage to churn rate. Based on data exploration there is a huge different between adtional service user and non additional service user. "Online Security" user has churn rate of 14.61% whil churn rate in general 27.00%. This effect isn't pure because it's probably affected by another variable such as demographic, tenure, location etc.

For this one, we corrected the effect from "14.61% -27.00% = -12.39%" to "-8.9%". Converting user into "Online Security" usage may decrease churn rate around 8.9%. Approach we used is of the most common causal infrence technique "Propensity Score matching".
source : https://lnkd.in/gT4MqYzE

Imagine saying to your boss, user or stakeholder from your analysis that this will decrease churn rate around 12% in truth is not that big, perhaps around 8.9% only.
