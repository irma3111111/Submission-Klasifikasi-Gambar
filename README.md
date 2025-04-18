# Garbage Classification Project

## 📚 Deskripsi Proyek

Proyek ini dibuat untuk memenuhi tugas submission pada kelas **Klasifikasi Gambar** dari Dicoding. Fokus dari proyek ini adalah membangun model untuk mengklasifikasikan berbagai jenis sampah menggunakan dataset gambar. Model dikembangkan menggunakan TensorFlow dan diterapkan dalam beberapa format penyimpanan seperti SavedModel, TensorFlow Lite, dan TensorFlow\.js agar dapat digunakan di berbagai platform.

## 📂 Struktur Proyek

```
├───tfjs_model
│   ├───group1-shard1of1.bin
│   └───model.json
├───tflite
│   ├───model.tflite
│   └───label.txt
├───saved_model
│   ├───saved_model.pb
│   └───variables
├───notebook.ipynb
├───README.md
└───requirements.txt
```

## 📦 Teknologi yang Digunakan

- Python
- TensorFlow
- TensorFlow Lite
- TensorFlow\.js
- Scikit-learn
- Matplotlib & Seaborn
- Google Colab

## 🔥 Fitur Proyek

- Membuat dan melatih model klasifikasi gambar.
- Menyimpan model ke dalam format SavedModel, TF-Lite, dan TFJS.
- Visualisasi akurasi dan loss selama training.
- Evaluasi model menggunakan classification report dan confusion matrix.
- Melakukan inference dari model yang telah dilatih.

## 🗂️ Dataset

Dataset yang digunakan berasal dari Kaggle:

**[Garbage Classification Dataset by Mostafa Abla](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)**.

## 🚀 Cara Menjalankan Proyek

1. Clone repository ini.
2. Install dependencies dari `requirements.txt`.
3. Jalankan `notebook.ipynb` menggunakan Jupyter Notebook atau Google Colab.
4. Ikuti setiap sel kode untuk membangun, melatih, mengevaluasi, dan menyimpan model.



Terima kasih telah membaca! Semoga bermanfaat dan menginspirasi! 🌟

