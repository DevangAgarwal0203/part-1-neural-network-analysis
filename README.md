# Part 1 - Neural Network Fundamentals and Training Behavior Analysis

## Project Objective
The objective of this project is to build and analyze a feed-forward neural network for customer churn prediction using structured customer data.

This project demonstrates:
- Data preprocessing
- Neural network model building
- Model training and evaluation
- Hyperparameter experimentation
- Analysis of overfitting and class imbalance

---

## Dataset Information

Dataset Name:
customer_churn_nn.csv

Dataset Source:
Provided in the Module 5 shared Google Drive folder.

The dataset contains customer-related features such as:
- Region
- Plan type
- Payment method
- Tenure
- Monthly charges
- Satisfaction score
- Data usage
- Customer churn label

Target Variable:
- churn
    - 1 = customer left the service
    - 0 = customer stayed

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

## Project Workflow

### 1. Dataset Understanding
- Loaded and explored the dataset
- Checked missing values
- Analyzed feature types
- Visualized target distribution

### 2. Data Preprocessing
- Removed customer_id column
- Encoded categorical variables
- Applied feature scaling
- Performed train-test split

### 3. Neural Network Model
The neural network included:
- Input layer
- Hidden layers with ReLU activation
- Output layer with sigmoid activation

Loss Function:
- Binary Crossentropy

Optimizer:
- Adam Optimizer

### 4. Model Evaluation
The model was evaluated using:
- Accuracy
- Loss
- Confusion Matrix
- Classification Report

### 5. Hyperparameter Experimentation
Multiple experiments were performed by changing:
- Number of neurons
- Activation function
- Batch size

### 6. Key Observations
- The model achieved high overall accuracy.
- The dataset showed class imbalance.
- Accuracy alone was not sufficient for evaluation.
- The model struggled to identify minority churn cases.

---

## Repository Structure

part-1-neural-network-analysis/

│

├── data/

├── results/

│   ├── accuracy_curve.png

│   ├── loss_curve.png

│   ├── confusion_matrix.png

│   └── model_comparison_table.csv

│

├── part1_neural_network_analysis.ipynb

├── requirements.txt

└── README.md

---

## Conclusion

This project provided practical understanding of:
- Forward pass
- Backpropagation
- Activation functions
- Neural network optimization
- Hyperparameter tuning
- Overfitting and imbalance challenges

The project successfully demonstrated neural network fundamentals using a real-world customer churn prediction problem.
