# Breast-Cancer-SVM-
## Support Vector Machine (SVM) Classification

This repository contains Python code demonstrating the implementation and comparison of **Support Vector Machines (SVM)** using two different kernels: **Linear** and **Radial Basis Function (RBF)**.

The models are applied to the built-in **Wisconsin Breast Cancer Dataset** from scikit-learn to classify tumors as benign or malignant.

-----

### Key Features

  * **Binary Classification:** Solves a classic two-class problem.
  * **Kernel Comparison:** Directly compares the performance of the **Linear** and **RBF** kernels.
  * **Scikit-learn Implementation:** Uses standard, efficient libraries for data handling, modeling, and evaluation.
  * **Evaluation Metrics:** Reports model **accuracy** and a detailed **classification report** for both models.

-----

### Setup and Installation

1.  **Clone the Repository:**

    ```bash
    git clone [Your Repository URL]
    cd [Your Repository Name]
    ```

2.  **Install Dependencies:**
    You will need `numpy` and `scikit-learn`.

    ```bash
    pip install numpy scikit-learn
    ```

-----

### How to Run

1.  Open your preferred Python environment (e.g., a Jupyter Notebook or a Python script).
2.  Run the provided classification code.

The output will display the test accuracy and a full classification report for both the Linear and RBF kernel models, allowing for a clear performance comparison.

-----

### Results Overview

The final output will summarize the performance:

  * **Linear Kernel Accuracy:** `[Example: 0.9825]`
  * **RBF Kernel Accuracy:** `[Example: 0.9912]`

This comparison highlights which kernel is more effective at drawing the decision boundary for this specific dataset.
