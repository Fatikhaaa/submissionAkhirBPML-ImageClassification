# Submission Proyek Akhir Kelas Belajar Pengembangan Machine Learning - Image Classification
Proyek Klasifikasi Gambar dari modul "Belajar Pengembangan Machine Learning (BPML)" pada kelas Dicoding program Coding Camp 2025 powered by DBS Foundation.

## 📸 Image Classification Project

**Klasifikasi Gambar Menggunakan Deep Learning**  
Projek ini mengimplementasikan model deep learning untuk mengklasifikasikan gambar ke dalam beberapa kategori dengan akurasi tinggi.

## 🚀 Fitur Utama
- **Klasifikasi Multi-Kelas**  
  Membedakan gambar ke dalam kategori: 
  - 🐶 Anjing (Dog)
  - 🐴 Kuda (Horse)
  - 🕷️ Laba-laba (Spider)

- **Arsitektur**  
  Menggunakan model CNN dengan:
  - Lapisan konvolusi untuk ekstraksi fitur
  - Batch normalization untuk stabilisasi training
  - Dropout layer untuk mencegah overfitting

- **Akurasi Tinggi**  
  - **0.97%** pada data validasi
  - **0.95%** pada data training

- **Loss Rendah**  
  - **0.07%** pada data validasi
  - **0.11%** pada data training

## 💻 Teknologi
- Python 3.8+
- TensorFlow 2.15
- Keras API
- OpenCV untuk preprocessing

## 📂 Struktur Projek
```
/
📁 submissionBPML-image-classification/
├── 📁 models/
│   ├── best_model.keras
│   ├── model.h5
│   ├── 📁 saved_model/          # Format SavedModel
│   ├── 📁 tfjs_model/          # Model TFJS
│   └── 📁 tflite_model/        # Model TFLite
├── 📁 assets/
│   └── gambar/                # Contoh gambar untuk testing
├── 📄 submissionBPML_Image_Classification.py  # Script utama
├── 📄 translate.py            # Utility terjemahan
├── 📄 requirements.txt
└── 📄 README.md
```

## 📈 Hasil Submission Dicoding oleh Reviewer
![Hasil Submission](gambar/hasil_submission.jng)
