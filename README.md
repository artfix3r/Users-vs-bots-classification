# Users-vs-bots-classification
#### Dataset taken from kaggle @juice0lover
#### If you wish you can find dataset [here](https://www.kaggle.com/datasets/juice0lover/users-vs-bots-classification)
## About Dataset 
This dataset contains profile data collected from VK.com (VKontakte), Russia's largest social network, for distinguishing between genuine users and automated bots. The data includes both numerical and categorical features extracted from user profiles.

## Data Collection:
Collected from public VK.com profiles.
Includes both verified human users and verified bot accounts.
Represents realistic social network conditions with incomplete profiles.

## Feature Types:
Numerical Features (NaN values preserved):
Activity metrics (average posts per week, hashtag usage, etc.)
Friend/follower counts.
Categorical Features (missing values marked as 'unknown'):
Profile attributes (has_photo, has_mobile, etc.)
Privacy settings (is_closed_profile, etc)
Binary flags (can_post, can_message, etc)

## Data Processing:
Missing values handled differently by feature type:
Categorical: Filled with 'unknown' string
Numerical: Preserved as NaN
Boolean values converted to binary (0/1) where applicable

Potential Use Cases:
Binary classification (user vs bot detection)
Social media behavior analysis
Anomaly detection in social networks
Feature engineering exercises

After trying this ML algorithm, Logistic Regression, Random Forest, and Ada Boost, CatBoost and etc . The final results are :
![image](https://github.com/user-attachments/assets/596f1795-b089-484a-98b6-54436690cd7c)


