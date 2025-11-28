# ✈️ Analisis Dampak Pandemi Terhadap Kinerja Operasional Penerbangan AS

**Status:** Completed  
**Tools:** Tableau Public, Microsoft Excel  
**Role:** Data Analyst

## 📌 Business Understanding (Latar Belakang)
Pasca-pandemi COVID-19, industri penerbangan AS mengalami fase pemulihan (*recovery*). Namun, berdasarkan data operasional 2021-2022, ditemukan fenomena anomali dimana **tingkat keterlambatan (*delay*) melonjak drastis** justru saat volume penerbangan belum pulih 100% ke level normal (2019).

Proyek ini bertujuan untuk menginvestigasi fenomena **"Operational Rust"** (Ketidaksiapan Operasional) tersebut dan mencari akar penyebab inefisiensi maskapai.

**Tujuan:**
1. Memvalidasi apakah industri benar-benar sudah pulih atau mengalami kemunduran efisiensi.
2. Mengidentifikasi akar masalah: Apakah faktor Eksternal (*Cuaca*) atau Internal (*Maskapai*) yang dominan.
3. Menentukan maskapai dan periode waktu dengan kinerja terburuk untuk mitigasi risiko.

---

## 🔍 Key Insights (Temuan Utama)
Melalui analisis data historis (2017-2022), ditemukan 4 fakta krusial:

### 1. The Recovery Paradox
Data menunjukkan inefisiensi sistemik. Pada tahun 2022, volume penerbangan masih di bawah tahun 2019, namun **Delay Rate** (Garis Merah) justru meroket hingga **21%**.

<img width="619" height="642" alt="Insight 1" src="https://github.com/user-attachments/assets/28c296e5-e71f-4536-ab62-0701c2af265c" />'

> *Terlihat pola divergensi: Volume (Bar) belum pulih, tapi Delay (Garis) sudah 'overheat'.*

### 2. Root Cause: Internal Failure
Banyak yang menyalahkan cuaca, namun data berkata lain. Delay akibat cuaca (Garis Biru) cenderung stabil, sedangkan **Carrier Delay** (Garis Merah) naik tajam. Masalah utama ada pada manajemen internal maskapai.

<img width="1137" height="642" alt="Screenshot 2025-11-28 105303" src="https://github.com/user-attachments/assets/7da9da4e-6b58-4200-a6e4-7d418da1ac83" />

### 3. "Summer Chaos" 2022
Heatmap menunjukkan bahwa musim panas 2022 (Baris bawah, Juni-Juli) memiliki intensitas delay yang jauh lebih parah ("Merah Pekat") dibandingkan periode yang sama sebelum pandemi.

<img width="1107" height="626" alt="Screenshot 2025-11-28 105411" src="https://github.com/user-attachments/assets/85c32a0e-34a6-4d76-ac56-09149cce0888" />

### 4. Airline Efficiency Gap
Dampak pandemi tidak merata. Grafik ini menyoroti maskapai yang mengalami penurunan efisiensi paling signifikan (batang memanjang ke kanan) di tahun 2022 dibandingkan kinerja mereka sendiri di 2019.

<img width="1112" height="528" alt="Screenshot 2025-11-28 105436" src="https://github.com/user-attachments/assets/69bd030b-5df7-42be-bbd2-5fee5d92c8e1" />

---

## 📂 File Structure
- `Airline_Analysis.twbx`: File Tableau Packaged Workbook berisi dashboard interaktif lengkap.
- `Airplane_DataPreparation.xlsx ` : File hasil data cleaning & preparation.
- `Airline_Delay_Cause.csv`: Dataset mentah yang digunakan (sumber: US Dept. of Transportation).
- `Dashboard Analisis.png` : Dashboard hasil analisis. 

---

## 💡 Rekomendasi Bisnis
1.  **Workforce Restructuring:** Maskapai harus memprioritaskan rekrutmen kru dan teknisi untuk menurunkan *Carrier Delay*, bukan hanya menambah armada pesawat.
2.  **Seasonal Buffer:** Menambahkan buffer waktu (jeda antar penerbangan) khusus di bulan **Juni & Juli** untuk mengantisipasi pola *Summer Chaos*.
3.  **Audit Operasional:** Maskapai dengan *Efficiency Gap* tertinggi (seperti di Insight 4) perlu melakukan audit sistem manajemen antrian bandara.

### 📬 Connect with me
Jika Anda memiliki pertanyaan tentang analisis ini atau ingin berdiskusi, mari terhubung di [LinkedIn Saya](https://www.linkedin.com/in/muiz-isman)
