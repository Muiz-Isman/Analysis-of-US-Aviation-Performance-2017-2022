# ✈️ Analisis Dampak Pandemi Terhadap Kinerja Operasional Penerbangan AS

![Dashboard Preview](<img width="1599" height="740" alt="Dashboard Analisis" src="https://github.com/user-attachments/assets/d445e51f-ffce-4f36-8f5b-bdb2644c156a" />)
> *Tampilan Penuh Dashboard Analisis (Klik link di bawah untuk versi interaktif)*

## 🔗 [LIHAT DASHBOARD INTERAKTIF (TABLEAU PUBLIC)](MASUKKAN_LINK_TABLEAU_PUBLIC_KAMU_DISINI)

---

## 📌 Executive Summary
Industri penerbangan Amerika Serikat mengalami guncangan hebat akibat pandemi COVID-19. Setelah masa hening di tahun 2020, industri mulai bangkit pada 2021-2022 (*Revenge Travel*). Namun, data menunjukkan adanya anomali serius: **Tingkat keterlambatan (Delay Rate) justru melonjak melebihi era sebelum pandemi, meskipun volume penerbangan belum pulih sepenuhnya.**

Proyek ini menganalisis fenomena **"Operational Rust"** (Ketidaksiapan Operasional)—di mana maskapai kesulitan menangani lonjakan permintaan pasca-tidur panjang pandemi.

---

## 🔍 Temuan Utama Berbasis Data (Key Insights)

Analisis ini menggunakan data penerbangan tahun 2017-2022 untuk membuktikan 4 hipotesis utama:

### 1. Paradoks Pemulihan: Volume Belum Pulih, Delay Meroket
Terdapat inefisiensi sistemik yang nyata. Pada tahun 2022, volume penerbangan (batang abu-abu) masih berada di bawah level tahun 2019. Namun ironisnya, garis merah (**Delay Rate**) justru melonjak tajam menembus angka **21%**, lebih tinggi dibandingkan saat lalu lintas udara padat di 2019 (18%).

![Inefficiency Chart](<img width="310" height="321" alt="image" src="https://github.com/user-attachments/assets/1f8ba0c4-4ced-4cd8-a90a-47766b897a1e" />)

### 2. Akar Masalah: Kegagalan Internal Maskapai (Bukan Cuaca)
Banyak spekulasi bahwa keterlambatan disebabkan oleh cuaca ekstrem. Namun, grafik di bawah membantah hal tersebut.
* **Garis Biru (Weather Delay):** Cenderung stabil dan landai.
* **Garis Merah (Carrier Delay):** Mengalami lonjakan drastis pada fase pemulihan (2021-2022).
Ini membuktikan bahwa penyebab utama kekacauan adalah faktor internal maskapai (kekurangan kru, masalah teknis, atau manajemen armada).

![Root Cause Chart](<img width="569" height="321" alt="image" src="https://github.com/user-attachments/assets/0c727822-1523-4872-be9e-841841c9ce26" />)

### 3. "Summer Chaos": Musim Panas 2022 Lebih Buruk dari 2019
Heatmap di bawah memvisualisasikan intensitas keterlambatan. Perhatikan baris tahun 2022 (paling bawah) pada bulan **Juni-Juli** yang berwarna merah pekat. Hal ini menunjukkan bahwa musim panas pasca-pandemi memiliki intensitas delay yang jauh lebih parah dibandingkan periode yang sama sebelum pandemi.

![Seasonal Heatmap](<img width="1107" height="626" alt="image" src="https://github.com/user-attachments/assets/180105d6-0084-4643-8230-0920914f9f3a" />)

### 4. Disparitas Efisiensi Maskapai
Dampak pandemi tidak merata. Grafik ini memperlihatkan maskapai mana yang paling gagal beradaptasi. Batang yang memanjang ke kanan menunjukkan maskapai dengan rata-rata menit keterlambatan internal (*Carrier Delay per Flight*) tertinggi di tahun 2022.

![Airlines Performance](<img width="1112" height="528" alt="Screenshot 2025-11-28 105436" src="https://github.com/user-attachments/assets/c479bd6c-c2c0-4eff-a815-d0eee3c144da" />)

---

## 🛠️ Metodologi & Tools

### Tools yang Digunakan
* **Tableau Desktop:** Untuk visualisasi data interaktif & dashboard layouting.
* **Excel:** Untuk pembersihan data (*Data Cleaning*) dan preparation.

### Teknik Analisis
1.  **Calculated Fields:** Pembuatan metrik kustom seperti `Delay Rate (%)`, `Cancellation Rate (%)`, dan `Avg Carrier Delay (Min/Flight)`.
2.  **Grouping Analysis:** Segmentasi data menjadi 3 fase: *Pre-Pandemic* (<=2019), *Pandemic* (2020), dan *Recovery Phase* (>2020).
3.  **Time-Series & Dual Axis:** Membandingkan tren volume dan kualitas layanan dalam satu kerangka waktu.

---

## 📂 Struktur Repository
* `Airline_Analysis.twbx`: File Tableau Packaged Workbook (Mengandung data & visualisasi lengkap).
* `Airplane_DataPreparation.xlsx` : File excel yang sudah di cleaning & preparation.
* `Airline_Delay_Cause.csv`: Dataset mentah yang digunakan untuk analisis.
* `Dashboard Analisis.png`: Hasil dashboard analisis.

---

### 📬 Kontak & Diskusi
Terima kasih telah melihat portofolio analisis data ini. Jika Anda memiliki pertanyaan atau masukan mengenai analisis ini, silakan hubungi saya.

**Author:** [Nama Kamu]
