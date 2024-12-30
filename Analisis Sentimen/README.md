# Analisis Sentimen Ulasan PUBG Mobile

**Deskripsi**: Deskripsi: Menganalisis sentimen dari ulasan pengguna PUBG Mobile di Google Play Store menggunakan algoritma Naive Bayes. Analisis ini mencakup visualisasi data, pembersihan teks, dan evaluasi model untuk mengklasifikasikan sentimen menjadi positif, negatif, atau netral. Proyek ini bertujuan untuk menganalisis sentimen ulasan game PUBG Mobile yang diambil dari Google Play Store menggunakan Naive Bayes sebagai algoritma utama. Data yang digunakan telah diproses dan diolah untuk menghasilkan insight sentimen dari pengguna.

**Tools**: Python, Google Colab, Scikit-learn, WordCloud, NLTK.

**File Proyek**: `Analisis_Sentimen_PUBG_Mobile.ipynb`

**Fitur Proyek**
Pengumpulan Data: Menggunakan library google-play-scraper untuk mengambil 1.000 ulasan dari PUBG Mobile di Google Play Store.
Pembersihan Data: Menghapus stopwords, karakter khusus, dan kata-kata tidak relevan untuk meningkatkan kualitas analisis.
Visualisasi: Membuat Word Cloud dan diagram batang distribusi sentimen.
Klasifikasi Sentimen: Menggunakan algoritma Naive Bayes untuk memprediksi sentimen (positif, negatif, netral).
TF-IDF: Mengolah teks menggunakan metode TF-IDF untuk menghasilkan fitur yang relevan.

**Hasil Utama**:
  - **Akurasi model**: 55%
  - **Distribusi Sentimen** :
  -   **Negatif**: 520 Ulasan
  -   **Positif**: 347 Ulasana
  -   **Neutral**: 133 Ulasan
    
 **Hasil terpenting dalam sentiment**: game, main, update, bug
