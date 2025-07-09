# 📊 YouTube Data Analysis using Hadoop Ecosystem

> Unlocking the hidden trends in YouTube videos using Big Data Technologies like Hadoop, Spark, Pig, Hive, and Java MapReduce.

---

## 🧠 Project Overview

The online video platform YouTube has become an integral part of global digital consumption. Every minute, over 500 hours of video content is uploaded, creating a massive influx of unstructured and semi-structured data. This project aims to harness this enormous data stream and convert it into actionable insights using Big Data analytics frameworks. 

Through this project, we:
- Analyze large-scale YouTube video metadata.
- Extract hidden patterns in viewer behavior.
- Predict engagement drivers (likes, dislikes, comments, shares).
- Provide recommendations for content optimization.

The primary goal is to assist content creators, marketers, and analysts in making informed decisions by understanding the elements that influence video popularity.

---

## 🔍 Motivation

The vast majority of YouTube creators strive to increase their viewership, subscribers, and engagement rates. However, not every video performs well. Numerous factors, including category, keywords, upload timing, audience demographics, and interaction metrics like likes or dislikes, determine video performance.

At the same time, brand marketers seek reliable influencers or channels for promotions. This study helps identify top-performing content creators who can be ideal partners for marketing.

To uncover these dynamics, we apply a suite of Hadoop ecosystem technologies, enabling fast, distributed processing of massive datasets.

---

## 🚀 Objectives

- ✅ Analyze structured and unstructured YouTube data at scale.
- ✅ Leverage Hadoop and Spark for high-performance analytics.
- ✅ Determine top categories, channels, and engagement metrics.
- ✅ Visualize results for better interpretation.
- ✅ Suggest content and marketing strategies.

---

## 🛠 Tools and Technologies

| Tool/Tech | Purpose |
|----------|---------|
| **Apache Hadoop** | Distributed storage and batch processing |
| **Apache Pig** | Data cleaning and transformation scripting |
| **Apache Hive** | SQL-like query execution over HDFS |
| **Apache Spark** | In-memory fast processing and aggregation |
| **Java MapReduce** | Custom batch job logic for data analysis |
| **Python** | Data manipulation, scripting, and visualization |
| **YouTube API** | Real-time data fetching |
| **Kaggle Dataset** | Supplementary structured data |

---

## 📃 Dataset Description

We use both **structured data from Kaggle** and **unstructured data via the YouTube Data API**.

### Features Collected:
- `video_id`
- `title`
- `channel_title`
- `category_id`
- `publish_time`
- `views`
- `likes`
- `dislikes`
- `comment_count`
- `tags`
- `description`
- `country`

This comprehensive feature set allows us to answer a wide array of questions related to performance and engagement.

---

## 🌐 System Architecture

```plaintext
+---------------------+
| YouTube API/Kaggle  |
+---------+-----------+
          |
          v
+-------------------+
|     HDFS Storage   |
+---------+---------+
          |
    +-----+-----+
    |           |
+--------+ +-----------+
| HiveQL | |   Pig     |
+--------+ +-----------+
    |           |
    +-----+-----+
          |
      +---v---+
      | Spark  |
      +---+---+
          |
    +-----v-----+
    | Visualization |
    +---------------+


---

## 📈 Methodology

### 1. **Data Collection**
- Retrieved trending video data from Kaggle.
- Collected real-time data via the YouTube Data API.

### 2. **Data Storage**
- Stored data in **HDFS** for scalability and redundancy.

### 3. **Data Processing**
- **Pig** scripts for transformation and cleansing.
- **Hive** queries to perform SQL-based analytics.
- **Spark** for in-memory transformations.
- **Java MapReduce** jobs to implement logic-heavy aggregations.

### 4. **Visualization**
- Python’s matplotlib/seaborn used to generate insightful charts.
- Visualized results for top categories, trending videos, and more.

---

## 📊 Insights and Graphs

- 🏆 Top 10 Most Viewed Videos
- 💝 Most Liked Videos
- 💔 Most Disliked Videos
- 🌟 Top Performing Channels
- 🌚 Most Active Categories (Music, Comedy, Entertainment)
- 🌍 User Location Map
- 🔍 Word Cloud of Video Titles

---

## 🎓 UML Diagrams

### ✅ Use Case Diagram
Illustrates user interactions like analyzing trends, viewing graphs, and filtering by category.

### 📊 Class Diagram
Defines data structures like `Video`, `Channel`, `Engagement`, and their relationships.

### ⏱ Sequence Diagram
Represents sequence of operations: Data fetch → Transformation → Query → Visualization.

### ♻️ Activity Diagram
Outlines workflow of data ingestion, preprocessing, processing, and output.

---

## 🗃 Results

Key outcomes from our analysis:
- **Music and Comedy** are top-viewed categories.
- Videos with **emotional titles** tend to have more engagement.
- High **comment-to-view** ratios correlate with viral potential.
- Some channels outperform others regardless of upload frequency.

---

## 🖼 Screenshots

> **Note**: Replace with actual graphs when uploading to GitHub.

- Top 10 Videos by Views  
- Top Trending Channels  
- Likes vs Dislikes Analysis  
- Comments Heatmap  
- Category Distribution Pie Chart  
- Viewer Locations (Geo Map)  

---

## 🚧 Challenges Faced

- Handling inconsistent/unstructured API responses.
- Optimizing Spark jobs to avoid out-of-memory errors.
- Integrating Pig and Hive outputs into a unified dashboard.

---

## 🚀 Future Enhancements

- ✨ Add ML model to predict video success probability.
- 📈 Create a live dashboard with real-time YouTube data.
- 🧬 Integrate sentiment analysis using comments.
- 🤖 Train recommender system for content strategies.

---

## 🙋‍♂️ Target Users

- YouTube Content Creators  
- Influencer Marketing Teams  
- Data Science Students & Educators  
- Researchers studying digital behavior  

---

## 📅 Timeline

| Phase | Duration | Tools Used |
|-------|----------|------------|
| Data Collection | 1 Week | API, Kaggle |
| Preprocessing | 1 Week | Pig, Python |
| Storage & Querying | 1 Week | Hive, HDFS |
| Analysis & Results | 2 Weeks | Spark, MapReduce |
| Visualization | 1 Week | Matplotlib, Seaborn |

---

## 👨‍💼 Author

**Venkat Sai Charan Karasala**  
Software Engineer | Cloud Enthusiast | Data Analyst  
[GitHub](https://github.com/saicharankarasala) • [LinkedIn](https://linkedin.com/in/venkat-saicharan-karasala)
