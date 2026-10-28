# Summary Report — Deep Learning Practical Exam Set A

## Overview
This practical covers five mini-projects using tabular data, images, time series, and text. Each section demonstrates data preparation, a model or processing pipeline, evaluation, and saved outputs.

## Tasks
**ANN — Diabetes classification:** The Pima Indians Diabetes dataset is used for binary classification. The intended workflow replaces impossible zero values in selected medical columns with medians, scales features with `StandardScaler`, and trains a Sequential neural network with hidden layers of 16 and 8 ReLU neurons. Evaluation includes accuracy, precision, recall, F1-score, and a confusion matrix.

**OpenCV — Image preprocessing:** Five images are processed through resizing, grayscale conversion, Gaussian blur, Canny edge detection, and contour detection. The included 5×5 grid is a demonstration using generated sample images, not real-world photos.

**CNN — CIFAR-10 classification:** The notebook selects 20,000 training images and 4,000 test images, normalizes pixel values, trains a CNN, plots learning curves, and compares true and predicted labels.

**RNN — Airline passenger forecasting:** Monthly passenger counts are transformed into 12-month input sequences. A SimpleRNN predicts the next month, and test predictions are converted back to passenger counts and evaluated with RMSE.

**Transformer — Sentiment inference:** A pre-trained DistilBERT sentiment pipeline classifies 25 custom movie-review sentences as positive or negative. Ambiguous examples may still receive one of these labels because the selected model does not offer a neutral class.

## Results and limitations
The OpenCV demonstration grid and intermediate images are included. Actual ANN/CNN accuracy, RNN RMSE, and Transformer prediction counts are not stated because the notebook has not yet been executed successfully from beginning to end. Record these values from the notebook after resolving the TensorFlow import issue. The OpenCV demo images demonstrate the method but do not replace the exam's option to use five real images.

## Reflection and next steps
Dense layers process tabular features, convolutional layers learn spatial patterns, recurrent layers process ordered sequences, and Transformers use attention to model relationships among words. Future improvements could include additional model comparisons, more robust validation, testing on representative real images, error analysis, and deployment through a simple application.

Before submission, execute all notebook cells, verify the real metrics and plots, save the trained `.h5` models, update this report with the actual results, and add the required video link to the GitHub README.
