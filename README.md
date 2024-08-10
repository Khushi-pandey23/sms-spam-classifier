# SMS-Spam-Classifier

This project is an SMS Spam Classifier that uses machine learning to identify and filter out spam messages from legitimate ones. The model is trained on a dataset of SMS messages labeled as spam or ham (non-spam) and predicts the likelihood of new messages being spam.

## Features
- Preprocesses SMS text data by cleaning and normalizing the text.
- Extracts features using techniques like TF-IDF vectorization.
- Trains a machine learning model (e.g., Naive Bayes, SVM) to classify SMS messages.
- Evaluates the model performance using accuracy, precision, recall, and F1-score.
- Provides a user-friendly interface for predicting whether an SMS message is spam.

## Dataset
The model is trained on the SMS Spam Collection Dataset from the UCI Machine Learning Repository. It contains 5,574 SMS messages labeled as spam or ham.

## Model
The classifier is built using a Naive Bayes model with TF-IDF vectorization. The choice of model was based on its effectiveness in text classification tasks.

## Results
The model achieved the following performance metrics:

Accuracy: 97.2931	%
Precision: 100%

## Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or create a pull request.
