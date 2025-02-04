# PCOS Data Analysis - Exploratory Data Analysis (EDA)

## 📌 Project Overview
Polycystic Ovary Syndrome (PCOS) is a prevalent hormonal disorder affecting women worldwide. This project focuses on analyzing PCOS data to uncover key insights related to symptoms, lifestyle factors, and potential associations.

## 📊 Objectives
- Explore the prevalence of PCOS in different demographics.
- Identify common symptoms and their associations.
- Examine the impact of BMI, lifestyle, and mental health on PCOS.
- Use statistical methods to find meaningful correlations.

## 📝 About PCOS
PCOS is a hormonal disorder causing enlarged ovaries with small cysts. Symptoms include irregular periods, excessive androgen levels, weight gain, and insulin resistance. Understanding PCOS is crucial for early diagnosis and lifestyle management.

## 📂 Dataset Overview
- **Type:** Categorical-heavy dataset (mostly Yes/No values)
- **Key Features:**
  - **Symptoms:** Menstrual irregularity, hormonal imbalance, hyperandrogenism, hirsutism, etc.
  - **Lifestyle Factors:** Diet, exercise, and sleep habits
  - **Health Metrics:** BMI, mental health status, family history

## 🛠️ Tools & Technologies Used
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook for analysis
- Feature Engineering & Normalization
- Cramér’s V for correlation analysis    

## 🔬 Methodology
### 1️⃣ Data Preprocessing
- Label encoding categorical values
- Feature engineering (Sleep Score, Diet Score, Exercise Score, Healthy Lifestyle Score)
- Normalization of numerical values

### 2️⃣ Exploratory Data Analysis (EDA)
- **PCOS Prevalence:** 22% of women in the dataset have PCOS
- **Common Symptoms:** Menstrual Irregularity, Hormonal Imbalance, and Hirsutism
- **BMI & PCOS:** Higher BMI observed in PCOS cases, but no direct age correlation
- **Lifestyle Impact:** Women without PCOS tend to have healthier habits
- **Childhood Trauma:** Possible association with PCOS cases
- **Cramer's V Analysis:** Strong correlation with hormonal imbalance, hyperandrogenism, and mental health

## 📌 Key Insights
✅ PCOS is most common in the **20-25 age group** and **unmarried women**
✅ Lifestyle factors such as **diet, exercise, and sleep quality** may influence PCOS risk
✅ **Mental health and childhood trauma** may be potential risk factors
✅ **Statistical correlations** confirm strong links between PCOS and hormonal disorders

## 🚧 Challenges Faced
- High categorical dominance made predictive modeling difficult
- Complex feature engineering required to quantify lifestyle factors
- Needed effective visualizations to communicate insights better

## 📍 Conclusion
This analysis provides valuable insights into PCOS prevalence and related factors. Due to the categorical nature of the data, the project was concluded at the **EDA stage** rather than proceeding to predictive modeling.

## 📎 Next Steps
- Extend analysis with additional datasets to improve generalizability
- Explore time-series data for tracking PCOS symptoms over time
- Investigate possible interventions based on lifestyle factors

💡 **Open for feedback and collaboration! Let’s discuss more about PCOS and data-driven insights in healthcare.**

