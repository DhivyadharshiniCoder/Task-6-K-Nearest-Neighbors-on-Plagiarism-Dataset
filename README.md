# 🧠 Task 6 – K-Nearest Neighbors on Plagiarism Dataset

This task implements a **K-Nearest Neighbors (KNN)** classifier to predict whether a sentence pair is plagiarised, using their semantic similarity score as input.

---

## 📁 Dataset Used

- **File**: `similarity_output_task3.csv`
- **Features**:
  - `Similarity_Score`: Cosine similarity between sentence pairs
- **Label**:
  - `Plagiarised`: Binary value (1 = Yes, 0 = No)

---

## 🔧 Steps Performed

1. Loaded the dataset and selected the features
2. Split the dataset into training and testing sets
3. Trained a KNN model with K=3
4. Evaluated using Accuracy, Confusion Matrix, and Classification Report
5. Visualized accuracy scores for K from 1 to 10

---

## 📊 Results

- Best K: From accuracy plot
- Accuracy: Printed in output
- Confusion matrix and classification report shown

---

## 🖼️ Screenshot Output
![image](https://github.com/user-attachments/assets/d485e42b-742c-48f4-b66e-b78b2495b5fd)
![image](https://github.com/user-attachments/assets/c1a52d15-4138-42c9-a519-012f4d89a572)


## ❓ Interview Q&A Covered

- What is KNN?
- How KNN works with numeric features
- Choosing the best K
- Effect of outliers
- Distance metric used (Euclidean)

---

## ✅ Files


