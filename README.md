# Home_Assignment-3

## Student Details
Name : Nikhith Raju Konduru

700   : 700756171

crn   : 23849

## To run this file clone this repo and download the necessary files to execute

## Explanation of Tasks:


1.Load the IMDB Sentiment Dataset
We load the IMDB dataset, which contains movie reviews labeled as positive or negative. The data is pre-processed into integer-encoded sequences of words, and we use a limited vocabulary of the most frequent words.

2. Preprocess the Text Data
The reviews are padded to ensure they all have the same length, making them suitable for input to a neural network. This step standardizes the input size for the LSTM model.

3. Train an LSTM-based Model
We build an LSTM-based model to classify reviews as positive or negative. The model learns to capture patterns in the text through an embedding layer, an LSTM layer, and a dense output layer for classification.

4. Generate a Confusion Matrix and Classification Report
After training, we evaluate the model by generating a confusion matrix and classification report, which show performance metrics like accuracy, precision, recall, and F1-score. These help assess how well the model distinguishes between positive and negative reviews.

Precision-Recall Tradeoff: In sentiment classification, precision and recall need to be balanced. Precision indicates how many predicted positives were correct, while recall measures how many actual positives were captured.

