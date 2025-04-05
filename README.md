# 📊 Marketing A/B Testing Analysis

This project analyzes the results of a marketing A/B test to evaluate ad campaign effectiveness.

##### 📌 Objective
- Determine **if the ad campaign was successful**
- Quantify **how much of the success can be attributed to the ads**

##### 🧪 Experiment Setup
- **Ad Group (Test):** Users exposed to advertisements
- **PSA Group (Control):** Users shown a public service announcement (PSA) instead of ads

##### 🧾 Dataset Overview
- **user_id:** Unique identifier for each user  
- **test_group:** 'ad' or 'psa' depending on exposure  
- **converted:** `True` if the user made a purchase  
- **total_ads:** Total number of ads the user saw  
- **most_ads_day:** Day with highest ad exposure  
- **most_ads_hour:** Hour with highest ad exposure

Data: [Marketing A/B Testing Dataset on Kaggle](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)


We'll analyze conversion rates, revenue impact, and statistical significance to guide campaign decisions
