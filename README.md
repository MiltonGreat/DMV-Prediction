# DMV-Prediction

### Summary and Recommendations

#### 1. Overview

In this project, we implement a logistic regression model from scratch using Python and NumPy. The goal is to understand the fundamental building blocks of machine learning algorithms by implementing everything ourselves, including the logistic function, cost function, and gradient descent. By completing this project, I gained a deeper understanding of the mechanics behind logistic regression without relying on popular libraries like scikit-learn.

#### 2. Data

The dataset used is DMV_Written_Tests.csv, which contains the following columns:

- DMV_Test_1: Scores from the first written test.
- DMV_Test_2: Scores from the second written test.

Results: Binary outcome indicating whether a student passed (1) or failed (0) the test.

#### 3. Data Analysis Steps

1. Data Exploration and Visualization
2. Logistic Function
3. Cost Function
4. Gradient Descent
5. Prediction: Used the trained model to predict whether a student with given test scores will pass.
6. Evaluation

#### 4. Data Visualization

- Cost Function over Iterations: Visualized how the cost function decreases over 200 iterations of gradient descent, indicating model improvement.

- Decision Boundary: Plotted the decision boundary to show how the model separates students who passed from those who failed based on their test scores.

#### 5. Key Findings
      
- Cost at Initialization: 0.6931 (indicating an untrained model).
- Final Cost: 0.2049 (indicating a well-trained model).
- Training Accuracy: 89% (the model correctly classifies 89% of the students).
- Prediction: A student scoring 50 and 79 on the two DMV tests has a 71% chance of passing.

#### 6.  Source

https://www.kaggle.com/datasets/lunaticmaestro/dmv-written-test
