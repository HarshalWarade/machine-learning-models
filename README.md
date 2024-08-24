A quick add-on to my Machine Learning Journey! I built a classification model to recognize handwritten digits using the classic Digits Dataset. This model is now hosted on my GitHub as a pickle file.

The Digits Dataset consists of 1,797 images of handwritten digits, each 8x8 pixels in size. These grayscale images are flattened into 64-dimensional vectors, where each value represents a pixel’s intensity ranging from 0 (white) to 16 (black). The dataset includes digits from 0 to 9.

I used a Random Forest Classifier. The dataset was split into training and testing sets, with 80% of the data used for training and 20% for testing.
Evaluation: The model was evaluated based on its accuracy in classifying unseen test data.

Code Walkthrough:
Data Preparation: Loaded the Digits Dataset and saved it as a CSV file. The dataset consists of 64 features (pixel values) and corresponding labels (digits).
Model Training: Trained the Random Forest Classifier using the training subset of the data.
Predictions: Made predictions on both individual samples and the test set to evaluate model performance.
Accuracy: The model achieved an impressive accuracy score of 97.22% on the test set!
