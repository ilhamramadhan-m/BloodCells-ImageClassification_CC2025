# 🧬 Klasifikasi Sel Darah: Deep Learning untuk Pengenalan Citra Mikroskopis

## 📌 Ringkasan Proyek

Proyek ini bertujuan untuk membangun model klasifikasi citra menggunakan **Convolutional Neural Networks (CNNs)** guna mengidentifikasi berbagai jenis sel darah dari gambar mikroskopis. Tujuan utamanya adalah menciptakan pengklasifikasi yang andal untuk membantu proses otomatisasi kategorisasi sel darah — sebuah tugas yang selama ini dilakukan secara manual oleh tenaga medis profesional.

## 📁 Dataset

Dataset yang digunakan tersedia secara publik di Kaggle:

🔗 [Blood Cells Image Dataset](https://www.kaggle.com/datasets/unclesamulus/blood-cells-image-dataset)

Dataset ini berisi ribuan gambar sel darah yang telah diberi label, dengan beberapa kelas utama seperti:

* Neutrofil
* Eosinofil
* Basofil
* Limfosit
* Monosit
* Platelet
* Granulosit Imatur (IG)
* Eritroblas

## 🛠 Alur Kerja Proyek

Proyek ini terdiri dari beberapa tahapan penting:

* **Eksplorasi & Pra-pemrosesan Data**: Resize gambar, normalisasi, augmentasi citra.
* **Pengembangan Model**: Membangun dan melatih arsitektur CNN menggunakan TensorFlow/Keras.
* **Evaluasi Model**: Menggunakan metrik seperti akurasi, presisi, recall, dan confusion matrix.
* **Deploy Model**: Mengekspor model yang telah dilatih ke beberapa format untuk berbagai platform:

  * **TensorFlow SavedModel** (untuk deployment berbasis server)
  * **TensorFlow\.js** (untuk deployment di web)
  * **TensorFlow Lite** (untuk perangkat mobile dan edge)

## 📂 Struktur Direktori

```
submission/
├───tfjs_model/
│   ├───group1-shard1of4.bin
│   └───model.json
├───tflite/
│   ├───model.tflite
│   └───labels.txt
├───saved_model/
│   ├───assets/
│   ├───variables/
│   ├───fingerprint.pb
│   └───saved_model.pb
├───notebook.ipynb
├───README.md
└───requirements.txt
```

## ⚙️ Persiapan Environment

### 1. Membuat dan Mengaktifkan Virtual Environment

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 2. Instalasi Dependensi

```bash
pip install -r requirements.txt
```
