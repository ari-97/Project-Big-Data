# Proyeksi UMK Jawa Barat 2027 Berbasis Integrasi Big Data dan Analisis Sentimen YouTube

**Disusun Oleh:**
* Ari Arianto (NIM: 312310141)
* Muhamad Endang Zakaria (NIM: 312310140)

## Deskripsi Proyek
Proyek ini dikembangkan untuk memproyeksikan Upah Minimum Kabupaten/Kota (UMK) di Provinsi Jawa Barat untuk tahun 2027. Proyek ini menggabungkan data ekonomi makro tradisional dengan data aspirasi publik yang diekstrak dari platform YouTube.

Sistem menggunakan teknik Natural Language Processing (NLP) untuk memahami sentimen masyarakat terhadap isu upah, yang kemudian diintegrasikan ke dalam model prediksi berbasis Machine Learning.

## Metodologi dan Alur Kerja
1. Data Scraping: Pengambilan lebih dari 570 komentar dari YouTube menggunakan YouTube Data API v3.
2. Big Data Processing: Pemrosesan data skala besar menggunakan Apache Spark (PySpark).
3. Sentiment Analysis: Klasifikasi komentar masyarakat ke dalam beberapa kategori isu seperti Keadilan, Kelayakan Upah, dan Harga Pangan.
4. Data Integration: Menggabungkan hasil sentimen dengan data PDRB dan Inflasi Jawa Barat.
5. Predictive Modeling: Menggunakan algoritma Linear Regression untuk menghasilkan proyeksi kenaikan UMK sebesar 5.37%.
6. Visualization: Dashboard interaktif menggunakan framework Streamlit.

## Isi Repository
* finalprojectmkjabar2027.ipynb: Notebook utama berisi seluruh kode pemrosesan (Google Colab).
* data_sentimen_umk_570_komentar (2).csv: Dataset hasil analisis sentimen komentar YouTube.
* inflasi_jabar.csv: Dataset indikator inflasi.
* pdrb_jabar_2023.csv: Dataset Produk Domestik Regional Bruto.
* umk_jabar_21_25.csv: Dataset historis UMK Jawa Barat.

---
Proyek ini merupakan Tugas Akhir (UAS) untuk mata kuliah Big Data.
