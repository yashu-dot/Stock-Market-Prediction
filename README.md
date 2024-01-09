# Stock Market Prediction
## Overview
This project introduces an innovative stock market forecasting system, leveraging machine learning and deep learning models. It focuses on accurate predictions for selected publicly traded companies by incorporating historical stock data and sentiment-enriched tweets.

## Key Features
1. Data Sources: Utilizes historical stock data from Yahoo Finance and sentiment-enriched tweets from finviz.com.
2. Methodology: Employs a two-step process, forecasting next week's stock prices and integrating sentiment scores for investment viability.
3. Models Used: Includes Long Short-Term Memory (LSTM), Recurrent Neural Networks (RNN), Gated Recurrent Units (GRU), and ensemble techniques.
4. Accuracy: Achieves 63% accuracy without sentiment scores and 47% with sentiment analysis.
5. Data Collection: Historical stock data is collected from Yahoo Finance, and sentiment-enriched tweets are scraped from finviz.com.
6. Preprocessing: Text data is preprocessed, and sentiment analysis is performed using the Vader Sentiment Analyzer.
7. Visualizations: Various visualizations, such as heat maps, moving averages charts, and growth rate charts, provide insights into stock trends.
8. Models: Machine learning and deep learning models, including LSTM and GRU, are applied for forecasting and classification.
9. Investment Recommendation System: A user-friendly system is developed, allowing users to input stock names and dates to receive tailored investment advice.

## Results
Best Model: GRU emerges as the top-performing model, achieving a high R-squared score of 0.97.
Classification Accuracy: Logistic regression achieves 47% accuracy with sentiment scores and 63% without sentiment scores.

## Conclusion
This project contributes significantly to predictive analytics in the financial domain, offering a practical tool for investors and financial analysts. By integrating advanced models and sentiment analysis, it bridges gaps between traditional methodologies and contemporary financial demands.

## Future Works
Expand dataset for enhanced model accuracy.
Implement GPU support for improved model training.
Explore long-term market trend analysis for deeper insights.
