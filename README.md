## Breast Cancer Classification using K-Nearest Neighbors (KNN)

### 👨‍🎓 Student Details

- **Name:** Rohan Ramdhan Decharwal
- **Course:** AI/ML Internship
- **Batch:** Batch 1(A)
- **Mentor:** Nishant Shrivastava

---

## 📌 Objective

The objective of this project is to develop a **K-Nearest Neighbors (KNN)** classification model to predict whether a breast tumor is **Malignant (M)** or **Benign (B)** based on diagnostic measurements. The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, evaluation, and classification performance analysis.

---

## 📂 Dataset

**Breast Cancer Wisconsin Diagnostic Dataset**

🔗 **Kaggle Dataset:**  
https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

### Features

The dataset contains multiple numerical features extracted from breast cancer cell nuclei, including measurements such as:

- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal Dimension
- Other diagnostic measurements

### Target Variable

- Diagnosis (M = Malignant, B = Benign)

---

## 🛠 Libraries Used

The following Python libraries were used in this project:

- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## ⚙️ Methodology

The project was completed using the following steps:

1. Loaded the dataset using Pandas.
2. Displayed the first five records, dataset information, and summary statistics.
3. Checked for missing values.
4. Removed unnecessary columns (if any).
5. Encoded the target variable.
6. Standardized the feature values using feature scaling.
7. Split the dataset into **80% training** and **20% testing**.
8. Trained a **K-Nearest Neighbors (KNN)** classifier with **K = 5**.
9. Predicted tumor classifications for the test dataset.
10. Evaluated the model using:
    - Accuracy Score
    - Precision
    - Recall
    - F1-Score
11. Generated a **Confusion Matrix** to visualize classification performance.

---

## 📊 Results

The KNN classifier successfully classified breast tumors as **Malignant** or **Benign**. Model performance was evaluated using Accuracy, Precision, Recall, and F1-Score. The Confusion Matrix provided a clear representation of correctly and incorrectly classified cases. Feature scaling significantly improved the model's performance because KNN relies on distance calculations between data points.

---

## 📝 Conclusion

This project demonstrates the effectiveness of the K-Nearest Neighbors algorithm for breast cancer classification using diagnostic measurements. The model achieved reliable classification performance by identifying patterns in the feature space. Proper feature scaling played a crucial role because KNN uses distance-based calculations, and unscaled features can negatively impact predictions. Although KNN is simple and effective for classification tasks, one limitation is that its prediction time increases with larger datasets, making it less efficient for very large-scale applications. Overall, KNN serves as a strong baseline classifier for medical diagnosis problems involving structured numerical data.

---

## 📁 Repository Structure

```
Assignment-4/
│── Assignment_4.ipynb
│── README.md
```

---

## 👤 Author

**Rohan Ramdhan Decharwal**

**AI/ML Internship – Batch 1(A)**

**Mentor:** Nishant Shrivastava
