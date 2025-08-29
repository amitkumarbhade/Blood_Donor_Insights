# 🩸 Blood Donor Behavior Analysis: Insights into Donation Patterns and Predictions  

## 📌 Project Overview  
This project explores the **UCI Blood Transfusion dataset (748 records, 5 attributes)** to analyze donor behavior.  
The aim is to understand **donation patterns, key behavioral drivers, and future donation likelihood**,  
and to generate actionable insights for **blood banks to improve donor engagement and retention**.  

---

## 🎯 Objectives  
1. **Data Exploration**  
   - Explore donor history (recency, frequency, total volume donated, time since first donation).  
   - Examine relationships between donation patterns and likelihood of future donations.  

2. **Visualization**  
   - Build histograms, scatter plots, and correlation heatmaps to highlight patterns.  
   - Compare donors vs. non-donors by key features.  

3. **Insights & Recommendations**  
   - Identify which factors most influence future donations.  
   - Segment donors (Active, Warm, Lapsed, Dormant).  
   - Suggest strategies for improving donor retention and outreach.  

4. **(Optional Extension)**  
   - Train simple predictive models (Logistic Regression, Random Forest, Gradient Boosting).  
   - Evaluate model performance (accuracy, recall, F1, ROC-AUC).  
   - Use probabilities to rank donors for targeted campaigns.  

---

## 📊 Dataset  
- **Source:** UCI Machine Learning Repository – Blood Transfusion Dataset  
- **Records:** 748 donors  
- **Features:** 5 attributes (donor behavior only, no medical lab values)  
- **Missing Values:** None  

### Key Columns  
- **Recency** → Months since last donation  
- **Frequency** → Total number of donations  
- **Monetary** → Total blood volume donated (ml)  
- **Time** → Months since first donation  
- **Class** → Target variable (1 = donated in March 2007, 0 = did not)  

---

## 🔍 Project Steps  
1. **Data Overview** – structure, descriptive statistics, missing values  
2. **Exploratory Data Analysis (EDA)** – distributions, correlations, donor behavior trends  
3. **Visualizations** –  
   - Class distribution  
   - Histograms of features  
   - Correlation heatmap  
   - Scatter plots (Recency vs Frequency, etc.)  
4. **Insights** – interpret patterns in donor activity  
5. **(Optional ML Extension)** – model training, evaluation, feature importance  
6. **Recommendations** – donor segmentation and targeted engagement strategies  
7. **Conclusion** – summarize findings, limitations, and future directions  

---

## 💡 Key Insights  
- Majority of donors **did not donate again** in March 2007 (~76% vs 24%).  
- **Recency** (time since last donation) is the strongest predictor of donation likelihood.  
- **Frequency** (past donations) is highly correlated with total volume (Monetary) and also predicts future donations.  
- **Time since first donation** has less influence; recent activity matters more than long-term history.  
- Donors can be segmented as **Active, Warm, Lapsed, Dormant** for targeted re-engagement.  

---

## 🏆 Conclusion  
This analysis shows that **donor recency and frequency are key drivers of future donations**.  
By segmenting donors and applying targeted engagement campaigns, blood banks can:  
- Retain **active donors** with thank-you and reminders.  
- Re-engage **warm donors** with easy booking links.  
- Target **lapsed donors** with personalized campaigns.  
- Place **dormant donors** in low-priority nurture tracks.  

A predictive model (Random Forest) further demonstrated that donor behavior can be used to rank donors by probability of future donations, supporting more efficient outreach strategies.  

---

## 🚀 How to Run  
You can run the notebook directly in **Google Colab**:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amitkumarbhade/Blood_Donor_Insights/blob/main/Blood_Donor_Insights.ipynb)  

Steps:  
1. Upload the notebook (`Blood_Donor_Analysis.ipynb`) to Colab.  
2. Upload the dataset file (`blood.csv`) when prompted.  
3. Run cells sequentially to reproduce the analysis and visualizations.  

---
