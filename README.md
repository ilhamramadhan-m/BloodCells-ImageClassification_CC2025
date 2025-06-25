# Proyek Klasifikasi Sel Darah: Blood Cells Image Dataset

## Deskripsi
Proyek ini bertujuan untuk mengembangkan model klasifikasi gambar/citra berbasis Convolutional Neural Network (CNN). Model yang dibangun akan memproses gambar  dan mengkategorikan gambar tersebut ke dalam kelas-kelas sel darah.

## Dataset
[Blood Cells Image Dataset](https://www.kaggle.com/datasets/unclesamulus/blood-cells-image-dataset)

Proyek ini mencakup beberapa tahap, antara lain:
- Eksplorasi dan pra-pemrosesan data
- Pengembangan dan pelatihan model CNN
- Evaluasi kinerja model
- Konversi model ke berbagai format deployment (TensorFlow.js, TensorFlow Lite)

---

## Struktur Direktori
```
submission/
├───tfjs_model
| ├───group1-shard1of4.bin
| └───model.json
├───tflite
| ├───model.tflite
| └───labels.txt
├───saved_model
| ├───assets
| ├───variables
| ├───fingerprint.pb
| └───saved_model.pb
├───notebook.ipynb
├───README.md
└───requirements.txt
```

## Setup Environment
### Membuat dan mengaktivasi virtual environment:
```bash
python -m venv venv
venv\Scripts\activate
```

### Install library/dependency
```bash
pip install -r requirements.txt
```
