# Patient-Hospital-Stay-Prediction

This project predicts hospital stay durations based on patient data, using a Linear Regression model. The model analyzes patient age, severity level of the condition, and the number of previous admissions to make predictions.

---

## Features Used in the Model

1. **Age**: Patient's age.
2. **Severity**:
   - Minor
   - Medium
   - Critical
3. **Previous Admissions**: Number of prior hospitalizations.

---

## Steps Involved

### 1. Data Generation
- Data was generated to simulate real-world hospital data.
- `Days Stayed` was influenced by:
  - **Age**: Older patients tend to stay longer.
  - **Severity**: Higher severity leads to longer stays.
  - **Previous Admissions**: Patients with more prior admissions tend to stay longer.

### 2. Data Preprocessing
- Changing the missing values for days_stayed and age with the mean.
- One-hot encoding was applied to the Severity feature.
- The data was split into training and testing sets to evaluate model performance.

### 3. Model Training
- A Linear Regression model was trained to predict `Days Stayed`.

### 4. Model Evaluation
- The model was evaluated using:
  - **Mean Squared Error (MSE)**: Measures average prediction error.
  - **R-squared (R²)**: Explains variance captured by the model.

### 5. Visualizations
- Scatter plots were used to compare **actual vs. predicted values**.
- Box plots and bar charts illustrated the relationship between severity and hospital stays.
---
