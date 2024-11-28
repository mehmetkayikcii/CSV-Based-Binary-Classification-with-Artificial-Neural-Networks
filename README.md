# CSV-Based-Binary-Classification-with-Artificial-Neural-Networks
Prediction Based on CSV Data Using Artificial Neural Networks
This project aims to perform predictions using an Artificial Neural Network (ANN) trained on data from a CSV file. The ANN model, implemented entirely in Python from scratch, solves a binary classification problem.

Project Summary

The project processes a health dataset to predict a target condition (e.g., the presence of a disease) based on specific health metrics (e.g., age, cholesterol level, blood pressure). The possible prediction classes are:
0: Target condition is absent.
1: Target condition is present.

The data is read from the heart_statlog_cleveland_hungary_final.csv file, normalized, and processed using an ANN model. The model predicts the classes based on the input data and improves its performance throughout the training process.

Technical Details

Model Features;
Input Layer:
Based on the number of features in the dataset.
Hidden Layer:
Contains 5 neurons and uses the sigmoid activation function.
Output Layer:
Contains a single neuron that outputs probabilities between 0 and 1.
Activation Function:
The sigmoid function is used in both the hidden and output layers.
Optimization:
The model is trained using the gradient descent algorithm.
Training Process
The model trains using forward propagation and backpropagation processes.
Training runs for 100,000 iterations.
Every 100 iterations:
The loss and accuracy values are reported in the terminal.
At the end of training, graphs depicting the loss and accuracy trends are generated.

Code Workflow
1- Data Loading and Preprocessing:
The dataset is read from a CSV file.
Numeric columns are normalized.
The target column is separated as the classification goal.

2-ANN Structure:
The model consists of input, hidden, and output layers.
Randomly initialized weights and biases are optimized during training.

3-Training and Prediction:
The model is trained using the input data.
The final classification accuracy is calculated at the end of the training process.

4-Performance Analysis:
Loss and accuracy graphs are plotted to visualize training performance.


Generated Graphs
To track the training process, two graphs are created:

1-Loss Graph:
Displays how the prediction error decreases over time during training.

2-Accuracy Graph:
Shows the progression of the model’s classification accuracy during training.


~~~Feel free to use, modify, and share this project for educational or research purposes. Suggestions and contributions are always welcome! 😊
