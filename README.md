
# 📱 App User Segmentation Using Behavioral Data

This project analyzes user behavior data from a mobile application to identify patterns and segment users based on their activity, engagement, and spending habits. Using clustering techniques and interactive visualizations, the goal is to uncover actionable insights for retention, engagement, and monetization strategies.

---

## 📊 Overview

The project explores user data with the following objectives:

- Understand how screen time, app spending, and reviews correlate with user retention.
- Segment users into meaningful clusters using K-Means clustering.
- Visualize and interpret the behavior of different user segments.
- Provide targeted recommendations for each user segment.

---

## 🧠 Key Features

- **Exploratory Data Analysis (EDA)** with interactive visualizations.
- **Behavioral Segmentation** using K-Means clustering.
- **Feature Engineering** to derive additional insights like `Spending per Minute` and `Time Since Last Visit`.
- **Model Evaluation** using the Elbow Method and Silhouette Score.
- **Segment Interpretation** with meaningful labels:
  - 💎 Loyal Spenders
  - 🚶 Wanderers
  - 🧊 Silent Churners
- **Actionable Recommendations** for each segment.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy** for data manipulation
- **Plotly** for interactive visualizations
- **Scikit-learn** for clustering and preprocessing

---

## 📁 Files

- `app_user_segmentation.py`: The complete Python script for data analysis, clustering, visualization, and insights.
- `userbehaviour.csv`: Dataset used for the analysis (ensure this is added or linked in your repo).

---

## 🔍 How It Works

1. **Load and explore the dataset**.
2. **Visualize relationships** between:
   - Average screen time vs spending
   - Screen time vs ratings
3. **Engineer features** for enhanced clustering.
4. **Normalize and cluster data** using K-Means.
5. **Label and visualize segments** interactively.
6. **Print personalized recommendations** for each segment.

---

## 📈 Visual Output

The project produces:
- Trendline scatter plots showing screen time vs spending/ratings.
- Segment distribution plot based on `Last Visited Minutes` and `Spending`.
- Elbow and silhouette analysis for optimal cluster count.

---

## 📌 Insights

- Users who uninstalled the app spent minimal time and money.
- Higher screen time is correlated with higher app spending.
- Three clear user segments emerged: loyal, at-risk, and inactive users.

---

## ✅ Recommendations

| Segment           | Action                                                                 |
|------------------|------------------------------------------------------------------------|
| 💎 Loyal Spenders | Offer exclusive perks and rewards.                                     |
| 🚶 Wanderers       | Use re-engagement strategies like push notifications.                 |
| 🧊 Silent Churners | Initiate retention campaigns and onboarding assistance before drop-off.|

---

## 🚀 Getting Started

1. Clone the repo  
   ```bash
   git clone https://github.com/yourusername/app-user-segmentation.git
   cd app-user-segmentation
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Add the `userbehaviour.csv` dataset to the working directory.

4. Run the script  
   ```bash
   python app_user_segmentation.py
   ```

---

## 🙌 Acknowledgements

This project was built to showcase practical clustering for behavioral segmentation in apps. Inspired by real-world retention and churn problems faced by app-based platforms.
