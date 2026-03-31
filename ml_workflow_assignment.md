# ML Workflow Assignment

Prepared by: Manikandan M

---

## Task 1 — Identify Label and Data Leakage

### Label Column

The label column is **repeat_purchase_flag** because it represents the target variable that indicates whether a customer will make a repeat purchase within 30 days.

### Data Leakage Column

The column **discount_used_on_repeat_order** introduces data leakage because it contains information that is only available after the repeat purchase has already occurred, which will not be available at prediction time.

---

## Task 2 — Missing Steps in ML Workflow

### Step 1: Data Preprocessing and Cleaning

Before training the model, the dataset must be cleaned by handling missing values, removing duplicates, and ensuring data quality. This helps improve model accuracy and reliability.

### Step 2: Train-Test Split

The dataset should be split into training and testing sets so that the model can be evaluated on unseen data. Without this step, the model may overfit and not perform well in real-world scenarios.

---

## Conclusion

A proper machine learning workflow ensures that data is clean, reliable, and properly validated before training models. Skipping important steps can lead to inaccurate predictions and poor performance.

---
