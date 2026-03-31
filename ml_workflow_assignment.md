# ML Workflow Assignment

Prepared by: Manikandan M

---

## Task 1 — Identify Label and Data Leakage

### Label Column

The label column is **repeat_purchase_flag** because it represents the target variable we want to predict, indicating whether a customer makes a repeat purchase within 30 days.

### Data Leakage Column

The column **discount_used_on_repeat_order** introduces data leakage because it contains information that is only available after the repeat purchase has occurred, which would not be known at prediction time.

---

## Task 2 — Missing Steps in ML Workflow

### Step 1: Data Preprocessing and Cleaning

Before training a model, it is important to clean the dataset by handling missing values, removing duplicates, and ensuring data consistency. This step ensures that the model learns from accurate and reliable data.

### Step 2: Train-Test Split

The dataset should be split into training and testing sets to evaluate model performance on unseen data. Without this step, the model may overfit and give misleadingly high accuracy.

---

## Conclusion

A proper machine learning workflow involves careful data preparation and validation before model training. Skipping essential steps like preprocessing and train-test splitting can lead to inaccurate predictions and poor model generalization.

---
