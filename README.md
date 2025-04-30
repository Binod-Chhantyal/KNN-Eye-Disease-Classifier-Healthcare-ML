# Healthcare ML Project: Eye Disease Detection using KNN Classifier

This project focuses on using the K-Nearest Neighbors (KNN) algorithm to classify eye images into multiple diagnostic categories. Developed for a real-world hospital scenario, the model aims to support resource allocation for patients based on automated image-based diagnostics. This is a data science project designed to demonstrate applied machine learning in a healthcare context.

---

## 🔍 Methodology

1. **Data Preprocessing**  
   - Load and preprocess labeled eye images.
   - Normalize pixel values and flatten images.

2. **Model Implementation**  
   - Apply **K-Nearest Neighbors (KNN)** classifier.
   - Optimize value of **K** using cross-validation.

3. **Evaluation Metrics**  
   - **Confusion Matrix** for 3 labels:
     - *normal*
     - *dragged disc*
     - *normal with laser spot*
   - **Accuracy Score** of the model.
   - **Observational Summary** discussing model performance and challenges.

---

## 📈 Results

- **Model Accuracy**: *99.99%*
- **Key Observation**: *(Example)*
  - The model performs best with K = 3.
  - Classification of "dragged disc" was less accurate due to fewer training samples.

---

## 💡 Technologies Used

- Python 3
- Jupyter Notebook
- NumPy, Pandas, Matplotlib, Scikit-learn
- KNN Classifier from `sklearn.neighbors`
- Confusion Matrix and Accuracy from `sklearn.metrics`

---

## 📌 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Binod-Chhantyal/KNN-Eye-Disease-Classifier-Healthcare-ML.git
