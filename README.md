# Superstore Sales & Profit EDA (Python)

Sebuah project **data analysis menggunakan Python** yang berfokus pada proses **Exploratory Data Analysis (EDA)** terhadap dataset *Superstore*.  
Project ini bertujuan untuk memahami **pola penjualan, profitabilitas, serta performa bisnis** melalui proses **data cleaning, analisis, dan visualisasi data**.

Dataset yang digunakan berisi data **sales, profit, discount, product, category, segment, dan region** pada periode **2014–2017**.

Project ini dibuat untuk menghasilkan **insight berbasis data** yang dapat mendukung pengambilan keputusan bisnis.

---

## Project Objectives
- Melakukan exploratory data analysis (EDA) pada dataset Superstore  
- Memahami tren penjualan dan profit dari waktu ke waktu  
- Menganalisis performa kategori dan sub-kategori produk  
- Mengidentifikasi pengaruh diskon terhadap profitabilitas  
- Menentukan region dan produk dengan kontribusi profit tertinggi  
- Menghasilkan insight bisnis berbasis data  

---

## Analysis Overview

Analisis dilakukan menggunakan **Python (Jupyter Notebook)** dengan alur kerja sebagai berikut:

### Data Preparation
- Load dataset dari file CSV  
- Pemeriksaan struktur data dan tipe data  
- Konversi kolom tanggal ke format datetime  
- Pembuatan kolom turunan (Year, Month, Month Name)  
- Pengecekan missing value dan duplikasi data  

---

### Exploratory Analysis
- **Sales & Profit Trend by Year**  
  Analisis tren penjualan dan profit dari tahun ke tahun  
- **Category & Sub-Category Performance**  
  Analisis kontribusi penjualan dan profit berdasarkan kategori dan sub-kategori  
- **Discount vs Profit Analysis**  
  Analisis hubungan tingkat diskon terhadap profit  
- **Regional Performance**  
  Analisis kontribusi profit berdasarkan region  
- **Top Products Analysis**  
  Identifikasi produk dengan kontribusi profit tertinggi  

---

## Key Insights
- Penjualan menunjukkan tren meningkat dari tahun ke tahun, namun profit tidak selalu meningkat secara linear.  
- Kategori **Technology** memberikan kontribusi profit tertinggi dibandingkan kategori lainnya.  
- Beberapa sub-kategori memiliki penjualan tinggi namun profit rendah, yang mengindikasikan margin keuntungan yang kecil.  
- Tingkat diskon yang tinggi cenderung berdampak negatif terhadap profit.  
- Sebagian kecil produk dan region memberikan kontribusi signifikan terhadap total profit.  

---

## Business Recommendations
- Mengoptimalkan strategi diskon dengan membatasi diskon tinggi pada produk dengan margin rendah.  
- Memfokuskan strategi penjualan pada kategori dan sub-kategori dengan kontribusi profit tertinggi.  
- Memperkuat strategi penjualan di region dengan performa profit terbaik.  
- Mengevaluasi produk dengan penjualan tinggi namun profit rendah untuk perbaikan harga atau efisiensi biaya.  

---

## Tools & Technologies

| Layer | Teknologi |
|------|----------|
| Programming Language | Python |
| Data Analysis | Pandas |
| Data Visualization | Matplotlib |
| Environment | Jupyter Notebook |
| Dataset | Superstore |

---

## Project Structure

### `/`
Root folder berisi seluruh file utama project Python EDA:

- `superstore_eda.ipynb`  
  Jupyter Notebook yang berisi seluruh proses EDA mulai dari data cleaning, analisis, visualisasi, hingga insight bisnis  

- `Superstore.csv`  
  Dataset **Sample Superstore** yang digunakan sebagai sumber data analisis  

- `README.md`  
  Dokumentasi project yang menjelaskan tujuan analisis, alur EDA, serta insight dan rekomendasi bisnis  

---

## Skills Demonstrated
- Exploratory Data Analysis (EDA)  
- Data Cleaning & Transformation  
- Data Visualization  
- Business-Oriented Data Analysis  
- Insight & Recommendation Generation  
- Python for Data Analysis  

---

## Author
**Agnesha Riby Tjoanda**  
Informatics Engineering — Universitas Surabaya

---

## License
Project ini dibuat untuk **tujuan pembelajaran dan portofolio**.
