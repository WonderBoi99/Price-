# Airbnb Price Intelligence

![Screenshot 2024-08-04 at 10 31 06 PM](https://github.com/user-attachments/assets/a5acaa77-7f18-4920-8799-7040fc2fefc9)

## Objectives 📋
The primary goal was to develop an AI model to generate accurate price estimates for Airbnb properties based on listing data (e.g., location, number of bedrooms). Another objective was to determine if incorporating sentiment analysis of reviews (positive, negative, neutral) could enhance the model's accuracy.

## Tech Stack 🧰
- Python
- PySpark
- Databricks

## Steps taken 🪜
- **Data Collection:** data source was from Airbnb properties in New York City, obtained from [Inside Airbnb](https://insideairbnb.com/)<br/>
  ![Screenshot 2024-08-05 at 8 13 47 AM](https://github.com/user-attachments/assets/88250ad3-1cae-4023-9910-8934e9da1d49)
- **Data Preprocessing:** <br/>
  ![Screenshot 2024-08-04 at 10 33 36 PM](https://github.com/user-attachments/assets/4bb1c5c0-9beb-4e4f-a8e0-1028e857f053)
- **Data Sentiment Labeling:** since manual sentiment labeling was tedious and time-consuming, prompted ChatGPT to label the reviews as Position (2), Negative (0), or Neutral (1)<br/>
  ![Screenshot 2024-08-05 at 8 13 47 AM](https://github.com/user-attachments/assets/d7a7e803-384b-4b69-8d1b-2379405f1fd1)
- **Creating Natural Language Processing Model:** experimented with Machine Learning classification algorithms like Random forest, Naive Bayes, and Logistic regression (best result)<br/>
  ![Screenshot 2024-08-05 at 8 23 07 AM](https://github.com/user-attachments/assets/07e411d6-4bde-45e4-988e-c25cf4011650)
- 

- Experimented with different Machine Learning algorithms for the price prediction model:
  - Linear Regression
  - Decision Trees
  - Gradient Boosting



## More Details: <br>
Please refer to the Price Prediction Model Report.pdf in this repository.


 
