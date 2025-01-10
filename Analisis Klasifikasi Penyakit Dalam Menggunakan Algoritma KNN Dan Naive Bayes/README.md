# Analisis Klasifikasi Penyakit Dalam Menggunakan Algoritma KNN dan Naive Bayes

Proyek ini bertujuan untuk menganalisis dan mengklasifikasikan jenis penyakit menggunakan algoritma **K-Nearest Neighbors (KNN)** dan **Naive Bayes**. Notebook ini mencakup langkah-langkah pemrosesan data, pelatihan model, dan evaluasi performa model.

## Deskripsi Proyek

Proyek ini dirancang untuk:
- Mengolah dataset penyakit dan mempersiapkannya untuk analisis.
- Membangun model klasifikasi menggunakan algoritma KNN dan Naive Bayes.
- Membandingkan performa kedua model berdasarkan akurasi, presisi, dan metrik evaluasi lainnya.
- Membuat visualisasi untuk mempermudah interpretasi hasil.

## Struktur Proyek

- **Notebook Jupyter**: Implementasi langkah-langkah proyek dalam file `.ipynb`.
- **Dataset**: Dataset yang diunggah ke notebook untuk analisis.
- **Hasil Evaluasi**: Grafik dan metrik yang menunjukkan performa model.

## Langkah-Langkah Utama

1. **Impor Library**  
   Notebook menggunakan pustaka Python berikut:  
   - `pandas` untuk manipulasi data.
   - `numpy` untuk operasi numerik.
   - `matplotlib` dan `seaborn` untuk visualisasi.
   - `scikit-learn` untuk membangun dan mengevaluasi model klasifikasi.

2. **Pengunggahan Dataset**  
   Dataset diunggah langsung melalui notebook, diikuti oleh eksplorasi data awal (EDA).

3. **Pra-pemrosesan Data**  
   - Menangani nilai kosong atau tidak valid.
   - Normalisasi data jika diperlukan.
   - Pembagian dataset menjadi data latih dan uji.

4. **Implementasi Algoritma**  
   - **KNN**: Klasifikasi berbasis jarak dengan parameter jumlah tetangga terdekat (k).  
   - **Naive Bayes**: Klasifikasi probabilistik berbasis teorema Bayes.

5. **Evaluasi Model**  
   - Metrik evaluasi seperti akurasi, presisi, recall, dan F1-score.  
   - Matriks kebingungan untuk analisis performa detail.

6. **Visualisasi Hasil**  
   - Grafik performa model.
   - Perbandingan hasil prediksi.
