# Proyek-Klasifikasi-Gambar

Proyek ini merupakan tugas akhir klasifikasi citra menggunakan Convolutional Neural Network (CNN) dengan dataset berisi 3 kelas: **kucing (cats)**, **anjing (dogs)**, dan **ular (snakes)**. Dataset telah dibagi menjadi data training, validation, dan testing, masing-masing sebanyak:

- **Train**: 700 gambar/kelas
- **Validation**: 150 gambar/kelas
- **Test**: 150 gambar/kelas

---

## 📊 Akurasi Model
Model CNN yang dibangun berhasil mencapai:

- **Akurasi testing**: >98%
- F1-Score tertinggi pada semua kelas

---


## 🛠️ Format Model

- `saved_model/`: Format standar TensorFlow untuk digunakan dalam deployment.
- `tflite/`: Format ringan untuk digunakan pada perangkat mobile/embedded.
- `tfjs_model/`: Format TensorFlow.js untuk digunakan di browser.

---

## 🧪 Environment & Library

Untuk menjalankan proyek ini, install dependensi yang tersedia pada `requirements.txt`.

---

## 🖼️ Augmentasi Gambar

Augmentasi data digunakan untuk meningkatkan generalisasi model, termasuk:
- Rotasi acak
- Zoom in/out
- Flipping horizontal
- Brightness variation
