# 📊 Proyek Akhir Data Mining
## Preprocessing dan Unsupervised Learning (K-Means Clustering)

---

## 👨‍🎓 Identitas Mahasiswa

**Nama : Abdallah Najwan Muharidien**

**NIM : 241011400767**

**Kelas : 04TPLM008**

**Mata Kuliah : Data Mining** 

---

# 📖 Deskripsi Proyek

Proyek ini merupakan tugas akhir mata kuliah **Data Mining** yang bertujuan untuk melakukan proses **Preprocessing Data** dan menerapkan algoritma **Unsupervised Learning (K-Means Clustering)** pada dataset **Customer Personality Analysis**.

Tahapan yang dilakukan meliputi:

- Data Understanding
- Data Cleaning
- Penanganan Missing Value
- Penanganan Data Duplikat
- Normalisasi Data
- Penentuan Jumlah Cluster menggunakan Elbow Method
- Clustering menggunakan K-Means
- Evaluasi menggunakan Silhouette Score
- Visualisasi menggunakan PCA (Principal Component Analysis)

---

# 📂 Struktur Folder

```
UAS_DATA_MINING/
│
├── dataset/
│   └── marketing_campaign.csv
│
├── output/
│   └── hasil_clustering.csv
│
├── venv/
│
├── clustering.ipynb
│
├── README.md
│
└── Laporan_Proyek_Akhir.pdf
```

---

# 🛠 Software yang Digunakan

- Visual Studio Code
- Python 3.x
- Jupyter Notebook

---

# 📚 Library yang Digunakan

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

# ⚙ Cara Menjalankan Program

## 1. Clone / Download Project

Letakkan project pada folder yang diinginkan.

---

## 2. Aktifkan Virtual Environment

Windows

```bash
venv\Scripts\activate
```

---

## 3. Install Library

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install notebook
```

atau

```bash
pip install -r requirements.txt
```

---

## 4. Jalankan Jupyter Notebook

```bash
jupyter notebook
```

atau buka menggunakan **Visual Studio Code**.

---

# 📊 Dataset

Dataset yang digunakan adalah:

**Customer Personality Analysis**

Jumlah Data :

- 2240 Baris

Jumlah Kolom :

- 29 Kolom

Dataset digunakan untuk melakukan analisis karakteristik pelanggan berdasarkan informasi pendapatan, perilaku pembelian, dan aktivitas pelanggan.

---

# 🔄 Tahapan Pengerjaan

1. Import Library
2. Membaca Dataset
3. Data Understanding
4. Cleaning Data
5. Missing Value
6. Data Duplikat
7. StandardScaler
8. Elbow Method
9. K-Means Clustering
10. Silhouette Score
11. PCA
12. Visualisasi Cluster
13. Analisis Cluster

---

# 📈 Hasil

Hasil penelitian menunjukkan bahwa:

- Missing Value berhasil ditangani menggunakan Mean Imputation.
- Tidak ditemukan data duplikat.
- Data berhasil dinormalisasi menggunakan StandardScaler.
- Jumlah cluster terbaik diperoleh menggunakan Elbow Method.
- Algoritma K-Means berhasil mengelompokkan data pelanggan menjadi **3 Cluster**.
- Evaluasi menggunakan Silhouette Score menunjukkan kualitas clustering yang cukup baik.
- Visualisasi PCA memperlihatkan persebaran data pada masing-masing cluster.

---

# 📁 Output

Program akan menghasilkan file:

```
output/
└── hasil_clustering.csv
```

File tersebut berisi dataset beserta label cluster hasil proses K-Means.

---

# 📖 Referensi

1. Han, J., Kamber, M., & Pei, J. (2012). *Data Mining: Concepts and Techniques.*

2. Tan, P. N., Steinbach, M., Karpatne, A., & Kumar, V. (2019). *Introduction to Data Mining.*

3. Pedregosa, F., et al. (2011). *Scikit-Learn: Machine Learning in Python.*

4. McKinney, W. (2022). *Python for Data Analysis.*

5. Customer Personality Analysis Dataset (Kaggle)

---

# 👨‍💻 Penulis

CodeName : Abdallah Najwan Muharidien A.K.A SigmaaWann
 
