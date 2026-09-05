# Social Media Engagement Analytics and Prediction

## 📌 Project Overview
**Social Media Engagement Analytics and Prediction** is a data science project that analyzes **5,000 social media posts with 20 features** to understand the factors associated with social media engagement.

The project uses data cleaning, exploratory data analysis, statistical analysis, outlier treatment, visualization, and predictive analysis to identify engagement patterns and generate data-driven recommendations.

---

## 🎯 Objectives
The main objectives of this project are to:

- Understand social media engagement patterns.
- Identify factors associated with higher engagement.
- Compare engagement across different platforms.
- Analyze content-type performance.
- Study the relationship between sentiment and engagement.
- Analyze engagement by posting time.
- Examine the impact of media usage and verification status.
- Analyze influencer tiers and engagement.
- Identify high-performing posts.
- Generate data-driven recommendations.

---

## 📊 Dataset
The dataset contains **5,000 social media posts and 20 features**.

### Important Features

- Platform
- Content Type
- Likes
- Comments
- Shares
- Views
- Saves
- Follower Count
- Engagement Rate
- Posting Hour
- Sentiment
- Influencer Tier
- Media Usage
- Verification Status
- Timestamp
The primary metric analyzed in this project is **Engagement Rate**.

---

## 🔄 Project Workflow

### 1. Data Loading
The dataset was loaded into Python using **Pandas** for analysis.

### 2. Data Cleaning
The following preprocessing steps were performed:

- Checked for missing values.
- Checked for duplicate records.
- Verified data types.
- Cleaned categorical values.
- Removed unnecessary whitespace.
- Converted the Timestamp column into datetime format.

### 3. Outlier Detection and Treatment
Outliers were detected using the **Interquartile Range (IQR) method**.

Outliers were identified in variables including:

- Likes
- Comments
- Shares
- Views
- Saves
- Engagement Rate
Instead of deleting these observations, **IQR-based capping** was applied to reduce the influence of extreme values while preserving the dataset.

### 4. Exploratory Data Analysis
The project analyzes:

- Platform performance
- Content-type performance
- Sentiment categories
- Influencer tiers
- Verification status
- Media usage
- Posting hours
- High-performing posts

### 5. Correlation Analysis
Correlation analysis was performed to understand relationships between numerical variables and engagement-related metrics.

### 6. Data Visualization
Multiple visualizations were created to communicate the findings effectively.

These include:

- Bar charts
- Line charts
- Histograms
- Box plots
- Scatter plots
- Correlation heatmaps

---

## 📈 Key Analyses

### Platform Analysis
Average engagement rates were compared across different social media platforms to identify differences in platform performance.

### Content-Type Analysis
Different content formats were analyzed to determine how content type is associated with engagement.

### Sentiment Analysis
Posts were compared across sentiment categories to understand differences in engagement behavior.

### Posting-Time Analysis
Engagement rates were analyzed by posting hour to identify potentially stronger posting periods.

### Influencer Analysis
Different influencer tiers were compared to understand their relationship with engagement.

### Verification and Media Analysis
Verified versus non-verified accounts and posts with versus without media were analyzed for engagement differences.

### High-Performing Posts
Posts with the highest engagement rates were examined to identify common characteristics and potential patterns.

---

## 📊 Visualizations
The project includes visualizations such as:

1. **Average Engagement Rate by Platform**
2. **Average Engagement Rate by Posting Hour**
3. **Engagement Rate Distribution**
4. **Correlation Heatmap**
5. **Views vs Engagement Rate**
6. **Content Type vs Engagement**
7. **Sentiment vs Engagement**
8. **Influencer Tier vs Engagement**

---

## 💡 Key Insights
The analysis demonstrates that social media engagement can vary based on multiple factors, including:

- Platform
- Content type
- Posting time
- Sentiment
- Influencer tier
- Media usage
- Verification status
- Audience interaction metrics
Engagement metrics such as **likes, comments, shares, views, and saves** provide useful information for evaluating post performance.

The analysis of high-performing posts also helps identify patterns that can support future content planning.

---

## 🚀 Recommendations
Based on the analysis, the following recommendations can be considered:

- Focus on platforms showing stronger engagement performance.
- Prioritize content formats associated with higher engagement.
- Schedule important content during stronger-performing posting hours.
- Encourage audience interaction using questions and calls-to-action.
- Use relevant hashtags and media strategically.
- Monitor likes, comments, shares, views, saves, and engagement rate continuously.
- Use data-driven insights instead of relying only on follower count.

---

## 🛠️ Technologies Used
| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Data science and analytical utilities |
| Jupyter Notebook | Project development |
---

## 📁 Project Structure

```
Social_Media_Analytics/
│
├── README.md
├── Social_Media_Analytics.ipynb
├── dataset/
│   └── social_media_data.csv
├── images/
│   └── visualizations/
└── requirements.txt
```

> Update the filenames above if your actual GitHub files use different names.

---

## 🎥 Project Demonstration Video
A **3–5 minute project demonstration video** explaining the dataset, preprocessing, analysis, visualizations, findings, and recommendations is available here:

**Project Video:**
[https://drive.google.com/file/d/186G6H7sZyVSKTebipCdM5cpcOUOt5ywV/view?usp=sharing](https://drive.google.com/file/d/186G6H7sZyVSKTebipCdM5cpcOUOt5ywV/view?usp=sharing)

---

## 🔗 Project Links

### GitHub Repository
[https://github.com/gamepatt78/Social_Media_Analytics](https://github.com/gamepatt78/Social_Media_Analytics)

### LinkedIn Project Post
[https://lnkd.in/p/gCRBhPtT](https://lnkd.in/p/gCRBhPtT)

### Project Demonstration Video
[https://drive.google.com/file/d/186G6H7sZyVSKTebipCdM5cpcOUOt5ywV/view?usp=sharing](https://drive.google.com/file/d/186G6H7sZyVSKTebipCdM5cpcOUOt5ywV/view?usp=sharing)

---

## 👨‍💻 Author
**Athwin Videsh M**

**MCA Graduate | Aspiring Data Scientist**

---

## 📋 Project Deliverables

- ✅ Public GitHub Repository
- ✅ Professional README
- ✅ Project Demonstration Video — 3–5 minutes
- ✅ LinkedIn Project Post
- ✅ EncoderX Mention
- ✅ Required Hashtags

---

## 🏷️ Required Hashtags
**#EncoderX #DataScience #Internship #LearningInPublic**

---

## 📜 Declaration
This project demonstrates the practical application of Python-based data analysis, exploratory data analysis, statistical techniques, visualization, and data-driven decision-making to understand social media engagement.
