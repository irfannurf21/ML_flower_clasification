# README

## Ringkasan Proyek

Proyek ini berisi Jupyter Notebook (`notebook.ipynb`) yang melakukan analisis, pemodelan dan inference model machine learning. Dataset yang digunakan adalah **Flower Classification** dari Kaggle:

[https://www.kaggle.com/datasets/utkarshsaxenadn/flower-classification-5-classes-roselilyetc](https://www.kaggle.com/datasets/utkarshsaxenadn/flower-classification-5-classes-roselilyetc)

Spesifikasi dataset:
- Memiliki 10 label : {Aster, Daisy, Iris, Lavender, Lily, Marigold, Orchid, Poppy, Rose, Sunflower}
- Total data gambar : 22355

Notebook ini mencakup:
- **Pra-pemrosesan dan eksplorasi data**
- **Pelatihan dan evaluasi model**
- **Evaluasi dan visualisasi hasil**
- **Inference model**


Hasil evaluasi model:
- **Akurasi confusion matrix**: 90%
- **Akurasi pelatihan (train)**: 96.88%
- **Akurasi pengujian (test)**: 89.58%

Struktur file
```md 
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

## Instalasi

Untuk menginstal dependensi yang diperlukan, jalankan perintah berikut:

```bash
pip install -r requirements.txt
```

## Cara Penggunaan

1. Buka notebook di Jupyter atau Google Colab.
2. Jalankan sel secara berurutan untuk mengeksekusi pemrosesan data, pelatihan model, dan evaluasi.
3. Ubah parameter sesuai kebutuhan untuk bereksperimen dengan model yang berbeda.

## Lisensi

Proyek ini menggunakan dataset dari Kaggle dan mematuhi ketentuan penggunaan dataset tersebut. Harap periksa lisensi dataset sebelum menggunakannya untuk keperluan lain.

