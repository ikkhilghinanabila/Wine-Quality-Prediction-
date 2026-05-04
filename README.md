# Wine Quality Prediction 🍷

## 📌 Deskripsi

Proyek ini bertujuan untuk membangun model machine learning dalam memprediksi kualitas anggur berdasarkan karakteristik kimia yang dimiliki. Dataset yang digunakan berisi berbagai variabel seperti alcohol, acidity, pH, dan kandungan kimia lainnya yang berpengaruh terhadap kualitas anggur.

## 📊 Dataset

Dataset terdiri dari:

* Data training (dengan label quality)
* Data testing (tanpa label)

Variabel target yang diprediksi adalah **quality**, dengan skala nilai tertentu yang menunjukkan tingkat kualitas anggur.

## ⚙️ Metodologi

Tahapan analisis yang dilakukan meliputi:

1. Data Loading & Data Understanding
2. Exploratory Data Analysis (EDA)
3. Data Cleaning
4. Feature Selection & Splitting Data
5. Feature Scaling
6. Model Building:

   * Logistic Regression
   * Random Forest
7. Model Evaluation
8. Prediction pada data testing

## 🏆 Hasil

Berdasarkan hasil evaluasi, model terbaik adalah:

**Logistic Regression**
dengan akurasi sebesar **59.88%**

## 📈 Insight

* Variabel seperti alcohol, sulphates, dan volatile acidity memiliki pengaruh cukup besar terhadap kualitas anggur
* Model cenderung memprediksi kelas mayoritas seperti kualitas 5 dan 6
* Model sederhana dapat memberikan performa yang kompetitif dibandingkan model kompleks

## 📁 Output

Hasil prediksi disimpan dalam file:
`hasilprediksi_3digitNIMterakhir.csv`

## 👩‍💻 Author

Nama: (Ikkhil Ghina Nabila)
Prodi: Statistika dan Sains Data
Universitas Negeri Semarang
