# 📊 Training Data Analytics & Visualization: PT. X (2020–2025)

🔗 **Dashboard Link**:  
[Klik untuk membuka dashboard](https://datastudio.google.com/reporting/88460ec4-8fd5-44af-9532-315d2455b862)

🔗 **Insight Presentation Link**:  
[Klik untuk membuka presentasi](canva.link/DashboardInsightLink)

Proyek ini bertujuan untuk menganalisis efektivitas, distribusi, dan tren biaya program pelatihan di PT. X selama periode lima tahun. Analisis ini memberikan gambaran strategis bagi manajemen HR dalam mengoptimalkan anggaran dan partisipasi karyawan di masa depan.

---

## 🛠️ Tahap 1: Data Preprocessing

Sebelum visualisasi dilakukan, data mentah (raw data) melalui proses transformasi untuk memastikan akurasi analisis:

1. **Data Cleaning**  
   Menghapus entri duplikat pada nama peserta dan memastikan konsistensi penulisan nama unit kerja (misal: "Pemasaran" vs "Marketing").

2. **Handling Missing Values**  
   Mengisi atau mengeliminasi data biaya yang kosong untuk memastikan perhitungan *rata-rata biaya per karyawan* tetap akurat.

3. **Standardisasi Format**  
   Menyeragamkan format tanggal untuk analisis tren tahunan dan mengonversi nilai biaya ke dalam satuan miliar (B) dan jutaan (M) agar lebih mudah dibaca.

4. **Feature Engineering**  
   Menghitung variabel baru seperti *Realisasi vs Sisa Anggaran* dan *Rata-rata Jam per Karyawan* untuk mendapatkan metrik efisiensi.

---

## 🎨 Tahap 2: Data Visualization

Dashboard dirancang dengan pendekatan modern dan berfokus pada keterbacaan data melalui elemen visual berikut:

1. **Overview Cards**  
   Menggunakan indikator persentase kenaikan/penurunan dibanding tahun sebelumnya untuk memberikan konteks performa secara instan.

2. **Doughnut Chart**  
   Digunakan untuk memantau realisasi anggaran (83.3%) dan menampilkan proporsi sisa dana secara visual.

3. **Combo & Line Charts**  
   Memetakan tren historis 5 tahun untuk mengidentifikasi anomali antara pertumbuhan jumlah pelatihan dan penurunan partisipasi peserta.

4. **Horizontal Bar Chart**  
   Menampilkan peringkat unit kerja dan jabatan teraktif untuk memudahkan identifikasi target pengembangan kompetensi.

---

## 💡 Tahap 3: Insight & Analisis

### 🔹 Analisis Operasional (2025)

- **Fokus Manajerial**  
  Pelatihan tahun ini didominasi oleh level Manager (157 peserta), menunjukkan arah kebijakan perusahaan yang berfokus pada penguatan kepemimpinan.

- **Dominasi Program**  
  Program *Pembekalan dan Sertifikasi Keahlian* menjadi prioritas utama dengan total 104 topik, mencerminkan komitmen perusahaan terhadap standar kompetensi formal.

---

### 🔹 Analisis Tren & Biaya (2020–2025)

- **Penurunan Efisiensi Partisipasi**  
  Terjadi penurunan jumlah peserta sebesar 18% di tahun 2025 dibandingkan tahun sebelumnya, meskipun jumlah program pelatihan tetap stabil.

- **Dinamika Anggaran**  
  Realisasi biaya di tahun 2025 berada di bawah plafon anggaran 35B setelah sempat mengalami *overbudget* pada tahun 2024.

- **Konsistensi Durasi**  
  Rata-rata jam pelatihan per karyawan tetap stabil di angka 16.78 jam, menunjukkan kualitas durasi pelatihan tetap terjaga.

---

## 🧰 Tools

- **Data Processing**: Google Sheets  
- **Data Visualization**: Google Looker Studio  
