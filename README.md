# Student Loan Repayment Prediction

## Project Overview

The goal of this project is to develop a machine learning model using a deep neural network to predict whether the borrower will be able to repay their student loan or not. By implementing a neural network model that can create predictions with the company's data, we can successfuly create predictions on student loan repayments for each client.

## Installation Instructions

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ezwang8/neural-network-challenge-1.git
   ```

2. **Verify Python Installation:**
   Check if Python is installed by running:
   ```bash
   python --version
   ```
   If Python is not installed, download it from [python.org](https://www.python.org/downloads/).

3. **Install Jupyter Notebook:**
   Install Jupyter Notebook (if not already installed):
   ```bash
   pip install notebook
   ```

4. **Install Required Packages:**
   Install the necessary Python libraries:
   ```bash
   pip install pandas scikit-learn tensorflow
   ```

5. **Navigate to the Project Directory:**
   ```bash
   cd neural-network-challenge-1
   ```

6. **Launch Jupyter Notebook:**
   Start the Jupyter Notebook interface:
   ```bash
   jupyter notebook
   ```

7. **Open the Notebook:**
   Locate and open the `student_loans_with_deep_learning.ipynb` file and run the cells for analysis.

## Steps

1. **Prepare the Data:**
   - Read the dataset from `https://static.bc-edx.com/ai/ail-v-1-0/m18/lms/datasets/student-loans.csv`.
   - Preprocess the dataset by splitting into features (`X`) and target (`y`).
   - Scale the features data using `StandardScaler`.

2. **Build and Train a Neural Network Model:**
   - Create a deep neural network with two hidden layers, both using the `relu` activation function.
   - Compile and train the model with the `adam` optimizer and `binary_crossentropy` loss function.
   - Save the model to a file (`student_loans.keras`).

3. **Evaluate the Model:**
   - Use test data to evaluate the model’s loss and accuracy.
   - Generate predictions from the trained model and evaluate its performance with a classification report.

4. **Create a Recommendation System (Optional Discussion):**
   - Outline how a recommendation system could be built for student loans using the trained model and additional features.

## Summary

- The neural network model achieved an accuracy of 73% on the test data.
- The accuracy would be improved with content-based filtering because the model relies on feature comparisons and user's preferences.
- For safety, the model must also include a cyber security program to prevent private data breaches. Along with a healthy training program to ensure the model only uses diverse and unbiased data.
