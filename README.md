# Shoe vs Sandal vs Boot Classification

Proyek ini bertujuan untuk melakukan klasifikasi gambar menjadi tiga kategori: **Boot**, **Sandal**, dan **Shoe** menggunakan model CNN (Convolutional Neural Network).

## Cara Menjalankan

1. Install semua dependency:
pip install -r requirements.txt

2. Jalankan notebook `notebook.ipynb` untuk melihat proses pelatihan, evaluasi, dan penyimpanan model.

3. Model tersedia dalam 3 format:
- **SavedModel** untuk server/cloud deployment
- **TF-Lite** untuk mobile/embedded deployment
- **TFJS** untuk browser deployment

## Dataset

Dataset yang digunakan: [Shoe vs Sandal vs Boot Dataset](https://www.kaggle.com/datasets/hasibalmuzdadid/shoe-vs-sandal-vs-boot-dataset-15k-images)

## Hasil

- Akurasi pada data testing mencapai **97%**.
- Model telah diekspor ke dalam berbagai format siap untuk deployment.

## Inference

Notebook menyediakan contoh inferensi untuk:
- TensorFlow SavedModel

Visualisasi gambar input dan prediksi juga ditampilkan.

---
"""
