# 👥 PRODIGY_ML_02 – Customer Segmentation using K-Means Clustering

This project uses K-Means clustering to segment retail store customers based on their spending behavior. The goal is to enable personalized marketing and customer targeting.

---

## 📌 Project Description

Customer segmentation helps businesses understand different customer groups and tailor marketing strategies. This project applies unsupervised learning to identify customer clusters.

---

## 🛠 Tech Stack / Tools Used

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Dataset**: Mall Customer Segmentation Dataset (Kaggle)

---

## 🧠 Problem Statement

How can a business segment its customer base effectively to understand varying spending patterns and create targeted strategies?

---

## 🧪 Solution Approach

1. **Data Collection**: Loaded Mall Customer data from Kaggle.
2. **Data Preprocessing**:
   - Removed null values
   - Scaled numerical features
3. **Model Building**:
   - Applied K-Means clustering
   - Used Elbow Method to find the optimal number of clusters
4. **Evaluation & Visualization**:
   - Used cluster plots to visualize customer groups
   - Analyzed behavior per segment

---

## 💻 Installation & Setup

```bash
git clone https://github.com/yourusername/customer-segmentation.git
cd customer-segmentation
pip install -r requirements.txt
jupyter notebook
