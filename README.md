# 🧠 Sentiment Analysis on YouTube Comments (GTA V Trailer)

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis sentimen komentar pengguna pada video YouTube trailer game GTA V.

Dengan menggunakan teknik Natural Language Processing (NLP), komentar diklasifikasikan ke dalam kategori:

* Positif 😊
* Negatif 😡
* Netral 😐

Proyek ini menunjukkan bagaimana data dari media sosial dapat digunakan untuk memahami opini publik terhadap suatu konten populer.

---

## 📊 Dataset

Dataset diambil dari komentar pengguna pada video YouTube:

* Video: GTA V Trailer
* Sumber: YouTube Comments
* Bahasa: Campuran (Indonesia & Inggris)

---

## ⚙️ Tahapan Proyek

### 1. Data Collection

* Scraping komentar dari YouTube

### 2. Data Preprocessing

* Case folding
* Tokenization
* Stopword removal
* Stemming

---

## 🧠 Feature Engineering

* TF-IDF Vectorization

---

## 🤖 Model Machine Learning

Model yang digunakan:

* [Isi model kamu, misal: Logistic Regression / Naive Bayes]

---

## 📈 Evaluasi Model

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📊 Hasil Model

* Akurasi: **Akurasi SVM: 94.51%**
           **Akurasi Random Forest: 91.44%**
           **Akurasi Deep Learning: 92.60%**

Kesimpulan:
Model mampu mengklasifikasikan sentimen komentar pengguna dengan cukup baik, sehingga dapat digunakan untuk menganalisis opini publik terhadap konten video.

---

## 🛠️ Teknologi yang Digunakan

* Python
* Pandas
* Scikit-learn
* NLTK / Sastrawi
* YouTube API (jika digunakan)

---

## 🚀 Cara Menjalankan

1. Clone repository:

```bash id="6jdg07"
git clone https://github.com/username/sentiment-analysis-indonesia.git
```

2. Install dependencies:

```bash id="xnybhq"
pip install -r requirements.txt
```

3. Jalankan notebook:

* Buka `.ipynb` di Jupyter Notebook / Google Colab

---

## 📁 Struktur Project

sentiment-analysis/
│
├── data/
├── model/
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## 👤 Author

**Mulya Adi Putra**
Informatics Student – Artificial Intelligence

---

## 🌟 Insight

Analisis ini menunjukkan bahwa komentar pengguna pada video populer dapat memberikan gambaran umum terhadap persepsi publik, yang berguna untuk strategi pemasaran dan evaluasi konten digital.

---
