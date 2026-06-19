# 🎓 Student Academic Performance Prediction

Copyright © 2026 Nico Haikal Hafier

---

Sebuah aplikasi web interaktif yang dibangun menggunakan Streamlit untuk memprediksi performa akademik mahasiswa berdasarkan berbagai faktor pendidikan dan perilaku belajar. Aplikasi ini memanfaatkan algoritma Machine Learning Random Forest untuk mengklasifikasikan mahasiswa ke dalam kategori **Good Performance** atau **Poor Performance**.

---

## 🖥️ Tampilan Aplikasi

### Halaman Input Data
<img width="1912" height="831" alt="image" src="https://github.com/user-attachments/assets/3e7d4a08-eabb-4691-ac5d-52f4fb98b276" />



### Hasil Prediksi
<img width="1866" height="782" alt="image" src="https://github.com/user-attachments/assets/9eaad7c7-098e-4920-be88-9ebcdd9245f8" />



---

## 📖 Deskripsi Proyek

Proyek ini bertujuan untuk membantu mengidentifikasi performa akademik mahasiswa berdasarkan faktor-faktor yang mempengaruhi proses belajar, seperti jam belajar, tingkat kehadiran, motivasi belajar, nilai sebelumnya, dan faktor pendukung lainnya.

Dengan memanfaatkan Machine Learning, sistem dapat memberikan prediksi secara cepat sehingga dapat digunakan sebagai alat bantu dalam mengevaluasi potensi performa akademik mahasiswa.

---

## ✨ Fitur Utama

### 🎯 Prediksi Performa Akademik
Memprediksi apakah seorang mahasiswa termasuk dalam kategori:

- Good Performance
- Poor Performance

### 📊 Probabilitas Prediksi
Menampilkan tingkat keyakinan (confidence score) hasil prediksi.

### 📝 Input Data Interaktif
Pengguna dapat memasukkan data seperti:

- Hours Studied
- Attendance
- Sleep Hours
- Previous Scores
- Tutoring Sessions
- Motivation Level
- Internet Access
- Gender

### ⚡ Prediksi Real-Time
Hasil prediksi ditampilkan secara langsung setelah tombol prediksi ditekan.

### 🌐 Web-Based Interface
Aplikasi dapat diakses melalui browser menggunakan Streamlit.

---

## 🤖 Algoritma Machine Learning

Model yang digunakan pada proyek ini adalah:

### Random Forest Classifier

Alasan penggunaan:

- Akurasi tinggi pada dataset klasifikasi
- Mampu menangani data numerik dan kategorikal
- Mengurangi risiko overfitting
- Cocok untuk prediksi performa akademik mahasiswa

---

## 📂 Dataset

Dataset yang digunakan:

**Student Performance Factors Dataset**

Dataset berisi:

- 6.607 data mahasiswa
- 20 atribut
- Faktor akademik dan non-akademik

Target utama:

```text
Exam_Score
```

Kemudian dikonversi menjadi:

```text
Good Performance
Poor Performance
```

---

## 🛠️ Teknologi yang Digunakan

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-Learn
- Joblib
- Matplotlib
- Seaborn

---

## 📈 Tahapan Machine Learning

### 1. Data Collection

Menggunakan dataset Student Performance Factors.

### 2. Data Cleaning

Menangani missing value menggunakan:

- Mode untuk data kategorikal
- Median untuk data numerik

### 3. Data Preprocessing

- Label Encoding
- Standard Scaling

### 4. Model Training

Menggunakan:

- Decision Tree Classifier
- Random Forest Classifier

### 5. Model Evaluation

Menggunakan metrik:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 6. Deployment

Model disimpan menggunakan:

```python
model.pkl
scaler.pkl
```

Kemudian diintegrasikan ke aplikasi Streamlit.

---

## 🚀 Instalasi dan Menjalankan Proyek

### 1. Clone Repository

```bash
git clone https://github.com/Nico-Haikal/student-performance-prediction.git

cd student-performance-prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

atau

```bash
pip install streamlit pandas numpy scikit-learn joblib matplotlib seaborn
```

### 3. Jalankan Aplikasi

```bash
streamlit run app.py
```

atau

```bash
python -m streamlit run app.py
```

---

## 📁 Struktur Folder

```text
StudentPerformancePrediction/
│
├── StudentPerformanceFactors.csv
├── model.pkl
├── scaler.pkl
├── app.py
├── requirements.txt
└── README.md
```

---

## 👨‍💻 Author

**Nico Haikal Hafier**

Information Systems Student

Institut Teknologi PLN

AI Track Project – Laboratory Assistant Selection
