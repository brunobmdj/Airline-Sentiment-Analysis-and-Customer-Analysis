# About

This project is a part of the Data Science virtual internship program offered by Forage with British Airways.

# The virtual Internship is divided into two main tasks;
1. Web scraping to gain company insights
2. Predicting customer buying behaviour

# Task 1 - Web scraping to gain company insights

- Goal: To find customer's sentiment on the airline's service.

- Process:
  1. Web Scrape data from third-party source using Beautiful Soup.
  2. Perform cleaning of data using NLTK performing Text Lemmatization, Stemming, Removing Special Characters.
  3. Use WordCloud, NLTK, Textblob to understand the most commonly used words and find the overall sentiment of the Customers and the nature of the ratings whether they are positive, negative or neutral.

- Result: We found that most reviews were with positive sentiment with over 54%, about 3.8% were neutral and remaining 41% were with negative sentient.

# Task 2 - Predicting customer buying behaviour

- Goal: To predict customer's booking behaviour and find which customers are most likely to book a holiday in the future and to find what is the impact of each feature.

- Process:
  1. Perform data cleaning followed by EDA to understand the relationships of all features.
  2. Present the analysis in a dashboard [Link Here]{https://public.tableau.com/app/profile/bruno.maria7382/viz/BA_Forage/Dashboard1?publish=yes}
  3. Develop a predictive model to accuractely predict whether the customer will confirm the booking or not with the help of some Feature Engineering and find the features that are most co-related with the customer booking.

- Result: Using AdaptiveBoosting ML algorithm along with HyperParameter tuning, we achieved a prediction accuracy of over 90% for both Train and Test data and found that *Length of Stay* is the most influential feature which plays a role in the customer booking the ticket.
