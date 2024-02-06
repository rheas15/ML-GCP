# Machine Learning Engineering: Sentiment Analysis Model Deployment and Cloud Integration

## Description
This project focuses on the integration of Machine Learning models with the Google Cloud Platform for deployment and accessibility. I build a sentiment analysis model for financial text data using a Multinomial Naive Bayes classifier in scikit-learn. Cloud Functions are used to host the model and enable querying through HTTP requests. The project also includes a user-friendly interface for querying the model and displaying the sentiment prediction.


## Methodology
1. **Training the ML Model:** The model is trained using financial text data. Data preprocessing, model training, and evaluation are performed using scikit-learn.
   
2. **Storing the Pipeline on Cloud:** The trained model pipeline is stored on the cloud using Google Cloud Storage for easy accessibility.

3. **Cloud Functions:** Functions are implemented to access the model from the cloud and make predictions based on user input.

4. **Querying the Model:** A user-friendly interface is provided for users to input text data and receive sentiment predictions from the deployed model.


## Industrial Applications
The sentiment analysis model developed in this project has various applications in the financial industry:
- **Market Analysis:** Financial institutions can analyze sentiment from news articles, analyst reports, and press releases to gain insights into market trends.
- **Trading Strategies:** Research and trading teams can use sentiment analysis to identify market sentiment and adjust their trading strategies accordingly.
- **Risk Management:** Risk management teams can monitor sentiment around specific financial instruments or market segments to identify potential risks and take appropriate risk mitigation measures.

