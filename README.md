# Netflix-Content-Acquisition-EDA
Exploratory Data Analysis of ~4,000 Netflix titles to identify key content success drivers across genre, language, and format. Includes feature engineering, engagement metrics, strategic insights, and data-backed recommendations to improve Netflix’s content acquisition and hit-rate efficiency.


```markdown
# 🎬 Netflix Content Acquisition Strategy – EDA Project  

## 📌 Overview  
This project analyzes ~4,000 Netflix titles to uncover what drives successful content performance. Using Exploratory Data Analysis (EDA), feature engineering, and audience engagement insights, the goal is to help optimize Netflix's content acquisition strategy and improve hit-rate, ROI, and catalog efficiency.

---

## 🎯 Objectives  
- Analyze Netflix’s catalog to identify success factors  
- Perform data cleaning & feature engineering  
- Study impact of genre, format, language, ratings & votes  
- Create engagement-based success metrics  
- Recommend data-driven content investment strategy  

---

## 🛠️ Tech Stack  
| Category | Tools |
|--------|-------|
| Language | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Data Source | TMDB API |
| Notebook | Jupyter Notebook |

---

## 📂 Project Files  


Netflix-Content-Acquisition-EDA/
├── Scrapping_the_netflix_data.ipynb
├── Data Cleaning of the netflix raw data.ipynb
├── complete analysis with insights.ipynb
├── raw_netflix_data.csv
├── netflix_cleaned_data.csv
├── Netflix project.pdf
├── Documentation of netflix content acquisition project.docx
└── README.md



---

## 📊 Key Insights  
### Hit Rate & Success Drivers  
- Only **5.7%** of titles are hits → huge optimization opportunity  
- **TV Shows outperform Movies** in success rate  
- **Animation, Sci-Fi, Thriller, Action** lead in performance  
- Oversaturation in **Drama & Comedy** with low ROI  
- Engagement + votes are stronger success signals than rating alone  
- Korean, Japanese & Spanish content rising → international potential  

---

## 📈 Major Findings  
| Area | Insight |
|------|--------|
Format | TV > Movies in audience success  
Genres | Expand high-hit categories, reduce Drama/Comedy volume  
Language | Diversify beyond English – tap Korean, Japanese, Spanish  
Quality | Require minimum quality threshold (rating ≥ 6.5)  
Audience Metrics | Engagement score stronger than rating alone  

---

## ✅ Recommendations  
| Strategy | Action |
|---------|--------|
Format Shift | Move toward **60% TV / 40% Movies**  
Genre Focus | Invest more in Thriller, Sci-Fi, Action, Animation  
Language Expansion | Boost Korean, Japanese, Spanish, Hindi content  
Quality Gate | Approve content only above rating & engagement threshold  
ROI Optimization | Remove low-performing titles & focus on proven content clusters  

> 📌 Expected impact: Hit-rate improvement from **5.7% → ~15%**

---

## 📂 Key Features Engineered  
- `rating_category`
- `engagement_score` (rating × log(votes))
- `language_grouped`
- `recent_release`
- `is_hit` (rating ≥ 7.5 & votes > 1000)
- `primary_genre`

---

## 🧠 Skills Gained  
- Data cleaning & wrangling  
- Feature engineering  
- Exploratory Data Analysis  
- Data visualization  
- Business insight generation & storytelling  
- Real-world media analytics understanding  

---

## 👥 Contributors  
- **Ravindra Nadh**
- **Chandu Nayak**
- 

**Special Thanks:** * Nagaraj (Trainer) , Tasleema Noor (Mentor) – Innomatics Research Labs*

---

## 🚀 Future Enhancements  
- Build ML model to predict content success  
- Create interactive dashboard (Power BI / Streamlit)  
- Add time-series forecasting for demand prediction  

---

## ⭐ Support  
If you like this project, please ⭐ the repository and connect with me on LinkedIn!  

---

```

---

