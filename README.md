# Social Media Engagement Analysis

## 📌 Project Overview
This repository contains an Exploratory Data Analysis (EDA) of social media engagement metrics. The project processes raw tweet data to uncover trends regarding media views, user interactions, click-through behavior, and app opens. 

The analysis was performed using Python, applying strict filtering constraints (time-based, character/string-matching, and integer odd/even logic) to isolate high-performing data subsets.

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook / Google Colab

## 🎨 Visual Theme
The entire visualization suite has been custom-configured with a strict **black background and electric blue color palette** to ensure high contrast, readability, and a modern, professional aesthetic across all generated graphs.

## 📂 Dataset
* **File:** `Tweet.xlsx - SocialMedia (1).csv`
* **Contents:** Impressions, engagements, media views, retweets, likes, click breakdowns, and raw tweet text with UTC timestamps.

## 📊 Analysis Tasks & Results

### Task 1: Media Views vs. Engagements
Analyzed the correlation between media views and actual engagements for high-reply tweets (>10 replies) with high word counts (>50 words) on odd-numbered dates.
![Task 1 Scatter Plot](task1_scatter.png)

### Task 2: Clicks Breakdown
Categorized URL, user profile, and hashtag clicks for weekday tweets with even impressions and short word counts (<30 words).
![Task 2 Pie Chart](task2_pie.png)

### Task 3: Top 10 Tweets by Total Reactions
Ranked the highest-performing tweets based on the sum of likes and retweets using strict weekday and impression constraints.
![Task 3 Bar Chart](task3_bar.png)

### Task 4: Monthly Engagement Rate Trends
Tracked the average engagement rate across months, comparing tweets with and without media, explicitly filtering out tweets containing the capital letter 'C'.
![Task 4 Line Chart](task4_line.png)

### Task 5: High-Performance Comparison
Compared replies, retweets, and likes for tweets that performed above the median engagement threshold during the summer months (June–August), filtering out the letter 'S'.
![Task 5 Clustered Bar Chart](task5_clustered.png)

### Task 6: App Opens vs. Engagement Rate
Evaluated the average engagement rate for tweets that drove App Opens versus those that did not, specifically for standard working hours (9 AM - 5 PM).
![Task 6 Donut Chart](task6_donut.png)

## 🚀 How to Run the Code
1. Clone this repository:
   ```bash
   git clone [https://github.com/tusharsingh/social-media-analysis.git](https://github.com/tusharsingh/social-media-analysis.git)
