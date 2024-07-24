Prediksi Harga Mobil Toyota
1. Project Overview
Proyek ini bertujuan untuk memprediksi harga mobil Toyota berdasarkan beberapa fitur seperti tahun, jarak tempuh, pajak, mpg, dan ukuran mesin. Model ini diharapkan dapat memberikan estimasi harga mobil yang akurat sehingga dapat membantu dalam pengambilan keputusan untuk pembelian atau penjualan mobil.

Identitas Lengkap
Nama: Akhmad Haris
NIM: A11.2022.14626
Matkul: Pembelajaran Mesin
Kelompok: A11.4413
2. Ringkasan dan Permasalahan Project
Ringkasan
Proyek ini bertujuan untuk memprediksi harga mobil Toyota berdasarkan beberapa fitur seperti tahun, jarak tempuh, pajak, mpg, dan ukuran mesin. Model ini diharapkan dapat memberikan estimasi harga mobil yang akurat sehingga dapat membantu dalam pengambilan keputusan untuk pembelian atau penjualan mobil.

Permasalahan
Bagaimana cara memprediksi harga mobil dengan menggunakan dataset yang berisi informasi mengenai fitur-fitur mobil?

Tujuan
Membangun model machine learning untuk memprediksi harga mobil Toyota.
Membandingkan performa model Linear Regression, Random Forest Regressor, dan Gradient Boosting Regressor.
Melakukan tuning hyperparameter untuk meningkatkan performa model.

Alur Penyelesaian
'''mermaid
Copy code
graph LR
   A[Mulai] --> B[Load dan Preprocessing Data]
    B --> C[EDA dan Feature Engineering]
    C --> D[Pemisahan Data Train dan Test]
    D --> E[Modeling]
    E --> F[Evaluasi Model]
    F --> G[Selesai]
3. Penjelasan Dataset, EDA, dan Proses Features Dataset
Dataset
Dataset yang digunakan adalah dataset harga mobil Toyota yang berisi informasi tentang harga mobil dan beberapa fitur seperti tahun, jarak tempuh, pajak, mpg, ukuran mesin, dan model mobil.

Exploratory Data Analysis (EDA)
EDA dilakukan untuk memahami karakteristik dataset dan hubungan antara fitur-fitur yang ada. Beberapa langkah EDA yang dilakukan meliputi:

Menampilkan distribusi fitur
Memvisualisasikan korelasi antara fitur-fitur
Menangani missing values
Mengatasi data outliers
Proses Features Dataset
Setelah EDA, fitur-fitur diproses untuk digunakan dalam model machine learning. Beberapa langkah yang dilakukan meliputi:

Encoding fitur kategorikal
Normalisasi atau standarisasi fitur numerik
Pemisahan dataset menjadi training set dan test set
4. Modeling
Modeling dilakukan menggunakan beberapa algoritma machine learning seperti:

Linear Regression
Random Forest Regressor
Gradient Boosting Regressor
Setiap model di-train menggunakan training set dan dievaluasi menggunakan test set. Hyperparameter tuning dilakukan untuk mendapatkan performa terbaik dari setiap model.

5. Evaluasi Model
Model dievaluasi menggunakan metrik-metrik berikut:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R²)
Hasil evaluasi digunakan untuk membandingkan performa model dan memilih model terbaik untuk prediksi harga mobil Toyota.

6. Hasil Evaluasi Model
Hasil evaluasi model akan ditampilkan dalam notebook, termasuk perbandingan performa antara model Random Forest Regressor, dan Gradient Boosting Regressor. Hasil ini akan digunakan untuk memilih model terbaik.
