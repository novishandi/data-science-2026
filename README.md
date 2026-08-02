# Portofolio Belajar Data Science

## Identitas

**Nama** : Novi Shandi  
**NIM** : 240401010291  
**Kelas** : IF401  
**Program Studi** : PJJ Informatika

---

## Deskripsi Repository

Halo, perkenalkan saya **Novi Shandi**, mahasiswa yang sedang mempelajari bidang **Data Science**. Repository ini dibuat sebagai dokumentasi sekaligus portofolio proses pembelajaran saya selama mengikuti mata kuliah Pengantar Data Science.

Tujuan saya mempelajari Data Science adalah untuk memahami bagaimana data dapat diolah, dianalisis, dan dimanfaatkan dalam pengambilan keputusan menggunakan bahasa pemrograman Python serta berbagai library pendukung.

Repository ini berisi kumpulan notebook praktikum mulai dari pengenalan Python, eksplorasi data, visualisasi data, preprocessing dataset, hingga implementasi dasar machine learning menggunakan algoritma Regresi Linear. Setiap notebook dibuat berdasarkan aktivitas Hands-on pada setiap pertemuan dan dilengkapi dengan penjelasan, analisis, serta kesimpulan hasil praktikum.

Selain sebagai media pengumpulan tugas, repository ini juga diharapkan dapat menjadi dokumentasi perkembangan kemampuan saya dalam mempelajari Data Science.

---

## Daftar Pertemuan

| Pertemuan | Topik | Notebook |
|-----------|--------|-----------|
| Pertemuan 1 | Pengenalan Python dan Jupyter Notebook | [Buka Notebook](./Pertemuan1_NoviShandi_240401010291.ipynb) |
| Pertemuan 2 | Dasar Pemrograman Python | [Buka Notebook](./Pertemuan2_NoviShandi_240401010291.ipynb) |
| Pertemuan 3 | NumPy untuk Pengolahan Data | [Buka Notebook](./Pertemuan3_NoviShandi_240401010291.ipynb) |
| Pertemuan 4 | Eksplorasi Statistik Dataset Iris | [Buka Notebook](./Pertemuan4_NoviShandi_240401010291.ipynb) |
| Pertemuan 5 | Dashboard Visualisasi Data Dataset Tips | [Buka Notebook](./Pertemuan5_NoviShandi_240401010291.ipynb) |
| Pertemuan 6 | Preprocessing Dataset Titanic | [Buka Notebook](./Pertemuan6_NoviShandi_240401010291.ipynb) |
| Pertemuan 7 | Prediksi Gaji Menggunakan Regresi Linear | [Buka Notebook](./Pertemuan7_NoviShandi_240401010291.ipynb) |
| Pertemuan 9 | Algoritma Klasifikasi (Bagian 1): Logistic Regression & Decision Tree | [Buka Notebook](https://github.com/novishandi/data-science-2026/blob/main/Pertemuan9_NoviShandi_240401010291.ipynb) |
| Pertemuan 10 | Algoritma Klasifikasi (Bagian 2): Random Forest & Imbalanced Dataset | [Buka Notebook](https://github.com/novishandi/data-science-2026/blob/main/Pertemuan10_NoviShandi_240401010291.ipynb) |
| Pertemuan 11 | Unsupervised Learning: Clustering (K-Means & Hierarchical) | [Buka Notebook](https://github.com/novishandi/data-science-2026/blob/main/Pertemuan11_NoviShandi_240401010291.ipynb) |
| Pertemuan 12 | Asosiasi Data (Apriori) & Sistem Rekomendasi Dasar | [Buka Notebook](https://github.com/novishandi/data-science-2026/blob/main/Pertemuan12_NoviShandi_240401010291.ipynb) |
| Pertemuan 13 | Pengantar Deep Learning & NLP Dasar (TF-IDF) | [Buka Notebook](https://github.com/novishandi/data-science-2026/blob/main/Pertemuan13_NoviShandi_240401010291.ipynb) |

---

## Tools dan Library yang Digunakan

Dalam proses pembelajaran dan praktikum, saya menggunakan beberapa tools dan library berikut:

- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn (sklearn)
- mlxtend
- TensorFlow / Keras
- SciPy

---

## Cara Menjalankan Notebook

### Melalui Google Colab

1. Buka repository GitHub ini.
2. Pilih notebook (.ipynb) yang ingin dijalankan.
3. Klik tombol **Open in Colab** (jika tersedia), atau upload file notebook ke Google Colab.
4. Jalankan seluruh cell dengan memilih menu:

```
Runtime → Run All
```

### Menjalankan Secara Lokal

Pastikan Python dan library yang dibutuhkan telah terpasang.

Install library:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Jalankan Jupyter Notebook:

```bash
jupyter notebook
```

Kemudian buka file notebook yang diinginkan dan jalankan seluruh cell.

---

## Kesimpulan Perjalanan Belajar Data Science (Pertemuan 1–13)

Selama mengikuti pembelajaran Data Science dari Pertemuan 1 hingga Pertemuan 7, saya telah mempelajari berbagai konsep dasar yang menjadi fondasi dalam analisis data dan machine learning.

Pembelajaran dimulai dari pengenalan Python dan penggunaan Jupyter Notebook, kemudian dilanjutkan dengan pemanfaatan NumPy dan Pandas untuk pengolahan data. Setelah itu saya mempelajari eksplorasi statistik dan visualisasi data menggunakan Matplotlib dan Seaborn.

Pada tahap berikutnya, saya belajar melakukan preprocessing data, seperti menangani missing values, encoding data kategorikal, pembagian data train-test, dan feature scaling menggunakan dataset Titanic. Terakhir, saya mempelajari implementasi dasar machine learning dengan membangun model Regresi Linear untuk melakukan prediksi.

Melalui rangkaian praktikum ini, saya memperoleh pemahaman yang lebih baik mengenai alur kerja Data Science, mulai dari pengumpulan data, eksplorasi, pembersihan data, visualisasi, hingga pembuatan model prediksi sederhana.

Memasuki paruh kedua perkuliahan, saya mempelajari algoritma klasifikasi mulai dari Logistic Regression dan Decision Tree beserta metrik evaluasinya (Confusion Matrix, Accuracy, Precision, Recall, F1-Score), dilanjutkan dengan metode ensemble Random Forest dan penanganan imbalanced dataset pada kasus Customer Churn. Setelah itu saya beralih ke Unsupervised Learning, yaitu clustering menggunakan K-Means dan Hierarchical Clustering dengan Metode Elbow untuk menentukan jumlah cluster optimal, serta Association Rule Mining dengan algoritma Apriori untuk Market Basket Analysis dan konsep sistem rekomendasi. Pembelajaran ditutup dengan pengantar Deep Learning melalui Artificial Neural Network menggunakan Keras, dan dasar Natural Language Processing dengan TF-IDF untuk analisis sentimen.

Pelajaran terpenting yang saya peroleh adalah bahwa pemilihan metrik evaluasi harus disesuaikan dengan konteks masalah, bukan sekadar mengejar Accuracy tertinggi. Pada kasus diagnosis kanker dan prediksi churn yang datanya tidak seimbang, Recall justru menjadi metrik yang paling kritis karena kesalahan melewatkan kasus positif berdampak jauh lebih besar daripada alarm palsu.

Repository ini merupakan dokumentasi proses belajar saya dan akan terus dikembangkan seiring bertambahnya materi dan pengalaman dalam bidang Data Science.
