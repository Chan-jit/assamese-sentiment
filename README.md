Assamese Sentiment Analysis (Bidirectional LSTM - Keras)
This repository provides a robust framework for sentiment analysis of Assamese-language text using deep learning (Bidirectional LSTM). It includes preprocessing, class balancing, model training, evaluation, and visualization. The workflow is implemented in Python with TensorFlow/Keras.

Features
Language: Assamese (Unicode Bengali script)

Preprocessing: Normalization, Unicode filtering, cleaning.

Class Balancing: Uses compute_class_weight for handling class imbalance.

Tokenization: Supports rare and out-of-vocabulary words.

Neural Model:

Embedding layer

Bidirectional LSTM (with dropout)

Dense layers, softmax output

Early Stopping: Prevents overfitting.

Class Weighting: Increases robustness on imbalanced data.

Evaluation: Confusion matrix, classification report, macro/micro/weighted F1-scores.

Visualizations: Accuracy and loss curves.
