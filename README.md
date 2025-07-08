# Akhir Submission - BPML (Belajar Pengembangan Machine Learning)

Repositori ini berisi submission akhir untuk program belajar **Pengembangan Machine Learning**. Proyek ini mencakup proses pelatihan model image classification sederhana menggunakan TensorFlow, serta konversi model ke berbagai format deployment seperti TensorFlow Lite dan TensorFlow.js.

---

## 📁 Struktur Direktori
BPML-ImageClassification
├───tfjs_model
| ├───group1-shard1of1.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───label.txt
├───saved_model
| ├───saved_model.pb
| └───variables
├───Nabila_Alawiyah_Submission_Akhir_BPML_2.ipynb
├───README.md
└───Requirements.txt

---

## 📘 Penjelasan File

### `Nabila_Alawiyah_Submission_Akhir_BPML_2.ipynb`
Notebook utama yang mencakup:

- Persiapan dan preprocessing dataset gambar
- Pembuatan dan pelatihan model CNN
- Evaluasi performa model
- Penyimpanan model dalam format `SavedModel`
- Konversi model ke format:
  - TensorFlow Lite (`.tflite`)
  - TensorFlow.js (`tfjs`)

### `saved_model/`
Folder ini menyimpan model hasil pelatihan dalam format asli TensorFlow (`SavedModel`). Format ini biasa digunakan untuk retraining dan deployment di server.

### `tflite/`
Model hasil konversi ke format **TensorFlow Lite**, cocok untuk aplikasi mobile atau embedded device (Android, IoT, dll).

### `tfjs_model/`
Model yang telah dikonversi ke format **TensorFlow.js**, memungkinkan integrasi langsung ke dalam aplikasi web berbasis JavaScript.

### `Requirements.txt`
File ini berisi daftar dependency yang digunakan dalam proyek. Install dengan:

```bash
pip install -r Requirements.txt
