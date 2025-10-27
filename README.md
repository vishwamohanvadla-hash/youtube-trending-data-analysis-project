# 📊 YouTube Trending Video Dataset Analysis

## 📄 Project Overview

This project analyzes the **YouTube Trending Videos Dataset** to uncover
insights about what makes a video trend --- such as relationships
between views, likes, dislikes, comments, categories, and upload times.

**Goal:** Understand patterns behind trending content using data
analysis and visualization.

**Dataset Used:** - `USvideos.csv` --- Trending videos in the U.S.
region. - `US_category_id.json` --- Mapping of category IDs to names.

------------------------------------------------------------------------

## 🧠 Key Analysis Performed

### 1. Trending Video Analysis

-   Identified frequently trending videos and top categories.
-   Defined "trending" as videos appearing consistently over multiple
    days.

### 2. Views, Likes & Dislikes Relationship

-   Explored correlations between views, likes, dislikes, and comments.
-   Calculated engagement ratios (`likes/views`, `comments/views`,
    etc.).

### 3. Publish Time Analysis

-   Examined how publish day and hour impact video popularity.
-   Found best times: **11 AM -- 2 PM**, mid-week uploads
    (Tuesday--Wednesday).

### 4. Text Analysis on Titles & Descriptions

-   Combined and tokenized video titles + descriptions.
-   Word cloud revealed popular keywords: **music**, **official**,
    **video**, **new**, **us**.

### 5. Category-Wise Analysis

-   Used **ANOVA** to test differences in average views by category.
-   Found significant differences --- Entertainment, Music, and Comedy
    dominate.

------------------------------------------------------------------------

## ⚙️ Technologies Used

  Library               Purpose
  --------------------- -----------------------
  pandas                Data manipulation
  matplotlib, seaborn   Visualization
  numpy                 Numerical operations
  scipy.stats           Statistical testing
  nltk                  Text preprocessing
  wordcloud             Text visualization
  json                  Parsing category data

------------------------------------------------------------------------

## 📈 Insights Summary

-   Higher engagement (likes, comments) correlates with more views.
-   Uploading mid-day, mid-week yields better performance.
-   Entertainment & Music categories dominate trending lists.
-   Titles with "official," "music," and "new" trend more often.

------------------------------------------------------------------------

## 🧾 Project Structure

    📁 YouTube_Trending_Analysis/
    │
    ├── USvideos.csv
    ├── US_category_id.json
    ├── youtube_analysis_index.pdf
    ├── youtube.csv
    ├── analysis_notebook.ipynb
    │
    ├── README.md
    │
    └── outputs/
         ├── correlation_matrix.png
         ├── wordcloud_tags.png
         ├── category_donut_chart.png
         └── views_by_publish_time.png

------------------------------------------------------------------------

## 🚀 How to Run

1.  **Clone the repository:**

    ``` bash
    git clone https://github.com/<your-username>/youtube-trending-analysis.git
    cd youtube-trending-analysis
    ```

2.  **Install dependencies:**

    ``` bash
    pip install pandas numpy matplotlib seaborn nltk wordcloud scipy
    ```

3.  **Run the analysis:**

    ``` bash
    jupyter notebook analysis_notebook.ipynb
    ```

------------------------------------------------------------------------

## 🔮 Future Improvements

-   Add data from multiple countries.
-   Develop a prediction model for trending videos.
-   Integrate YouTube API for real-time updates.

------------------------------------------------------------------------

## 👨‍💻 Author

**Vishwa Mohan**\
*Data Analysis \| Visualization \| Insights Generation*
