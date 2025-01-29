# NLP_1_sentiment_analysis

This project performs sentiment analysis using a deep learning model on the Emotion dataset

Dataset:
The dataset used for this project is the "Emotion" dataset, which contains texts labeled with various emotions. It was loaded using the load_dataset function from the Hugging Face datasets library.

Approach:
Text data is preprocessed and tokenized using standard NLP techniques.
A deep learning model (based on an LSTM architecture) is trained to classify emotions from the text.
The model is evaluated using validation data to assess its accuracy in predicting emotional labels.

Requirements:
TensorFlow
Hugging Face datasets
NumPy
Pandas
