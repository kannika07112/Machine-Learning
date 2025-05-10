# Spam Mail Detection using Logistic Regression

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

This project demonstrates how to build a machine learning model to classify emails as either **spam** or **ham (not spam)** using **Logistic Regression**. The model is trained on a dataset of labeled email messages and uses **TF-IDF vectorization** for feature extraction.

---

## Dataset

**Source:** `mail_data.csv` (contains labeled email messages)

* **Columns:**

  * `Category`: Label (spam or ham)
  * `Message`: The email content
* **Classes:**

  * `spam`: Unwanted or junk emails
  * `ham`: Normal or legitimate emails
* Null values are replaced with empty strings before preprocessing.

---

## Technologies Used

This project uses the following tools and libraries:

* **Python** – Programming language
* **Pandas** – Data handling
* **NumPy** – Numerical operations
* **Scikit-learn** – Machine learning model building
* **TF-IDF Vectorizer** – Text vectorization for NLP
* **Logistic Regression** – Binary classification algorithm

---

## Usage

### How to Run:

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/spam-mail-detector.git
   ```

2. **Navigate to the project directory**

   ```bash
   cd spam-mail-detector
   ```

3. **Install required packages**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the notebook or script**

   ```bash
   jupyter notebook Spam_Detector.ipynb
   ```

---

## File Structure

```
.
├── mail_data.csv            # Dataset with spam and ham labels
├── Spam_Detector.ipynb      # Jupyter Notebook containing the full ML workflow
├── requirements.txt         # List of dependencies
├── README.md                # Project documentation
```

---

## Results

| Dataset      | Accuracy      |
| ------------ | ------------- |
| Training Set | *e.g., 96.5%* |
| Testing Set  | *e.g., 94.2%* |

* The model performs well on both training and unseen test data.
* New email inputs can be classified accurately as **Spam** or **Ham**.

---

## Contributing

Interested in improving this project?

1. Fork the repository
2. Create a new branch: `git checkout -b feature-branch`
3. Commit your changes
4. Push to the branch: `git push origin feature-branch`
5. Open a pull request

For significant changes, feel free to open an issue first to discuss what you’d like to modify.

---
