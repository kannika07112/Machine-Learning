# Diabetes Prediction using Machine Learning

## Table of Contents

* [Overview](#overview)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Usage](#usage)
* [File Structure](#file-structure)
* [Results](#results)
* [Contributing](#contributing)

---

## Overview

This repository contains a machine learning model designed to predict whether a person is diabetic or not based on medical input parameters. The model is built using **Support Vector Machine (SVM)** with a linear kernel and is trained on the publicly available **Diabetes Dataset** from the UCI Machine Learning Repository.

---

## Dataset

**Source**: [UCI Machine Learning Repository - Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

* **Rows**: 768 samples
* **Columns**: 8 numerical features + 1 target label

**Target Classes**:

* `0`: Non-diabetic
* `1`: Diabetic

Each sample includes features like glucose level, blood pressure, BMI, and other clinical data used to classify diabetic conditions.

---

## Technologies Used

This project leverages the following tools and libraries:

* **Python** – Programming language
* **Jupyter Notebook** – Interactive coding environment
* **NumPy** – For numerical computations
* **Pandas** – For data processing and manipulation
* **Scikit-learn** – For model building, preprocessing, and evaluation

---

## Usage

### How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/kannika07112/Machine_Learning
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Diabetes_Prediction
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**:

   ```bash
   jupyter notebook diabetes.ipynb
   ```

5. **Follow the notebook cells to explore, train, and test the model**.

---

## File Structure

```
.
├── diabetes.csv                  # Dataset for training/testing
├── Diabetes_Prediction.ipynb     # Jupyter Notebook with complete workflow
├── README.md                     # Documentation file
├── requirements.txt              # Python dependencies
```

---

## Results

| Dataset      | Accuracy                       |
| ------------ | ------------------------------ |
| Training Set | *(Add training accuracy here)* |
| Testing Set  | *(Add testing accuracy here)*  |

The model shows reliable accuracy in predicting diabetic conditions based on the clinical inputs.

---

## Contributing

If you'd like to contribute to this project:

1. **Fork** the repository
2. **Create** a new branch for your feature or bug fix
3. **Submit** a pull request with clear explanation

For significant changes, please open an issue first to discuss the proposal.

---
