# MNIST Image Classification

This project uses machine learning to classify handwritten digits from the MNIST dataset. I compare several classification algorithms to see which one performs the best.

## Data

I used the MNIST dataset, which has 70,000 images of handwritten digits. The dataset is split into 60,000 training images and 10,000 test images. Each image is 28x28 pixels and labeled with the digit it represents (0-9). The data comes from http://yann.lecun.com/exdb/mnist/.

## Models

I compared the following classification algorithms:
- Support Vector Classification (`SVC`)
- Random Forest Classification (`RandomForestClassifier`)
- Neural Network Classification (`MLPClassifier`)
- XGBoost Classification (`XGBClassifier`)
- Logistic Regression (`LogisticRegression`)

## Results

I evaluated each algorithm on the test data and compare their performance. We report the performance of the best-performing algorithm.
