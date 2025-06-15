# Movie-Review-Analyzer 🎬

Sebuah model Machine Learning untuk menganalisis dan mengklasifikasikan sentimen ulasan film secara otomatis, dilengkapi dengan **demo interaktif** untuk pengujian *real-time*.

---

## 🚀 Demo Interaktif

Model ini tidak hanya ada di dalam kode, tapi dapat dicoba secara langsung! Berikut adalah tampilan antarmuka demo saat aplikasi dijalankan melalui notebook.

![Demo Aplikasi Movie Review Analyzer]([httpsd://github.com/user-attachments/assets/523c9e6d-07f2-4683-943e-b5cd901d498c](https://github.com/nfldffa/Movie-Review-Analyzer/blob/main/demo-movie.png?raw=true))




---

## 🎯 Tantangan & Tujuan Proyek

Di era digital, data teks seperti ulasan, komentar, dan tweet melimpah ruah. Tantangannya adalah bagaimana mesin dapat memahami makna subjektif di balik teks tersebut.

Tujuan proyek ini adalah:
1.  Membangun model klasifikasi teks yang akurat menggunakan teknik NLP.
2.  Mendemonstrasikan proses end-to-end proyek Machine Learning, dari pembersihan data hingga deployment model sederhana.
3.  Menciptakan sebuah alat interaktif yang dapat digunakan untuk menguji performa model secara langsung.

## ✨ Kemampuan yang Ditunjukkan

Proyek ini mendemonstrasikan keahlian dalam:
- **Klasifikasi Teks (NLP):** Menerapkan algoritma untuk memahami dan mengkategorikan teks tidak terstruktur.
- **Preprocessing Data Teks:** Membersihkan dan mempersiapkan data teks mentah (HTML tags, stopwords, tanda baca) untuk pemodelan.
- **Feature Engineering:** Menggunakan teknik TF-IDF untuk mengubah teks menjadi fitur numerik yang dapat dipahami mesin.
- **Evaluasi Model:** Mengukur kinerja model secara kuantitatif menggunakan metrik seperti Akurasi dan F1-Score.
- **Pembuatan Prototipe Cepat:** Membangun antarmuka pengguna (UI) yang fungsional dengan Gradio untuk memamerkan hasil model.

## 🛠️ Tech Stack & Library

| Teknologi | Kegunaan |
| :--- | :--- |
| **Python** | Bahasa utama |
| **Pandas** | Manipulasi & pembersihan data |
| **NLTK** | Preprocessing teks & stopwords |
| **Scikit-learn** | Feature engineering (TF-IDF) & pemodelan (Logistic Regression) |
| **Gradio** | Pembuatan demo UI interaktif |
| **Matplotlib & Seaborn**| Visualisasi data (EDA) |
| **Google Colab** | Lingkungan development berbasis cloud |

## 📈 Hasil & Performa Model

Setelah melalui proses training dan validasi, model ini berhasil mencapai **akurasi sebesar 87.38%** pada data uji. Ini menunjukkan bahwa model memiliki kemampuan yang solid untuk membedakan antara ulasan positif dan negatif.

<details>
<summary>Klik untuk melihat Laporan Klasifikasi Detail</summary>

```
Laporan Klasifikasi:
              precision    recall  f1-score   support

    Negative       0.88      0.87      0.87      4961
    Positive       0.87      0.88      0.88      5039

    accuracy                           0.87     10000
   macro avg       0.87      0.87      0.87     10000
weighted avg       0.87      0.87      0.87     10000
```
