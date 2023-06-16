# Email Spam Detector
This repository contains code and resources for email spam classification using various machine learning algorithms. The goal is to accurately classify emails as either spam or non-spam (ham).

## Dataset
The dataset used for training and evaluation is available in the repository (dataset.csv). It consists of labeled email data, where each email is associated with a target label indicating whether it is spam or ham.

## Models
The following machine learning models have been applied to the email spam classification task:

1. Logistic Regression

2. Naive Bayes

3. Support Vector Machine (SVM)

4. Decision Tree

5. K-Nearest Neighbors (KNN)

6. Bagging

7. Random Forest (Best Performing Model)

8. Gradient Boost

9. Adaboost


Among these models, the Random Forest classifier has shown the best performance in terms of accuracy and precision scores. However, you are encouraged to explore and experiment with other models to find the best fit for your specific requirements.

## Usage
To use the models provided in this repository, follow these steps:

1. Clone or download this repository to your local machine.

2. Load the desired model(s) using the provided .pkl files in your Jupyter Notebook or Python script.

3. Preprocess your email data and transform it into the appropriate format as shown in the provided Jupyter Notebook (email_spam_detection.ipynb).

4. Use the loaded model(s) to make predictions on new email data and classify them as spam or ham.

5. Feel free to explore the Jupyter Notebook for detailed code examples and instructions on loading and using the models.

## Evaluation
The performance of each model on the email spam classification task is as follows:

![Screenshot 2023-06-16 232642](https://github.com/deepshikhar23/Email-Spam-Detector/assets/116090674/5d90b672-fede-4be7-95af-da675b7d224e)


Please note that these scores are based on the evaluation performed on the provided dataset (dataset.csv). Your results may vary depending on the dataset and preprocessing techniques used.

## Contributing
Contributions to this project are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the code in this repository for personal and commercial purposes.
