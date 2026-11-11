# 🌍 Gempa Bumi Dunia

Aplikasi web interaktif berbasis **Python dan Streamlit** untuk menampilkan dan memvisualisasikan data gempa bumi dunia berdasarkan kekuatan magnitudo dan lokasi geografis.

Aplikasi ini membantu pengguna memahami persebaran aktivitas gempa bumi melalui informasi statistik, filter magnitudo, dan peta lokasi gempa.

## ✨ Fitur Utama

- **Total Data Gempa** – Menampilkan jumlah keseluruhan data gempa yang tersedia.
- **Magnitudo Terbesar** – Menampilkan nilai magnitudo tertinggi dari dataset.
- **Filter Magnitudo** – Memungkinkan pengguna menyaring data gempa berdasarkan batas magnitudo menggunakan slider.
- **Peta Lokasi Gempa** – Menampilkan persebaran lokasi gempa berdasarkan koordinat latitude dan longitude.
- **Jumlah Gempa Terfilter** – Menampilkan jumlah gempa sesuai kriteria filter yang dipilih.

## 🛠️ Teknologi yang Digunakan

- Python
- Streamlit
- Pandas

## 📁 Struktur Project

```text
gempabumi/
│
├── app.py
├── all_month.csv
├── requirements.txt
└── README.md
```

## ⚙️ Instalasi dan Menjalankan Aplikasi

### 1. Clone Repository

```bash
git clone https://github.com/della436/gempabumi.git
```

### 2. Masuk ke Folder Project

```bash
cd gempabumi
```

### 3. Buat Virtual Environment (Opsional)

```bash
python -m venv venv
```

Aktivasi virtual environment:

**Windows:**
```bash
venv\Scripts\activate
```

**macOS/Linux:**
```bash
source venv/bin/activate
```

### 4. Instal Library

```bash
pip install -r requirements.txt
```

Jika belum memiliki file `requirements.txt`, jalankan:

```bash
pip install streamlit pandas
```

### 5. Jalankan Aplikasi

```bash
streamlit run app.py
```

Aplikasi akan terbuka melalui browser pada alamat lokal Streamlit, biasanya:

```text
http://localhost:8501
```

## 📊 Dataset

Aplikasi menggunakan dataset `all_month.csv` yang berisi informasi kejadian gempa bumi.

Kolom data yang digunakan:

| Kolom | Keterangan |
|---|---|
| `mag` | Magnitudo gempa |
| `latitude` | Garis lintang lokasi gempa |
| `longitude` | Garis bujur lokasi gempa |

Dataset harus berada dalam folder yang sama dengan file `app.py`.

## 🎯 Tujuan Project

Project ini dikembangkan untuk membantu pengguna memperoleh gambaran mengenai aktivitas gempa bumi dunia melalui pengolahan dan visualisasi data secara interaktif.

## 👩‍💻 Pengembang

**Adela Annur Aziiza**

GitHub: [@della436](https://github.com/della436)

---

*Gempa Bumi Dunia – Visualisasi Data Gempa Bumi secara Interaktif.*
