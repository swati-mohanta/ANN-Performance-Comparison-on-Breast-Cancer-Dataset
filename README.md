# ANN Performance Comparison on Breast Cancer Dataset

### 📌 Project Overview
This project explores how **different numbers of neurons** and **learning rates** affect the performance of an **Artificial Neural Network (ANN)** built using Scikit-learn’s `MLPClassifier`.  
The experiment uses the **Breast Cancer dataset** from `sklearn.datasets`.

---

### 🧰 Technologies Used
- **Python**
- **Scikit-learn**
- **Pandas**
- **Matplotlib**
- **NumPy**

---

### ⚙️ Experiment Details

#### **Case 1 – Varying Neurons (Fixed Learning Rate = 0.01)**
- **256 neurons:** Accuracy = 0.9561  
- **10 neurons:** Accuracy = 0.9649  

#### **Case 2 – Varying Learning Rates (Fixed Neurons = 32)**
- **Learning rate = 0.01:** Accuracy = 0.9561  
- **Learning rate = 0.1:** Accuracy = 0.9474  

🕒 Execution time and accuracy were also compared to analyze trade-offs between **model complexity** and **training efficiency**.

---

### 📊 Visualization
A bar chart compares the accuracy of all four test cases:

> `neurons>100`, `neurons<50`, `lr=0.01`, `lr=0.1`

---

### 🧩 Results Summary
| Case | Configuration | Accuracy | Time (s) |
|------|----------------|-----------|-----------|
| 1a | Neurons = 256 | 0.9561 | 0.2466 |
| 1b | Neurons = 10 | 0.9649 | 0.1124 |
| 2a | LR = 0.01 | 0.9561 | 0.0736 |
| 2b | LR = 0.1 | 0.9474 | 0.0539 |

📈 **Observation:**  
- Lower neurons slightly improved accuracy and reduced computation time.  
- Higher learning rate led to faster but slightly less accurate results.
