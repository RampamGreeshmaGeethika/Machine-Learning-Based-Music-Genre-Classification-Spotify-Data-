# Machine-Learning-Based-Music-Genre-Classification-Spotify-Data-
A machine learning project that classifies music tracks into genres using audio features from Spotify data. The system analyzes musical attributes such as tempo, energy, danceability, and acousticness to predict the genre of a song using various machine learning algorithms.

Here is a **professional README.md** you can use for your **Machine Learning-Based Music Genre Classification on Spotify Data** project. You can paste this directly into your GitHub repository.

---

# 🎵 Machine Learning-Based Music Genre Classification (Spotify Data)

A machine learning project that classifies music tracks into genres using audio features from Spotify data. The system analyzes musical attributes such as tempo, energy, danceability, and acousticness to predict the genre of a song using various machine learning algorithms.

---

# 📌 Project Overview

With the rapid growth of music streaming platforms such as Spotify, automatically classifying songs by genre is essential for improving recommendation systems and user experience.

This project develops a **machine learning-based genre classification system** that predicts the genre of music tracks based on their audio characteristics. Multiple algorithms were tested to identify the best-performing model.

The final model achieved **88% classification accuracy** and was deployed using **Flask** to provide real-time genre predictions through a web interface.

---

# 🚀 Features

* Automated music genre classification
* Data preprocessing and feature engineering
* Exploratory Data Analysis (EDA)
* Model training with multiple machine learning algorithms
* Hyperparameter tuning for improved performance
* Handling imbalanced data using **SMOTE**
* Deployment using **Flask web application**
* Visualization of model results

---

# 📊 Dataset

The dataset contains Spotify track features with **22 attributes** including:

* danceability
* energy
* tempo
* loudness
* speechiness
* acousticness
* liveness
* instrumentalness
* valence
* genre (target variable)

The dataset was used to train and evaluate machine learning models for genre prediction.

---

# ⚙️ Machine Learning Models Used

The following algorithms were implemented and compared:

* Support Vector Machine (SVM)
* Random Forest
* XGBoost
* Bagging Classifier

After model comparison and hyperparameter tuning, **Random Forest achieved the best performance with 88% accuracy.**

---

# 🔬 Methodology

### 1️⃣ Data Preprocessing

* Removed unnecessary attributes
* Handled missing values
* Encoded categorical variables
* Feature scaling using StandardScaler

### 2️⃣ Exploratory Data Analysis

* Distribution plots
* Correlation matrix analysis
* Feature relationship visualization

### 3️⃣ Handling Imbalanced Data

* Applied **SMOTE (Synthetic Minority Oversampling Technique)**

### 4️⃣ Model Training

* Split dataset into **80% training and 20% testing**
* Trained multiple classification models
* Applied hyperparameter tuning using **GridSearchCV**

### 5️⃣ Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix
* Classification Report

---

# 🛠 Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* Seaborn
* Matplotlib
* TensorFlow / Keras
* XGBoost
* Imbalanced-learn (SMOTE)

### Tools

* Jupyter Notebook
* Anaconda
* Flask
* Git & GitHub

---

# 📈 Results

The comparison of machine learning algorithms showed that:

| Model             | Performance                         |
| ----------------- | ----------------------------------- |
| SVM               | Moderate Accuracy                   |
| XGBoost           | Good Performance                    |
| Bagging           | Stable Results                      |
| **Random Forest** | **Best Performance (88% Accuracy)** |

Random Forest was selected as the final model for deployment.

---

# 🌐 Deployment

The trained model was deployed using **Flask**, allowing users to:

1. Input audio feature values
2. Predict the genre of the song
3. Display prediction results on a web interface

---

# 📂 Project Structure

```
Music-Genre-Classification
│
├── dataset/
│   └── spotify_dataset.csv
│
├── notebooks/
│   └── model_training.ipynb
│
├── model/
│   └── model.pkl
│
├── app.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/music-genre-classification.git
cd music-genre-classification
```

---

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Run the Flask Application

```bash
python app.py
```

---

### 4️⃣ Open in Browser

```
http://localhost:5000
``

# 📌 Applications

* Music recommendation systems
* Playlist generation
* Music library organization
* Audio analysis and trend detection
* Music streaming personalization


