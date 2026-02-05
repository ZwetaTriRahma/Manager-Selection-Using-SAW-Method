# Manager Selection Using Simple Additive Weighting - SPK

Aplikasi Sistem Pendukung Keputusan (SPK) menggunakan metode **Simple Additive Weighting (SAW)** yang dibangun dengan Streamlit.

## 📸 Tampilan
![image](https://github.com/ZwetaTriRahma/Manager-Selection-Using-SAW-Method/blob/9610633685c01ecb9d36b3e37b03f4e30d7c433d/SPK1.png)
![image](https://github.com/ZwetaTriRahma/Manager-Selection-Using-SAW-Method/blob/9610633685c01ecb9d36b3e37b03f4e30d7c433d/SPK2.png)
![image](https://github.com/ZwetaTriRahma/Manager-Selection-Using-SAW-Method/blob/9610633685c01ecb9d36b3e37b03f4e30d7c433d/SPK3.png)


## 📋 Daftar Isi
- [Tentang Proyek](#tentang-proyek)
- [Fitur](#fitur)
- [Instalasi](#instalasi)
- [Cara Penggunaan](#cara-penggunaan)
- [Struktur Proyek](#struktur-proyek)
- [Teknologi](#teknologi)
- [Tim](#tim)

## 📖 Tentang Proyek

Aplikasi ini adalah implementasi sistem pendukung keputusan berbasis web yang menggunakan metode SAW (Simple Additive Weighting). SAW adalah salah satu metode Multi-Criteria Decision Making (MCDM) yang menggabungkan beberapa kriteria untuk membantu dalam pengambilan keputusan.

## ✨ Fitur

- 🎯 Interface yang modern dan responsif
- 📊 Analisis data multi-kriteria
- 🔢 Perhitungan otomatis metode SAW
- 📈 Visualisasi hasil dalam bentuk grafik
- 🎨 Desain yang menarik dengan gradient styling
- 💾 Input data yang fleksibel

## 🚀 Instalasi

### Prerequisites
- Python 3.8 atau lebih tinggi
- pip (Python package manager)

### Langkah Instalasi

1. Clone repository
```bash
git clone https://github.com/ZwetaTriRahma/Manager-Selection-Using-SAW-Method.git
cd SPKSAWMETHODE
```

2. Buat virtual environment (opsional tapi direkomendasikan)
```bash
python -m venv venv
source venv/Scripts/activate  # Windows
# atau
source venv/bin/activate  # Linux/Mac
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## 💻 Cara Penggunaan

1. Jalankan aplikasi
```bash
streamlit run app.py
```

2. Aplikasi akan membuka di browser default Anda 

3. Ikuti langkah-langkah pada aplikasi untuk:
   - Input data alternatif dan kriteria
   - Tentukan bobot setiap kriteria
   - Pilih jenis kriteria (benefit/cost)
   - Lihat hasil perhitungan SAW
   - Analisis visualisasi data

## 📁 Struktur Proyek

```
SPKSAWMETHODE/
├── app.py              # File utama aplikasi
├── README.md           # Dokumentasi ini
└── .git/               # Git repository
```
## 🛠️ Teknologi

- **Streamlit** - Framework untuk membuat web app interaktif
- **Pandas** - Data manipulation dan analisis
- **NumPy** - Komputasi numerik
- **Matplotlib** - Visualisasi data dan grafik


## 📝 Lisensi

Proyek ini bersifat edukatif dan dikembangkan untuk tujuan pembelajaran.




