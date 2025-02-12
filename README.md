This repository contains two machine learning and deep learning projects:

Titanic Survival Prediction - A classical ML problem using logistic regression, decision trees, and ensemble models.

Fashion MNIST Classification - A deep learning project using TensorFlow and Keras to classify images of clothing items.

 Titanic Survival Prediction

📌 Objective

Predict which passengers survived the Titanic disaster using machine learning models.

📊 Dataset

Source: Kaggle - Titanic Dataset

Features:

Pclass, Sex, Age, SibSp, Parch, Fare, Embarked

Target Variable: Survived (0 = No, 1 = Yes)

🏗 Models Used

✔ Logistic Regression✔ Decision Trees✔ Random Forest✔ Gradient Boosting

📈 Key Steps

Data Preprocessing: Handling missing values, feature encoding, and scaling.

Exploratory Data Analysis (EDA): Visualizing survival rates based on different features.

Model Training & Evaluation: Using accuracy, precision, recall, and F1-score.

Hyperparameter Tuning: Optimizing model performance.

🔹 Results: Achieved an accuracy of ~80% using ensemble learning.

👕 Fashion MNIST Classification

📌 Objective

Classify images of clothing items into 10 categories using a neural network.

📊 Dataset

Source: TensorFlow Fashion MNIST

Classes: 10 categories (T-shirts, trousers, pullovers, dresses, etc.)

Data Size: 60,000 training images & 10,000 test images (28x28 grayscale)

🏗 Model Architecture

✔ Input Layer (Flatten)✔ Dense Layer (128 neurons, ReLU)✔ Dropout (20%)✔ Output Layer (Softmax for classification)

📈 Key Steps

Data Preprocessing: Normalizing pixel values.

Building a Neural Network: Using TensorFlow & Keras.

Training & Evaluation: Using accuracy and loss metrics.

Optimization: Experimenting with different optimizers (Adam, SGD).

🔹 Results: Achieved ~92% accuracy on test data.


Objective

Classify images of clothing items into 10 categories using a neural network.

📊 Dataset

Source: TensorFlow Fashion MNIST

Classes: 10 categories (T-shirts, trousers, pullovers, dresses, etc.)

Data Size: 60,000 training images & 10,000 test images (28x28 grayscale)

🏗 Model Architecture

✔ Convolutional Neural Network (CNN)✔ Input Layer (Conv2D, ReLU)✔ MaxPooling Layer✔ Dense Layer (128 neurons, ReLU)✔ Dropout (20%)✔ Output Layer (Softmax for classification)

📈 Key Steps

Data Preprocessing: Normalizing pixel values and reshaping input.

Building a CNN: Using TensorFlow & Keras with multiple convolutional layers.

Training & Evaluation: Using accuracy and loss metrics.

Optimization: Experimenting with different optimizers (Adam, SGD) and batch normalization.

Data Augmentation: Enhancing model generalization.

🔹 Results: Achieved ~94% accuracy on test data with CNN.

