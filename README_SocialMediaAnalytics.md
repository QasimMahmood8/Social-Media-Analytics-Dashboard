
# 📊 Tableau Project: Social Media Analytics Dashboard

## 📘 Overview
This project analyzes **social media performance** using a Tableau dashboard built on top of a synthetic dataset.  
It visualizes engagement metrics (likes, shares, followers) and sentiment analysis across platforms and keywords over time.

---

## 🗂 Dataset Details
The dataset `social_media_analytics.csv` contains 180 days of simulated social media activity from platforms like Twitter, Instagram, TikTok, and LinkedIn.

| Column Name | Description |
|--------------|-------------|
| `date` | Date of post or data capture |
| `platform` | Social media platform |
| `post_id` | Unique post identifier |
| `keyword` | Keyword or hashtag analyzed |
| `likes` | Number of likes |
| `shares` | Number of shares/retweets |
| `followers` | Total followers at that time |
| `sentiment_score` | Sentiment score (-1 = negative, +1 = positive) |

---

## 🎨 Tableau Dashboard Ideas

### 1. **Engagement Over Time**
- Line chart showing daily average likes and shares per platform.
- Add filters for date range and keyword.

### 2. **Sentiment Analysis**
- Create a sentiment trend line by keyword or platform.
- Highlight spikes in positivity or negativity.

### 3. **Keyword Performance**
- Bar chart comparing total engagement (likes + shares) per keyword.
- Tooltip: average sentiment score per keyword.

### 4. **Platform Comparison**
- Use a bubble chart to compare total followers vs. engagement rate per platform.

---

## ⚙️ How to Use in Tableau

1. Download the dataset: `social_media_analytics.csv`  
2. Open Tableau Desktop or Tableau Public.  
3. Connect to the CSV file.  
4. Create the following calculated fields:
   ```text
   Engagement Rate = (SUM([Likes]) + SUM([Shares])) / AVG([Followers])
   ```
5. Build visualizations using `date`, `platform`, and `keyword` as dimensions.

---

## 💡 Skills Demonstrated
- Data visualization with Tableau  
- Social media analytics and KPI tracking  
- Sentiment trend analysis  
- Dashboard design and storytelling

---

## 🚀 How to Showcase on LinkedIn
> 🎉 Built a **Social Media Analytics Dashboard** in Tableau!  
> It tracks engagement, follower growth, and sentiment trends across multiple platforms using realistic data.  
> Skills: Tableau, data visualization, storytelling with data, and sentiment analysis.  
>  
> 💾 GitHub Repo: [your link here]

---

## 🏁 License
MIT License – free to use and modify.
