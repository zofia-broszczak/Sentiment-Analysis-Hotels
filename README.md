# Hotel Reviews Sentiment Analysis & Visualization

## Group Project | My Contributions: Sentiment Analysis & Visualization in Python and Power BI

**Overview**

This project analyzes hotel reviews to extract insights about customer sentiment and key trends. Using Sentiment Analysis with BERT, SQL and Power BI, we classify reviews as positive, negative, or neutral and explore their relationship with hotel ratings.

**Dataset description**
The analysis was performed on a dataset with hotel reviews (7282_1.csv) found on https://www.kaggle.com/datasets/datafiniti/hotel-reviews/data

**Key Features:**

- Review ID: Unique identifier for each review.
- Hotel categories: The categories of the hotel (e.g. hotel, motel, resort).
- City: The location of the hotel.
- Hotel name: The name of the hotel being reviewed.
- Review date: Date the review was posted.
- Review rating: Numerical rating (1 to 5 stars).
- Review text: Full text of the review provided by the user.
- User information: Optional fields such as user username or location, if available.

**Project Objectives**

1. Perform sentiment analysis on hotel reviews
2. Store data and sentiment analysis results in an SQL database.
3. Create visualizations in Python and Power BI to interpret findings.

**Technologies Used**

- Python: Sentiment analysis, data preprocessing, visualization; BERT Model
- SQL: Data extraction and transformation
- Power BI: Interactive data visualization

### **My Contributions:**

**Sentiment Analysis in Python**

- Used a multilingual BERT model to classify reviews as positive, neutral, or negative
- Generated star ratings (1-5) and sentiment scores (-1 to 1)
- Assigned sentiment labels:
1. Positive (score ≥ 0.5)
2. Negative (score ≤ -0.5)
3. Neutral (between -0.5 and 0.5)

**Visualizations in Python**

- Created a correlation matrix to analyze relationships between attributes
- Built heatmaps to explore data distributions
- Designed word clouds to highlight common themes in positive and negative reviews

**Power BI Visualizations**

- Sentiment overview: Breakdown of positive, neutral, and negative reviews
- Star rating histogram: Distribution of hotel ratings
- Filtering options: Analysis by date, hotel name, city
- Map visualization: Geographical sentiment trends across hotels
- Hotel performance table: Comparison of hotels by rating and sentiment

**Conclusions**

This project highlights how sentiment analysis and data visualization can reveal customer satisfaction trends in the hotel industry. By combining BERT-based classification and interactive Power BI dashboards, we extracted key insights that can help improve hotel services.
