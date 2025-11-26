# Tubes Mata Kuliah Kecerdasan Buatan

## Kelompok 2

### **"Prediksi Prestasi Akademik Siswa Menggunakan Machine Learning Berdasarkan Faktor Demografis dan Kehadiran"**

---

## 📌 Deskripsi Proyek

Proyek ini bertujuan untuk memprediksi kategori hasil akademik siswa (GPA) berdasarkan beberapa faktor seperti jenis kelamin, usia, jam belajar, tingkat kehadiran, pekerjaan paruh waktu, dan partisipasi dalam kegiatan ekstrakurikuler.

Dataset yang digunakan bersifat **synthetic** dan ditujukan untuk keperluan eksperimen machine learning.

Prediksi dilakukan menggunakan empat algoritma:

1. **Naive Bayes**
2. **Decision Tree**
3. **Support Vector Machine (SVM)**
4. **Random Forest**

Evaluasi dilakukan menggunakan metrik:

* Accuracy
* Classification Report (precision, recall, f1-score)
* Confusion Matrix

---

## 🧠 Tujuan Pembelajaran

* Menerapkan algoritma pembelajaran mesin untuk permasalahan klasifikasi multi-kelas
* Melakukan preprocessing data dan feature scaling
* Membandingkan performa beberapa model machine learning
* Menganalisis faktor yang mempengaruhi prestasi akademik siswa

---

## 📊 Dataset

Dataset dapat diakses melalui Kaggle:

> **Link Dataset:**  
> [https://www.kaggle.com/datasets/waqi786/student-performance-dataset/data](https://www.kaggle.com/datasets/waqi786/student-performance-dataset/data)

Format dataset digunakan dalam file:

```
student_performance_data_update.csv
```

---

## 🏷️ Atribut Data

| Kolom                     | Tipe                           | Deskripsi                                 |
| ------------------------- | ------------------------------ | ----------------------------------------- |
| Gender                    | Numerik (0 = Female, 1 = Male) | Jenis kelamin siswa                       |
| Age                       | Numerik                        | Usia siswa                                |
| StudyHoursPerWeek         | Numerik                        | Jam belajar per minggu                    |
| AttendanceRate            | Numerik (0–100)                | Persentase kehadiran                      |
| PartTimeJob               | Numerik (0/1)                  | Apakah bekerja paruh waktu                |
| ExtraCurricularActivities | Numerik (0/1)                  | Apakah mengikuti kegiatan ekstrakurikuler |
| GPA                       | Label Kelas                    | Target untuk diprediksi                   |

---

## 🧪 Model Machine Learning yang Digunakan

| Model                  | Jenis                    |
| ---------------------- | ------------------------ |
| Gaussian Naive Bayes   | Probabilistic Classifier |
| Decision Tree          | Tree-Based Model         |
| Support Vector Machine | Margin-Based Classifier  |
| Random Forest          | Ensemble Learning        |

---

## 🚀 Cara Menjalankan Program

### 1. Instalasi Dependensi

Pastikan sudah menginstal dependensi berikut:

```bash
pip install pandas numpy scikit-learn
```

### 2. Persiapan Dataset

Letakkan dataset:

```
student_performance_data_update.csv
```

di direktori yang sama dengan file kode `.ipynb` atau `.py`

### 3. Menjalankan Program

Jalankan script Python:

```bash
python main.py
```

Atau gunakan Jupyter Notebook untuk menjalankan secara interaktif.

---

## 👥 Anggota Kelompok

| No  | Nama                    |
| --- | ----------------------- |
| 1   | Rakasya Yoga            |
| 2   | R. Rafi Yudi Pramana    |
| 3   | Datu Reksa Hamza Putra  |
| 4   | M. Ali Abdillah Khotami |
| 5   | Aditya                  |

---

## 📌 Output

Program akan menampilkan:

* Akurasi tiap model
* Classification Report
* Confusion Matrix
* Perbandingan performa model untuk menentukan yang terbaik

---

## 🎯 Kesimpulan Singkat

Hasil eksperimen ini dapat digunakan untuk memahami:

* Model mana yang paling efektif dalam memprediksi prestasi siswa
* Pengaruh faktor demografis dan perilaku belajar terhadap pencapaian akademik

---

## 📄 Lisensi

Proyek ini dibuat untuk keperluan akademik Mata Kuliah Kecerdasan Buatan.

---

## 📧 Kontak

Untuk pertanyaan lebih lanjut, silakan hubungi anggota kelompok melalui repository ini.

---

**© 2025 Kelompok 2 - Kecerdasan Buatan**