# Spam Classification via Logistic Regression

This project implements a **Logistic Regression** model to classify emails from the UCI Spambase dataset as either "Spam" or "Non-Spam." 

## Project Documentation
For a comprehensive breakdown of our methodology, hyperparameter tuning, and final performance analysis, please view our full report:

### [Read the Full "About" PDF here](https://emiliowm.github.io/Spam-Detection-Logistic-Regression/About.pdf)

---

## Project Highlights
* **Model:** Custom Mini-batch Stochastic Gradient Descent (SGD) with L2 Regularization.
* **Optimal Hyperparameters:** * **Learning Rate ($\alpha$):** 0.1
    * **Batch Size ($B$):** 16
    * **Epochs:** 50
    * **$\lambda$:** 0.01
* **Results:** Achieved a **test accuracy of 89.87%** and a cross-entropy loss of 0.3143.
* **Comparison:** Includes an analysis against scikit-learn’s L1-regularized implementation for feature sparsity.

## Authors
* **Maxine Somers**
* **Emilio Wagner Munguia**
* **Connor Tate**

*Project Date: February 27, 2026*
