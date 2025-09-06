# 📺 YouTube Channel Analytics - Web Scraping

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white) ![Web Scraping](https://img.shields.io/badge/Web%20Scraping-4CAF50?style=for-the-badge&logo=selenium&logoColor=white) ![YouTube API](https://img.shields.io/badge/YouTube%20API-FF9800?style=for-the-badge&logo=googlecloud&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![Data Analysis](https://img.shields.io/badge/Data%20Analysis-9C27B0?style=for-the-badge&logo=databricks&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![CSV](https://img.shields.io/badge/CSV-1572B6?style=for-the-badge&logo=files&logoColor=white)  

Python web scraping project using YouTube API to analyze popular data science educators, comparing their channel performance and video content patterns.

## 🎯 What This Project Does

This project scrapes YouTube data to understand:

- Channel performance comparison (subscribers, views, videos)
- Top performing videos and content patterns
- Upload frequency and timing analysis
- Content strategy insights for educational channels


## 📊 Channels Analyzed

**5 Popular Data Science Educators**:

- **Krish Naik**: Data Science \& Machine Learning
- **Corey Schafer**: Python Programming Tutorials
- **Alex The Analyst**: Data Analytics Career Guidance
- **techTFQ**: SQL \& Database Tutorials
- **Absent Data**: Data Science Content


## 📈 Key Analysis Results

### **Subscriber Rankings**

1. **Corey Schafer**: 1.45M subscribers (highest)
2. **Krish Naik**: 1.22M subscribers
3. **Alex The Analyst**: 1.09M subscribers
4. **techTFQ**: 374K subscribers
5. **Absent Data**: 60.8K subscribers

### **Total Views Comparison**

1. **Krish Naik**: 119.59M views (highest reach)
2. **Corey Schafer**: 103.17M views
3. **Alex The Analyst**: 51.62M views
4. **techTFQ**: 21.66M views
5. **Absent Data**: 4.77M views

### **Content Volume**

1. **Krish Naik**: 2,032 videos (most prolific)
2. **Alex The Analyst**: 368 videos
3. **Corey Schafer**: 245 videos
4. **Absent Data**: 225 videos
5. **techTFQ**: 140 videos

### **Monthly Upload Patterns**

- **Peak Month**: March (42 videos uploaded)
- **Active Months**: September (16), June (12), December (11)
- **Slow Months**: April (2), July (5), November (6)
- **Pattern**: Higher activity in spring and fall months


### **Top Performing Videos (techTFQ)**

1. **"Learn how to write SQL Queries"** - 1.7M views
2. **"SQL Basics Tutorial for Beginners"** - 1.4M views
3. **"SQL Window Function Tutorial"** - 1.3M views
4. **"SQL JOINS Tutorial"** - 1.3M views
5. **"Subquery in SQL Tutorial"** - 1.3M views

## 🔍 Key Insights

### **Content Strategy Patterns**

- **SQL content dominates** top performing videos
- **Beginner tutorials** get highest engagement
- **"How to" and "Tutorial"** keywords perform well
- **Practical examples** attract more viewers


### **Channel Growth Strategies**

- **Quality vs Quantity**: Corey Schafer has fewer videos but most subscribers
- **Consistency**: Regular uploaders maintain steady growth
- **Niche Focus**: Specialized content (SQL, Python) works well


### **Seasonal Trends**

- **March surge**: Highest upload activity (new year motivation)
- **Back-to-school**: September shows increased activity
- **Holiday drops**: Low activity in April and summer months


### **Performance Metrics**

- **Subscriber-to-view ratio**: Educational content has loyal audiences
- **Long-tail success**: Older tutorials continue getting views
- **Engagement quality**: Educational channels maintain high like ratios


## 🛠️ Technical Implementation

### **Tools Used**

- **YouTube Data API v3**: Official data access
- **Python Libraries**: googleapiclient, pandas, seaborn, plotly
- **Data Processing**: CSV export for further analysis
- **Visualization**: Multiple chart types for insights


### **Data Extraction Process**

1. **API Setup**: Configure YouTube Data API access
2. **Channel Data**: Extract subscribers, views, video counts
3. **Video Details**: Get individual video performance metrics
4. **Data Cleaning**: Process and structure extracted information
5. **Analysis**: Generate comparative insights and patterns
6. **Export**: Save results to CSV files for reuse

### **Key Functions**

```python
def get_channel_statistics(youtube, channel_ids):
    # Extract channel metrics
    
def get_video_stats(youtube, video_ids):
    # Get video performance data
```


## 📁 Project Files

```
📦 youtube-analytics-scraping/
├── 📄 README.md                           (This file)
├── 📓 YouTube_webscraping.ipynb           (Complete analysis)
├── 📋 YouTube_channels_data.csv           (Channel statistics)
├── 📋 YouTube_videos_data.csv             (Video performance data)
├── 📊 No_of_videos_per_month.jpg          (Upload patterns)
├── 📊 Top_10_techTFQ_Videos.jpg           (Best performing videos)
├── 📊 Visualizing_most_videos_posted.jpg  (Content volume)
├── 📊 Visualizing_most_viewed_channel.jpg (View comparison)
└── 📊 Visualizing_most_subscribing.jpg    (Subscriber ranking)
```


## 🚀 How to Run This Project

### **Prerequisites**

- Python 3.7+
- YouTube Data API key (free from Google)
- Libraries: `pip install google-api-python-client pandas seaborn plotly`


### **Steps to Use**

1. **Get API Key**: Create YouTube Data API key from Google Cloud
2. **Clone Repository**: Download project files
3. **Install Requirements**: Install needed Python packages
4. **Add API Key**: Insert your key in the notebook
5. **Run Analysis**: Execute all cells to get fresh data
6. **View Results**: Check generated charts and CSV files

## 💡 Skills Demonstrated

- ✅ **API Integration**: YouTube Data API implementation
- ✅ **Web Scraping**: Systematic data collection
- ✅ **Data Analysis**: Comparative performance analysis
- ✅ **Data Visualization**: Clear chart creation
- ✅ **Data Processing**: CSV export and manipulation
- ✅ **Python Programming**: Clean, functional code


## 🔮 Real-World Applications

### **For Content Creators**

- **Content Strategy**: Identify what topics work best
- **Upload Timing**: Understand seasonal patterns
- **Competition Analysis**: Compare against top channels


### **For Marketers**

- **Influencer Selection**: Choose partners based on real metrics
- **Audience Insights**: Understand educational content preferences
- **Trend Analysis**: Spot popular topics and formats


### **For Students/Learners**

- **Channel Discovery**: Find best educational content
- **Learning Paths**: Identify comprehensive tutorial series
- **Quality Assessment**: Choose channels with proven engagement


## 📝 Key Findings Summary

1. **Educational content has loyal audiences** with high engagement
2. **SQL tutorials consistently perform well** across platforms
3. **Beginner-focused content gets highest views** and engagement
4. **March and September are peak months** for educational content
5. **Quality over quantity strategy works** for subscriber growth
6. **Consistent uploading builds steady audience** over time
7. **"How to" and tutorial formats dominate** top performing videos

***

**Created by**: [sankaran-s2001](https://github.com/sankaran-s2001)
**Tools Used**: Python, YouTube Data API, pandas, seaborn, plotly
**Project Type**: Web Scraping \& Social Media Analytics
**Domain**: Educational Content Analysis

## ✉️ Contact

**Sankaran S**  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sankaran-s2001) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sankaran-s21/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sankaran121101@gmail.com)

*Complete YouTube channel performance analysis with actionable insights for content creators and educational marketers*
