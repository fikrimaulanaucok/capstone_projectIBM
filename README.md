# 📊 Analisis Tren Fatalitas Penerbangan Global (1970-2021)
**Capstone Project - AI Data Analytics**  
![Aviation Safety]
![alt text](https://drive.google.com/file/d/1gqe9z-M7WIXBV_C4Cqp45U1CQBVvGMtv/view?usp=sharing?raw=true)

## 📌 Gambaran Proyek
Analisis ini mengeksplorasi data fatalitas penerbangan global selama 50+ tahun untuk mengidentifikasi:
- Pola penurunan angka kecelakaan
- Periode kritis dalam sejarah penerbangan
- Proyeksi keselamatan udara hingga 2030
- Rekomendasi berbasis data untuk industri penerbangan

## 🔗 Link Terkait
- [Google Colab Notebook](https://colab.research.google.com/drive/1u1uxMoKKoO822ri1sN-fbKXjIdAW20Bm?usp=sharing)
- [Dataset Asli](https://ourworldindata.org/grapher/aviation-fatalities-per-million-passengers)


## 🔍 Temuan Kunci
### 1. Tren Temporal
- Penurunan **96%** fatalitas sejak 1970 (4.76 → 0.05 per juta penumpang)
- 3 titik ekstrim:
  - Puncak: 1973 (5.65)
  - Terendah: 2017 (0.01)
  - Lonjakan terakhir: 2014 (0.29)

### 2. Analisis Dekade
| Dekade  | Rata-rata    | Penurunan vs 1970-an |
|-------- |----------    |----------------------|
| 1970-an | 3.38         |         -            |
| 1980-an | 1.72         | ▼ 49%                |
| 1990-an | 0.99         | ▼ 71%                |
| 2000-an | 0.39         | ▼ 88%                |
| 2010-an | 0.13         | ▼ 96%                |

### 3. Prediksi 2030
Model regresi linear memproyeksikan:
- **0.02-0.04** fatalitas/juta penumpang
- Akurasi model (R²): 0.87

## 🤖 Peran AI/ML
| Teknologi            | Fungsi                 | Contoh Implementasi                    |
|----------------------|------------------------|----------------------------------------|
| **Scikit-learn**     | Regresi Linear         | Prediksi tren jangka panjang           |
| **Plotly**           | Visualisasi Interaktif | Auto-generate grafik dengan hover info |
| **Pandas Profiling** | EDA Otomatis           | Deteksi anomali & korelasi             |
| **IBM Granite**      | Analisis Lanjutan      | Optimasi parameter model               |
