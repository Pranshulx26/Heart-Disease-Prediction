<img src="heart_pic.png" alt="Heart Icon" style="display: block; margin: 0 auto;" />

# <span style="color: #FF6347;"><strong>Heart Disease Prediction Project</strong></span>

This project aims to build a robust machine learning model for predicting heart disease based on patient health metrics, demonstrating the potential of AI in transforming healthcare.

---

## <span style="color: #4682B4;"><strong>Objective</strong></span>
- Develop a predictive model with high accuracy, prioritizing **high recall** to minimize the risk of undetected heart disease.
- Perform detailed **Exploratory Data Analysis (EDA)** to uncover relationships and trends in the dataset.
- Implement and evaluate diverse classification algorithms such as:
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Optimize performance using **hyperparameter tuning** and robust preprocessing techniques.

---

## <span style="color: #4682B4;"><strong>Methodology</strong></span>

### 1. <span style="color: #6A5ACD;"><strong>Data Collection and Exploration</strong></span>
- Loaded the heart disease dataset.
- Conducted **Exploratory Data Analysis (EDA):**
  - **Univariate Analysis**: Used histograms and bar plots to understand feature distributions.
  - **Bivariate Analysis**: Leveraged scatter plots, bar plots, and KDE plots to explore feature-target relationships.

### 2. <span style="color: #6A5ACD;"><strong>Data Preprocessing</strong></span>
- Ensured **data quality** (handled missing values—none found in this dataset).
- Addressed outliers via **Box-Cox transformations** for improved distribution.
- Applied **one-hot encoding** for categorical variables.
- Split the dataset into **training** and **testing** subsets.

### 3. <span style="color: #6A5ACD;"><strong>Model Building and Evaluation</strong></span>
- Trained and evaluated multiple models:
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- Conducted **hyperparameter tuning** using cross-validation for optimal performance.
- Evaluated metrics: **Accuracy**, **Precision**, **Recall**, and **F1-score**, emphasizing **high recall** for early detection.

### 4. <span style="color: #6A5ACD;"><strong>Model Selection and Interpretation</strong></span>
- Selected the **SVM model** for its excellent recall performance, ensuring fewer missed diagnoses.
- Analyzed **feature importance** to identify key predictors, including:
  - Chest pain type
  - Exercise-induced angina
  - Number of major vessels colored by fluoroscopy
  - Thalium stress test result
  - Age
  - Maximum heart rate achieved

---

## <span style="color: #4682B4;"><strong>Results</strong></span>
- The **SVM model** achieved a high recall while maintaining a balance with precision.
- Key predictors provided valuable insights into heart disease risk factors.

---

## <span style="color: #4682B4;"><strong>Conclusion</strong></span>
This project successfully developed a reliable machine learning model for **heart disease prediction**, emphasizing the critical balance between precision and recall. The findings highlight the potential of AI to assist healthcare professionals in identifying at-risk individuals effectively.

---

## <span style="color: #4682B4;"><strong>Future Enhancements</strong></span>
- Incorporate advanced models such as **XGBoost** or **neural networks** for improved accuracy.
- Enrich the dataset with additional features like patient lifestyle and family history.
- Develop a **user-friendly interface** for seamless deployment.
- Collaborate with healthcare experts to refine the model’s clinical application.

---

