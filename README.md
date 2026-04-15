# Prediksi Penjualan Cabang (Big Mart Sales) - UTS Pembelajaran Mesin

Proyek ini merupakan tugas Ujian Tengah Semester (UTS) Mata Kuliah **Pembelajaran Mesin** Semester Genap TA 2025/2026 di **Universitas Primakara**. Proyek ini bertujuan untuk membangun sistem prediksi numerik menggunakan algoritma *Simple Linear Regression* dan *Multiple Linear Regression* untuk memperkirakan total penjualan barang di berbagai cabang toko Big Mart.

##  Deskripsi Proyek
Sistem ini melakukan prediksi terhadap variabel target `Item_Outlet_Sales` (Total Penjualan Barang) berdasarkan fitur-fitur pendukung seperti harga maksimal barang, visibilitas di rak, ukuran toko, hingga umur toko. Proyek ini mencakup seluruh pipeline Machine Learning mulai dari:
1. Exploratory Data Analysis (EDA) & Visualisasi.
2. Data Preprocessing (Handling missing values & encoding).
3. Feature Engineering.
4. Pemodelan Regresi.
5. Evaluasi Statistik.

##  Dataset
Dataset yang digunakan dalam proyek ini adalah **Big Mart Sales Data** yang diambil dari Kaggle. Dataset ini memenuhi syarat minimal tugas yaitu lebih dari 500 baris data (total ~8.500 baris).

* **Sumber Dataset:** [Kaggle - Big Mart Sales Prediction]([https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data](https://www.kaggle.com/datasets/brijbhushannanda1979/bigmart-sales-data)
* **File Utama:** `Train.csv` (digunakan untuk pelatihan dan pengujian model).

##  Ketentuan Teknis & Library
Proyek ini dikembangkan menggunakan **Python 3.8+** dengan library utama sebagai berikut:
* `NumPy`: Manipulasi array dan komputasi numerik.
* `Pandas`: Manipulasi data tabel/DataFrame.
* `Matplotlib` & `Seaborn`: Visualisasi data dan grafik.
* `Scikit-learn`: Implementasi model Machine Learning dan evaluasi.

##  Cara Menjalankan Proyek
1. **Clone Repositori:**
   ```bash
   git clone [https://github.com/username-kamu/nama-repo.git](https://github.com/username-kamu/nama-repo.git)
   cd nama-repo
