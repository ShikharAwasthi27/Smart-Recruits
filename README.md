# Smart-Recruits
Analytics Vidhya Hackathon

Problem Statement: The problem stated  about a particular company Fintro ,a Financial Distribution company and  over the last 10 years, they have created an offline distribution channel across India. They sell Financial products to consumers by hiring agents in their network. They are looking data scientist like us (participants) to predict the target variable for each potential agent, which would help them identify the right agents to hire based on their previous recruitment process.

Link: https://datahack.analyticsvidhya.com/contest/the-smart-recruits/

About the data: Data was blend of various parameters like Manager DOB , Manager Grade , further details of manager and applicants. The target variable is Business Sourced whether the business was done or not.

Approach: The given data has scope for a lot of feature engineering but even after it, the model was not able to perform well. So, on 
closer inspection, I figured out that the order in which applications are received throughout a day was a significant predictor. Maybe,
managers got lazy in the afternoon so the conversion rates dropped for applications received later in the day. Including this feature in the model produced an AUC-ROC of 0.65 on the public dataset.
