This repository contains an original implementation of logistic regression built entirely from scratch using Python. The solution avoids high‑level machine learning libraries (such as scikit‑learn, TensorFlow, or PyTorch) and uses only NumPy, Pandas, Matplotlib, and standard Python libraries.  
The code in this project demonstrates the following:
1. Data Loading and Preprocessing: 
  Reads independent (features) and dependent (labels) data from CSV files, converts the data into NumPy arrays, and normalizes the features using z‑score normalization.
2. Manual Logistic Regression Implementation:
  - Sigmoid Function: Custom implementation of the logistic activation function.  
  - Cost Function: Calculation of the cross‑entropy (logistic regression) loss.  
  - Gradient Descent: A manual implementation of batch gradient descent to learn the weights and bias.
3. Visualization:  
  - Cost vs. Iteration graph demonstrating training convergence (for a learning rate of 0.1).
  - Decision Boundary Plot (for 2D datasets) showcasing how the model separates the classes.
  - Learning Rate Comparison Plot (over 100 iterations) comparing the effects of using different learning rates (0.1 vs. 5).
4. Model Evaluation:  
  The final part of the code computes evaluation metrics—including a confusion matrix, accuracy, precision, recall, and F1-score.
