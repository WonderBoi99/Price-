# Airbnb Price Intelligence

![Screenshot 2024-08-04 at 10 31 06 PM](https://github.com/user-attachments/assets/a5acaa77-7f18-4920-8799-7040fc2fefc9)

## Objectives 📋
The primary goal was to develop an AI model to generate accurate price estimates for Airbnb properties based on listing data (e.g., location, number of bedrooms). Another objective was to determine if incorporating sentiment analysis of reviews (positive, negative, neutral) could enhance the model's accuracy.

## Tech Stack 🧰
- Python
- PySpark
- Databricks

## Steps taken 🪜
- **Data Collection:** data source was from Airbnb properties in New York City, obtained from [Inside Airbnb](https://insideairbnb.com/).<br/>
  ![Screenshot 2024-08-05 at 8 13 47 AM](https://github.com/user-attachments/assets/88250ad3-1cae-4023-9910-8934e9da1d49)
- **Data Preprocessing:** <br/>
  ![Screenshot 2024-08-04 at 10 33 36 PM](https://github.com/user-attachments/assets/4bb1c5c0-9beb-4e4f-a8e0-1028e857f053)
- **Data Sentiment Labeling:** since manual sentiment labeling was tedious and time-consuming, prompted ChatGPT to label the reviews as Position (2), Negative (0), or Neutral (1).<br/>
  ![Screenshot 2024-08-05 at 8 13 47 AM](https://github.com/user-attachments/assets/d7a7e803-384b-4b69-8d1b-2379405f1fd1)
- **Creating Natural Language Processing Model:** experimented with Machine Learning classification algorithms like Logistic regression (best result), Random forest, and Naive bayes.<br/>
  ![Screenshot 2024-08-05 at 8 23 07 AM](https://github.com/user-attachments/assets/07e411d6-4bde-45e4-988e-c25cf4011650)
- **Used Natural Language Processing Model to label all the unlabelled reviews:**<br/>
  ![Screenshot 2024-08-05 at 8 40 36 AM](https://github.com/user-attachments/assets/765d69b7-d865-49cf-b50c-fcb4e0964ae4)
- **Creating Price Prediction Model:** experimented with Machine Learning regression algorithms like Linear regression(best result), Decision Tree, and Gradient boosting(best result).<br/>
  ![Screenshot 2024-08-05 at 8 46 54 AM](https://github.com/user-attachments/assets/541ee6cd-988d-4f1f-85ba-3aa33d6c0688)
- **Fine Tuning of HyperParameters to optimize model performance:**<br/>
  ![Screenshot 2024-08-05 at 8 49 33 AM](https://github.com/user-attachments/assets/6c180bf0-9558-4070-a165-a668db80589c)

## Reflection 🤔
- Sentimental Analysis was beneficial to the overall model performance
- Need more data

## More Information 📖
Please refer to the [Detailed Project Report](https://github.com/Nikhil-Naikar/Airbnb-Pricing-Intelligence/blob/main/Price%20Prediction%20Model%20Report.pdf).


 
