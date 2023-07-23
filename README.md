# Handwritten-Letter-Recognition-using-Naive-Bayes-Classifier

In this project, a Multinomial/Bernoulli Naive Bayes Classifier was built from scratch to predict handwritten letter recognition. The classifier utilizes concepts of Probability and Statistics to make predictions without relying on any predefined machine learning library.

## Technologies Used
* Python
* Numpy
* Pandas

## Project Overview
1. Data Preparation: The handwritten letter recognition dataset is preprocessed, and features are extracted for each image, converting them into a format suitable for training the Naive Bayes Classifier.

2. Multinomial/Bernoulli Naive Bayes Classifier: The classifier is implemented from scratch, considering either the Multinomial or Bernoulli variant, depending on the specific requirements of the task.

3. Training the Classifier: The classifier is trained on the preprocessed dataset, where probability calculations are performed based on feature occurrences in different classes (letters).

4. Prediction: Given a new handwritten letter image, the classifier predicts the letter by calculating the probabilities of it belonging to each class and selecting the class with the highest probability.

5. Evaluation: The performance of the Naive Bayes Classifier is assessed using appropriate metrics, such as accuracy, precision, recall, and F1-score.

## Usage

To use this project, follow these steps:

1. Prepare your handwritten letter recognition dataset in a format compatible with the project's implementation.
2. Clone the repository to your local machine.
3. Install the required dependencies (NumPy and Pandas) if you haven't already.
4. Run the Python script containing the Naive Bayes Classifier implementation.
5. Input a new handwritten letter image and receive the predicted letter from the classifier.

