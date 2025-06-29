# Height-Weight Cluster Predictor 🚀

This project demonstrates how to use K-Means clustering to classify individuals based on their height and weight. The application includes an interactive Streamlit web interface for user input and cluster prediction, along with visualizations to understand the clustering behavior.

---

## 📌 Overview

The model clusters individuals into groups using unsupervised learning, helping to identify natural groupings based on physical attributes. This can be useful for visualizing population patterns, understanding body type distributions, and exploring real-world data with machine learning.

---

## 🧾 Contents

* `hwprediction.ipynb` – Notebook with complete code for preprocessing, clustering using KMeans, Streamlit interface, and data visualization.
* `HW.csv` – Dataset file containing height and weight information used for training.


---

## 🧠 Technologies Used

* **Python**
* **Pandas** – Data manipulation
* **Matplotlib** – Data visualization
* **scikit-learn** – Machine Learning (KMeans Clustering)
* **Streamlit** – Web interface for model interaction

---

## 💡 Features

✅ Cluster prediction using KMeans
✅ Upload and visualize dataset
✅ Interactive Streamlit UI for real-time predictions
✅ Cluster visualization using scatter plots
✅ Simple, user-friendly design

---

## 🖥️ How to Run the Project

### 📌 Option 1: Jupyter Notebook (Offline)

1. Install the required libraries:

   ```bash
   pip install pandas matplotlib scikit-learn
   ```

2. Open `hwprediction.ipynb` in Jupyter Notebook or Google Colab.

3. Run each cell to:

   * Load the dataset
   * Train the KMeans model
   * Visualize clusters

### 📌 Option 2: Run the Streamlit App (Interactive)

1. Install Streamlit:

   ```bash
   pip install streamlit
   ```

2. Save the relevant code from the notebook into a Python file (e.g., `app.py`).

3. Run the app:

   ```bash
   streamlit run app.py
   ```

4. Use the web interface to input height and weight, and get real-time cluster predictions and visualizations.

---

## 📂 Dataset Description

The dataset `HW.csv` includes the following columns:

| Column | Description               |
| ------ | ------------------------- |
| Height | Height of person (inches) |
| Weight | Weight of person (pounds) |

---
<img width="665" alt="image" src="https://github.com/user-attachments/assets/49297487-fbb8-4576-b9e0-0a504575cb1c" />
