# Analisis Perbandingan Naïve Bayes, SVM, Bi-LSTM untuk Klasifikasi Kesehatan Mental pada Platform Instagram

## 📌 Deskripsi
Repositori ini berisi hasil penelitian tugas akhir yang bertujuan untuk menganalisis dan membandingkan performa tiga algoritma machine learning, yaitu **Naïve Bayes**, **Support Vector Machine (SVM)**, dan **Bidirectional Long Short-Term Memory (Bi-LSTM)**, dalam melakukan **klasifikasi sentimen terkait kesehatan mental** pada data dari **platform Instagram**.

Dataset yang digunakan adalah *Mpox Instagram Dataset: Sentiment & Hate Analysis* yang berisi 60.128 unggahan pengguna yang telah dilabeli sentimen dan indikasi stres/kecemasan.

## 🧠 Metodologi
Penelitian dilakukan melalui tahapan:
- **Data Collection**
- **Preprocessing**
  - Remove Columns, Re-Tweet, New Line
  - Balancing data menggunakan SMOTE
- **Text Processing**
  - Case Folding, Stopword Removal, Stemming, Tokenization, dll
- **Sentence Embedding**
  - Menggunakan Word2Vec
- **Model Training**
  - Naïve Bayes
  - Support Vector Machine (SVM)
  - Bidirectional LSTM (Bi-LSTM)
- **Model Evaluation**
  - Akurasi, Precision, Recall, F1-Score

## 📊 Hasil Evaluasi
| Model       | Accuracy (Before/After SMOTE) | F1-Score (Before/After SMOTE) |
|-------------|-------------------------------|-------------------------------|
| Naïve Bayes | 0.81 / 0.81                   | 0.73 / 0.71                   |
| SVM         |  0.87  / 0.88                 | 0.88 / 0.73                   |
| **Bi-LSTM** | **83.82% / 86.16%**           | **0.8117 / 0.8568**           |

Bi-LSTM menunjukkan performa terbaik setelah dilakukan balancing data.


## 🧪 Dependencies
- Python 

## 👨‍💻 Tim Peneliti
- Dhino Rayvaldo Turnip (12S21001)
- Bobby Willy Siagian (12S21010)
- Glory Natasya Hutahaean (12S21060)

## 📃 Lisensi
Repositori ini hanya untuk tujuan akademik.

---

> *Institut Teknologi Del — Program Studi Sarjana Sistem Informasi, 2025*
```
