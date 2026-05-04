
# Global YouTube Trend Analysis 📊

## Overview
This Python project analyzes global YouTube trending videos to uncover patterns in views, likes, categories, and publish times. The goal is to clean raw YouTube data and create meaningful visualizations that show what makes content go viral across different countries.

## Dataset
- **Source**: Kaggle YouTube Trending Dataset / YouTube Data API v3
- **Countries covered**: US, IN, GB, CA, DE, FR, RU, MX, KR, JP
- **Time period**: 2020-2024
- **Key features**: video_id, title, channel_title, category_id, publish_time, views, likes, dislikes, comment_count, tags

## Tech Stack
- **Language**: Python 3.10+
- **Libraries**: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn
- **Tools**: Jupyter Notebook, YouTube API, GitHub

## Key Analysis Done
1. **Data Cleaning**: Handled missing values, converted publish_time to datetime, decoded category IDs
2. **Exploratory Data Analysis**: 
   - Top trending categories by country
   - Best day/time to publish for max views
   - Correlation between likes, views, and comment count
3. **Visualizations**: 
   - Bar charts of top 10 categories globally
   - Heatmap of trending times by day/hour
   - Word cloud of most common tags in viral videos
4. **Insights Found**:
   - Entertainment & Music dominate 60%+ of trends globally
   - Videos published between 2-4 PM IST get 25% more views in India
   - Title length of 50-70 characters performs best

## How to Run
1. Clone this repo: `git clone https://github.com/rumadhlallerta38-design/Global_youtube_trend_analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Add your YouTube API key to `.env` file: `API_KEY=your_key_here`
4. Run notebook: `jupyter notebook youtube_analysis.ipynb`

## Project Structure<img width="1270" height="571" alt="py project" src="https://github.com/user-attachments/assets/2e1ed2e6-c552-4bbd-8dbb-fdcf428f2ff2" />
