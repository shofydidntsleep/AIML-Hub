# Mobile Price Classification

Proyek ini bertujuan untuk mengklasifikasikan harga ponsel ke dalam beberapa kategori berdasarkan fitur-fiturnya menggunakan berbagai algoritma pembelajaran mesin. Notebook ini mencakup proses pemrosesan data, eksplorasi data, pelatihan model, evaluasi model, dan visualisasi hasil.

## Deskripsi Proyek

Proyek ini mencakup:
1. **Pemrosesan Data**: Membaca dataset, eksplorasi data, dan pembersihan data.
2. **Eksplorasi Data**: Menganalisis dan memahami pola dalam dataset.
3. **Pelatihan Model**: Menggunakan algoritma seperti Random Forest untuk klasifikasi.
4. **Evaluasi Model**: Menggunakan metrik seperti confusion matrix dan classification report.
5. **Visualisasi Hasil**: Membuat grafik untuk interpretasi yang lebih baik.

## Struktur Proyek

- **Notebook Jupyter**: File utama berisi implementasi proyek.
- **Dataset**: Dataset harga ponsel yang digunakan untuk melatih dan menguji model.
- **Hasil Evaluasi**: Grafik dan laporan evaluasi model.

## Langkah-Langkah Utama

1. **Impor Library**  
   Notebook menggunakan pustaka Python berikut:
   - `pandas` untuk manipulasi data.
   - `numpy` untuk operasi numerik.
   - `matplotlib` dan `seaborn` untuk visualisasi data.
   - `sklearn` untuk pelatihan dan evaluasi model.

2. **Pemrosesan Data**  
   - Membaca dataset menggunakan `pandas`.
   - Memeriksa missing values dan membersihkan data jika diperlukan.

3. **Eksplorasi Data**  
   - Menggunakan visualisasi seperti heatmap untuk melihat korelasi antar fitur.
   - Memahami distribusi data untuk masing-masing kategori harga.

4. **Pelatihan Model**  
   - Menggunakan algoritma seperti Random Forest untuk klasifikasi.
   - Membagi dataset menjadi training dan testing set.

5. **Evaluasi Model**  
   - Menggunakan confusion matrix untuk mengevaluasi performa model.
   - Menampilkan classification report untuk metrik seperti precision, recall, dan F1-score.

6. **Visualisasi Hasil**  
   - Membuat visualisasi seperti confusion matrix heatmap untuk interpretasi hasil.
