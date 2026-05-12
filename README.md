# Thesis MTI - Syauqi

Notebook dan dataset untuk thesis program Magister Teknologi Informasi (MTI) Syauqi.

## 📋 Deskripsi Proyek

Proyek ini menganalisis data historis harga saham BBCA (PT Bank Central Asia) selama 5 tahun terakhir dengan konteks indikator ekonomi makro Indonesia untuk [deskripsi topik thesis Anda].

## 📊 Dataset

### 1. **bbca_historical_price_5years.csv**
   - Data historis harga saham BBCA
   - Periode: 5 tahun terakhir
   - Kolom: Date, Open, High, Low, Close, Volume

### 2. **ekonomi_makro_indonesia.csv**
   - Indikator ekonomi makro Indonesia
   - Meliputi: GDP, Inflasi, Suku Bunga, Nilai Tukar, dll
   - Periode: Selaras dengan data saham

## 📁 Struktur Repository

```
thesis-MTI-syauqi/
├── 00_data_acquisition.ipynb      # Notebook untuk data acquisition
├── bbca_historical_price_5years.csv # Dataset harga saham BBCA
├── ekonomi_makro_indonesia.csv      # Dataset indikator ekonomi makro
├── requirements.txt                 # Python dependencies
├── .gitignore                       # Git ignore rules
├── README.md                        # File ini
└── LICENSE                          # MIT License
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- Jupyter Notebook atau JupyterLab

### Setup

1. **Clone repository**
   ```bash
   git clone https://github.com/syauqidamario/thesis-MTI-syauqi.git
   cd thesis-MTI-syauqi
   ```

2. **Buat virtual environment** (recommended)
   ```bash
   python -m venv venv
   
   # Untuk Linux/Mac:
   source venv/bin/activate
   
   # Untuk Windows:
   venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Jalankan Jupyter**
   ```bash
   jupyter notebook
   ```

5. **Buka notebook**
   - Buka `00_data_acquisition.ipynb` di Jupyter interface

## 📝 Notebooks

### 00_data_acquisition.ipynb
Notebook untuk akuisisi dan eksplorasi data awal:
- Membaca dataset CSV
- Exploratory Data Analysis (EDA)
- Data cleaning dan preprocessing
- Visualisasi data

## 🔄 Workflow Development

Saat melakukan development:

1. Buat branch baru untuk fitur/analisis baru
   ```bash
   git checkout -b feature/nama-fitur
   ```

2. Commit dengan pesan yang jelas
   ```bash
   git commit -m "Add: deskripsi perubahan"
   ```

3. Push ke repository
   ```bash
   git push origin feature/nama-fitur
   ```

4. Buat Pull Request untuk review

## 📦 Dependencies

Lihat `requirements.txt` untuk daftar lengkap. Library utama:
- **pandas**: Data manipulation
- **numpy**: Numerical computing
- **matplotlib/seaborn**: Visualization
- **jupyter**: Interactive notebooks
- **scikit-learn**: Machine learning (jika diperlukan)

## 📄 License

Project ini menggunakan MIT License. Lihat file `LICENSE` untuk detail.

## ✍️ Author

**Syauqi**
- GitHub: [@syauqidamario](https://github.com/syauqidamario)

---

*Last updated: 2026-05-12*
