# Skripsi Machine Learning: Klasifikasi Tanaman dan Prediksi Hasil Panen

## Deskripsi

Repository ini berisi implementasi metode **Machine Learning** untuk analisis data pertanian yang terdiri dari dua bagian utama:

1. **Klasifikasi Tanaman**
   Mengklasifikasikan jenis tanaman berdasarkan fitur yang tersedia dalam dataset.

2. **Prediksi Hasil Panen (Regresi)**
   Memprediksi jumlah hasil panen menggunakan beberapa model regresi.

Penelitian ini merupakan bagian dari tugas akhir (skripsi) pada program studi **Teknik Elektro, Universitas Sebelas Maret**.

---

## Struktur Repository

```
skripsi_ml/
│
├── skripsi_klasifikasi.ipynb   # Notebook eksperimen klasifikasi
├── skripsi_regresi.ipynb       # Notebook eksperimen regresi
├── DATASET/                    # Dataset penelitian
└── README.md                   # Dokumentasi repository
```

---

## Dataset

Dataset yang digunakan dalam penelitian ini **bukan merupakan dataset yang dibuat oleh penulis**, melainkan diperoleh dari platform **Kaggle** dan digunakan untuk keperluan eksperimen model machine learning.

Sumber dataset:

Kaggle – [Crop Recommendation Dataset]
https://www.kaggle.com/atharvaingle/crop-recommendation-dataset

Kaggle – [Crop Yield Prediction Dataset]
https://www.kaggle.com/patelris/crop-yield-prediction-dataset

Seluruh hak kepemilikan dataset tetap berada pada pemilik dataset yang mengunggahnya di Kaggle.

---

## Metode Machine Learning

### Model Klasifikasi

Beberapa algoritma yang digunakan dalam proses klasifikasi:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* XGBoost

### Model Regresi

Model yang digunakan untuk memprediksi hasil panen:

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor

---

## Tahapan Analisis Data

1. **Data Preprocessing**

   * Pembersihan data
   * Penanganan missing value
   * Normalisasi atau scaling data

2. **Exploratory Data Analysis (EDA)**

   * Visualisasi distribusi data
   * Analisis korelasi antar fitur

3. **Pelatihan Model**

   * Training model klasifikasi
   * Training model regresi

4. **Evaluasi Model**

   **Klasifikasi**

   * Accuracy
   * Confusion Matrix

   **Regresi**

   * Mean Absolute Error (MAE)
   * Mean Squared Error (MSE)
   * R² Score

---

## Tools dan Library

Proyek ini menggunakan beberapa library Python:

* Python
* NumPy
* Pandas
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Cara Menjalankan Proyek

1. Clone repository ini

```
git clone https://github.com/abimputra04/skripsi_ml_klasifikasi.git
```

2. Masuk ke folder repository

```
cd skripsi_ml_klasifikasi
```

3. Jalankan Jupyter Notebook

```
jupyter notebook
```

4. Buka notebook:

* `skripsi_klasifikasi.ipynb`
* `skripsi_regresi.ipynb`

---

## Tujuan Penelitian

Penelitian ini bertujuan untuk:

* Membandingkan performa beberapa algoritma machine learning pada tugas klasifikasi tanaman.
* Menganalisis kemampuan model regresi dalam memprediksi hasil panen.
* Menentukan model yang memiliki performa terbaik berdasarkan metrik evaluasi yang digunakan.

---

## Penulis

**Abimanyu Putra**
Mahasiswa Teknik Elektro
Universitas Sebelas Maret
