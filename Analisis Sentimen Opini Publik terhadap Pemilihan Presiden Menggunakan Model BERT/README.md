# Sentiment Analysis Using BERT

Proyek ini bertujuan untuk menganalisis sentimen teks menggunakan model pembelajaran mesin berbasis Transformer, yaitu **BERT (Bidirectional Encoder Representations from Transformers)**. Dengan dataset yang tersedia, model ini dilatih untuk mengklasifikasikan teks ke dalam kategori sentimen seperti positif, negatif, dan netral.

## Deskripsi Proyek

Proyek ini mencakup:
1. **Pemrosesan Data**: Membaca dataset, eksplorasi data, dan pembersihan teks.
2. **Pra-Pemrosesan Teks**: Melakukan stemming, tokenisasi, dan penghapusan stopwords.
3. **Pelatihan Model**: Menggunakan model BERT untuk klasifikasi sentimen.
4. **Evaluasi Model**: Menggunakan metrik seperti classification report dan confusion matrix.
5. **Visualisasi Hasil**: Membuat visualisasi untuk interpretasi performa model.

## Struktur Proyek

- **Notebook Jupyter**: File utama yang mencakup semua langkah proyek.
- **Dataset**: Dataset teks dengan label sentimen yang digunakan untuk melatih dan menguji model.
- **Hasil Evaluasi**: Grafik dan laporan evaluasi model.

## Langkah-Langkah Utama

1. **Impor Library**
   Notebook menggunakan pustaka Python berikut:
   - `pandas` dan `numpy` untuk manipulasi data.
   - `matplotlib` dan `seaborn` untuk visualisasi.
   - `nltk` dan `Sastrawi` untuk pemrosesan teks.
   - `torch` dan `transformers` untuk pelatihan model berbasis BERT.

2. **Pemrosesan Data**
   - Membaca dataset menggunakan `pandas`.
   - Melakukan eksplorasi data untuk memahami distribusi label dan struktur teks.

3. **Pra-Pemrosesan Teks**
   - Menghapus emoji, simbol, dan karakter khusus dari teks.
   - Melakukan stemming menggunakan Sastrawi.
   - Menghapus stopwords untuk membersihkan data.

4. **Pelatihan Model**
   - Menggunakan tokenizer BERT untuk mengubah teks menjadi token yang dapat diproses oleh model.
   - Membagi dataset menjadi training dan testing set.
   - Melatih model BERT dengan optimizer AdamW.

5. **Evaluasi Model**
   - Menggunakan confusion matrix untuk memvisualisasikan hasil klasifikasi.
   - Menampilkan classification report untuk precision, recall, dan F1-score.

6. **Visualisasi Hasil**
   - Membuat grafik seperti heatmap untuk memahami performa model lebih baik.
