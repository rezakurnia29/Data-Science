# Analisis Faktor-Faktor Yang mempengaruhi churn nasabah bank

**Deskripsi**: Deskripsi: Pengujian algoritma random forest untuk menganalisis faktor-faktor yang
mempengaruhi churn nasabah bank. Tujuan dari proyek ini adalah Mengidentifikasi faktor-faktor yang mempengaruhi churn nasabah bank di industri perbankan dan Mengimplementasikan algoritma Random Forest untuk menganalisis dan memprediksi churn nasabah bank

**Tools**: Python, Google Colab, Scikit-learn, numpy, random forest

**File Proyek**: `ChurnNasabahBank.ipynb

**Fitur Proyek**

- **Pengumpulan Data**: Mencari dataset churn nasabah di situs web kaggle
- **Data Preprocessing**: Memeriksa tipe data, missing value, menghapus kolom yang tidak diingkan
- **Visualisasi**: Membuat visualisasi setiap fitur untuk melihat setiap pola atau tren yang terjadi.
- **Implementasi Random Forest**: Menggunakan algoritma Random Forest untuk memberikan satu suara ke kelas yang
diprediksi. Kelas dengan jumlah suara terbanyak dipilih sebagai prediksi akhir.
- **Evaluasi Model**: Evaluasi model menggunakan confusion matrix dengan data testing yang digunakan berjumlah 2000 data.`

**Hasil Utama**:
  - **Akurasi model**: 85%
  - **Penjelasan**: Model ini memiliki akurasi sebesar 85%, yang berarti 85% dari semua prediksi
yang dibuat oleh model adalah benar. Ini menunjukkan bahwa model cukup baik
dalam mengklasifikasikan data secara keseluruhan. variabel yang paling penting selain complain adalah variabel Age. 
   

 ## Cara Menjalankan Proyek
1. Clone repositori ini: `git clone https://github.com/rezakurnia29/Data-Science/Customer_Churn_Analysis.git`
2. Buka salah satu file `.ipynb` di Jupyter Notebook atau Google Colab.
3. Jalankan cell untuk melihat hasil analisis.
