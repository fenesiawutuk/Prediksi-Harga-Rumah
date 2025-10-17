# Prediksi-Harga-Rumah

**Prediksi Harga Rumah Jakarta Selatan**

Proyek ini bertujuan untuk membangun dan mengevaluasi model Machine Learning yang mampu memprediksi harga rumah di wilayah Jakarta Selatan. Seluruh langkah analisis data, pra-pemrosesan, pemodelan, dan visualisasi didokumentasikan sepenuhnya dalam file Jupyter Notebook utama proyek ini.

Sumber data yang digunakan dalam proyek ini adalah Dataset Harga Rumah Daerah Jakarta Selatan, yang diperoleh dari website Kaggle:https://www.kaggle.com/datasets/wisnuanggara/daftar-harga-rumah

**Alur Kerja Proyek:**

**1.Data Understanding:** Melakukan inspeksi awal untuk memahami struktur dataset, termasuk melihat jumlah total data, mengecek tipe data dari setiap fitur, dan memastikan penamaan variabel sudah jelas.

**2.Cleaning Data:** Setelah pemahaman awal, dilakukan fase Data Cleaning. Dalam tahap ini, fokus pada peningkatan kualitas data dengan menghapus missing value dan data duplikat yang ditemukan dalam dataset. Selain itu, penamaan variabel tertentu diubah (renaming) untuk menjaga konsistensi dan kemudahan interpretasi selama analisis lebih lanjut.

**3.Preprocessing Data:** Pada tahapan ni dilakukan label encoder yaitu mengubah data kategorikal ke dalam bentuk angka. Fitur seperi Garage_Availabel diubah menggunakan Label Encoder, di mana nilai 'ada' diubah menjadi 0 dan 'tidak ada' menjadi 1. Data kemudian dipisahkan menjadi data latih dan data uji dengan test size sebesar 0.1.

**4.Training and Evaluation Model:** Model dilatih menggunakan algoritma Random Forest dengan n_estimators 200. Setelah model dilatih, kinerjanya dievaluasi menggunakan metrik yaitu MSE (Mean Squared Error) dan R^2. 

**5.Testing:** Setelah model dilatih dan dievaluasi, selanjutnya adalah melakukan pengujian dengan data baru yang belum pernah dimuat dalam pelatihan model.

**6.Visualization Model Prediction:** Tahap akhir, memvisualisasikan hasil prediksi model untuk melihat perbandingan antara model aktual dan model prediksi menggunakan Random Forest.
