# 🛒 AWS Sales Analysis — Capstone Project Modul 2

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Microsoft-Excel-217346?logo=microsoft-excel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

> **Capstone Project Modul 2** — Purwadhika Digital Technology School  
> Data Analysis menggunakan Python (Jupyter Notebook) & Excel

---

## 📋 Deskripsi Project

Project ini merupakan analisis mendalam terhadap dataset **AWS SaaS Sales** untuk memahami performa penjualan, profitabilitas, dan perilaku pelanggan di berbagai segmen, kategori produk, serta wilayah. Analisis ini bertujuan untuk menghasilkan insight yang dapat digunakan sebagai dasar pengambilan keputusan bisnis.

---

## 🎯 Tujuan Analisis

- Mengidentifikasi kategori dan sub-kategori produk yang paling menguntungkan
- Menganalisis tren penjualan berdasarkan waktu (bulanan/tahunan)
- Mengevaluasi performa penjualan per wilayah/region
- Memahami pola diskon dan dampaknya terhadap profit
- Memberikan rekomendasi bisnis berbasis data

---

## 📁 Struktur Repository

```
Capstone-Modul-2/
│
├── data/
│   └── superstore.xlsx          # Dataset utama
│
├── notebook/
│   └── analysis.ipynb           # Jupyter Notebook analisis utama
│
├── visualization/
│   └── dashboard.xlsx           # Dashboard Excel
│
└── README.md
```

---

## 🗂️ Dataset

| Atribut | Detail |
|---|---|
| **Sumber** | Sample Superstore Dataset |
| **Format** | `.xlsx` / `.csv` |
| **Jumlah Kolom** | ±20 kolom |
| **Periode Data** | Multi-tahun |

**Fitur Utama Dataset:**
- `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
- `Customer ID`, `Customer Name`, `Segment`
- `Country`, `City`, `State`, `Region`
- `Product ID`, `Category`, `Sub-Category`, `Product Name`
- `Sales`, `Quantity`, `Discount`, `Profit`

---

## 🔍 Alur Analisis

### 1. Data Understanding & Cleaning
- Import dan eksplorasi awal dataset
- Penanganan missing values dan duplikat
- Konversi tipe data (tanggal, numerik)

### 2. Exploratory Data Analysis (EDA)
- Statistik deskriptif seluruh variabel numerik
- Analisis distribusi Sales dan Profit
- Korelasi antar variabel

### 3. Analisis Bisnis
- **Analisis per Kategori** — Sales & Profit tiap kategori/sub-kategori
- **Analisis per Region** — Wilayah dengan performa terbaik & terburuk
- **Analisis Temporal** — Tren bulanan dan tahunan
- **Analisis Diskon** — Pengaruh diskon terhadap profit margin
- **Analisis Segmen Pelanggan** — Consumer, Corporate, Home Office

### 4. Visualisasi & Dashboard
- Visualisasi Python (Matplotlib / Seaborn)
- Dashboard interaktif di Excel

---

## 🛠️ Tools & Library

| Tool | Kegunaan |
|---|---|
| **Python 3.x** | Bahasa pemrograman utama |
| **Jupyter Notebook** | Environment analisis |
| **Pandas** | Manipulasi & analisis data |
| **NumPy** | Komputasi numerik |
| **Matplotlib** | Visualisasi data |
| **Seaborn** | Visualisasi statistik |
| **Microsoft Excel** | Dashboard & laporan |

---

## 📊 Output & Hasil

- **Jupyter Notebook** — Analisis lengkap beserta visualisasi
- **Dashboard Excel** — Ringkasan visual performa bisnis
- **Insight & Rekomendasi** — Temuan kunci dan saran strategis

---

## 🚀 Cara Menjalankan Project

### Prasyarat
Pastikan Python dan library berikut sudah terinstal:

```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
```

### Menjalankan Notebook

```bash
# Clone repository
git clone https://github.com/malifhdyh/Capstone-Modul-2.git

# Masuk ke direktori project
cd Capstone-Modul-2

# Jalankan Jupyter Notebook
jupyter notebook
```

Kemudian buka file `notebook/analysis.ipynb` di browser.

---

## 💡 Insight Utama

> *(Diisi setelah analisis selesai)*

- 📈 **Kategori terlaris:** ...
- 💰 **Region paling profitable:** ...
- ⚠️ **Sub-kategori dengan profit negatif:** ...
- 🎯 **Segmen pelanggan dominan:** ...

---

## 👤 Author

**Muhammad Alif Hidayah**  
📧 [GitHub @malifhdyh](https://github.com/malifhdyh)  
🎓 Purwadhika Digital Technology School — Job Connector Data Science & Machine Learning

---

## 📄 Lisensi

Project ini dibuat untuk keperluan akademik sebagai bagian dari program Purwadhika Digital Technology School.

---

*Last updated: March 2026*
