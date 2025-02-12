# Indian-Airline-Customer-Review-AI-Week-5-

**Project Overview**
This project involves Natural Language Processing (NLP) analysis of customer reviews for Indian Airlines. The goal is to analyze customer feedback, extract insights, and identify sentiment patterns to improve airline services and customer satisfaction. Using Python and NLP techniques, we have performed data cleaning, exploratory data analysis (EDA), sentiment analysis, and feature engineering, preparing the dataset for future predictive modeling.

**Business Problem**
In the competitive airline industry, customer satisfaction plays a crucial role in business success. Airlines often receive large volumes of customer reviews on various platforms, making it difficult to manually extract meaningful insights.
Key Business Questions
What are common complaints and positive experiences in customer reviews?
How do customers perceive service quality, delays, baggage handling, and staff behavior?
What factors contribute to positive or negative sentiment?
How can airlines use customer feedback to improve service offerings?

By analyzing customer reviews, airlines can identify areas of improvement, enhance customer experience, and ultimately increase customer retention and brand reputation.

**Project Objectives**
The primary objective of this project is to analyze customer sentiment and uncover key insights from textual reviews to help Indian Airlines:
Understand Customer Sentiment – Categorizing customer feedback into positive, neutral, and negative sentiment.
Identify Service Strengths and Weaknesses – Finding common keywords in customer complaints and praise.
Improve Decision-Making – Providing actionable insights for operational and service improvements.
Enhance Competitive Positioning – Helping airlines make data-driven business decisions to stand out in the market.

**Steps Followed in the Project**

**Step 1: Data Collection & Loading**
I used the Indian Airlines Customer Reviews Dataset containing customer reviews, ratings, airline names, dates, and recommendations. The dataset was uploaded to Microsoft Azure (Machine Learning) for processing. I loaded the dataset using Pandas and checked for missing values or formatting issues.
**Step 2: Data Cleaning**
To prepare the dataset for analysis: Removed special characters, numbers, and punctuation from the text, Converted all text to lowercase for consistency, Removed short words (less than three characters) to reduce noise, Applied stopword removal (words like "the", "and", "is" were removed to keep only meaningful words), Stored the cleaned text in a new column
**Step 3: Exploratory Data Analysis (EDA)**
Word Frequency Analysis – Instead of a word cloud, we used a bar chart to visualize the top 20 most common words in reviews, Bigram Analysis – Identified common two-word phrases that appeared in customer reviews, Sentiment Distribution – Visualized customer ratings distribution (1-10 scale) using a histogram to understand the general sentiment.
**Step 4: Feature Engineering**
Bag of Words (BoW) – Converted textual reviews into a numerical matrix of word occurrences, TF-IDF (Term Frequency-Inverse Document Frequency) – Gave importance to rare but meaningful words in customer feedback.
**Step 5: Dataset Saving and Upload**
The processed dataset was saved as a CSV file, The final dataset was uploaded to GitHub for submission and further modeling.

**Key Findings**
Frequent Complaints – Common negative keywords included "delay", "lost baggage", "poor service".
Positive Feedback – Words like "great flight", "friendly staff", "comfortable" appeared frequently in positive reviews.
Sentiment Trends – A large portion of the reviews had negative ratings (1-4), indicating potential areas for service improvement.
Common Issues – Bigram analysis showed repeated complaints like "late flight", "lost luggage", "poor customer support".

![download](https://github.com/user-attachments/assets/008056f9-f81d-4728-8c5d-a668bbda9b33)
![Screenshot 2025-02-12 135704](https://github.com/user-attachments/assets/146510e8-26a8-4ace-995f-3a66d089c46d)
![download (1)](https://github.com/user-attachments/assets/5e01c44c-cf6b-4889-8812-b4ba8a8fef57)
![download (2)](https://github.com/user-attachments/assets/2b038b29-c6a0-48bc-9d16-28ec10bdc73b)

**Benefits of the Project**
Customer Experience Improvement - Airlines can identify key pain points in customer complaints and take proactive measures.
Brand Reputation Enhancement - Addressing negative feedback helps improve customer trust, Positive sentiment analysis can help airlines promote their strengths
Data-Driven Decision Making - Airlines can use this data to strategically improve policies, adjust pricing models, and implement better customer support services.
Competitive Advantage - By improving customer satisfaction, airlines can boost customer loyalty and increase revenue and edge over competitors

**Conclusion**
This project successfully analyzed Indian Airlines' customer reviews, revealing key trends and sentiments. By leveraging NLP and text analytics, airlines can gain actionable insights to improve service quality and customer satisfaction. This data-driven approach allows for better decision-making, increased customer retention, and a stronger market position in the airline industry.


