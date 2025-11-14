# Proyek Klasifikasi Gambar Sampah – RealWaste Dataset

Proyek ini bertujuan membangun model deep learning untuk mengenali jenis sampah berdasarkan gambar menggunakan dataset RealWaste. Model ini membantu proses pengelompokan sampah secara otomatis sehingga dapat mendukung inisiatif pengelolaan lingkungan dan daur ulang.

Dataset

Dataset yang digunakan adalah RealWaste, dataset untuk klasifikasi sampah yang terdiri dari beberapa kategori seperti:
- FoodOrganics
- Vegetation
- Plastic
- Metal
- Cardboard
- Misc Trash
- Glass
- Paper
- Textile Trash

Dataset ini memiliki lisensi CC BY-NC-SA 4.0.

## Langkah Pengerjaan
1. Data Preparation
  
  - Mengimpor library yang diperlukan (TensorFlow, Keras, NumPy, Matplotlib)
  
  - Memuat dataset berdasarkan folder per-label
  
  - Membuat struktur direktori agar dataset siap diproses model
  
  - Melakukan augmentasi data untuk mencegah overfitting

2. Model Training

- Menggunakan Transfer Learning (EfficientNetB4 sebagai base model) dan arsitektur CNN (Convolutional Neural Network) untuk penyesuaian dengan data sampah

- Menentukan batch size, optimizer, dan loss function

- Melatih model dengan training dan validation set

3. Evaluasi

- Menganalisis akurasi dan loss

- Menampilkan grafik training vs validation accuracy

- Memprediksi sampel uji menggunakan gambar baru

- Visualisasi hasil prediksi

## Output & Manfaat

Model mampu mengenali jenis sampah berdasarkan gambar dan memberikan prediksi label dengan tingkat akurasi tertentu.
Aplikasi model ini dapat digunakan untuk:

- Sistem pemilahan sampah otomatis

- Edukasi pengelompokan sampah

- Sistem pendukung pengelolaan lingkungan

- Prototype aplikasi mobile/IoT pengenalan sampah

## Teknologi yang Digunakan

- Python

- TensorFlow / Keras

- NumPy

- Matplotlib

- Jupyter Notebook
