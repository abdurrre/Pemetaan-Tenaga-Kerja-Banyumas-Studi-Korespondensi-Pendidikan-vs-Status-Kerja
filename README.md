# 📊 Analisis Kesenjangan Pendidikan & Pekerjaan di Banyumas 2024

![SPSS](https://img.shields.io/badge/Tools-IBM%20SPSS%2025-blue?style=for-the-badge)
![Excel](https://img.shields.io/badge/Tools-Microsoft%20Excel-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

> **Proyek Analisis Data Ketenagakerjaan menggunakan Uji Chi-Square dan Analisis Korespondensi.**

## 📖 Gambaran Proyek (Project Overview)

Proyek ini bertujuan untuk memetakan profil ketenagakerjaan di Kabupaten Banyumas dan menganalisis hubungan antara **Tingkat Pendidikan Terakhir** dengan **Status Pekerjaan Utama**. 

Dilatarbelakangi oleh fenomena *mismatch* (ketidaksesuaian) antara lulusan pendidikan dan kebutuhan pasar kerja, analisis ini memberikan wawasan berbasis data bagi pemerintah daerah untuk merumuskan kebijakan pelatihan kerja yang lebih tepat sasaran.

**Fokus Utama:**
* Menguji signifikansi hubungan antara pendidikan dan status kerja.
* Memvisualisasikan pola asosiasi antar kategori menggunakan peta persepsi (biplot).

## 📂 Dataset

* **Sumber Data:** Publikasi Badan Pusat Statistik (BPS) Kabupaten Banyumas Tahun 2024.
* **Sampel:** 924.757 penduduk usia kerja (15 tahun ke atas).
* **Variabel:**
    * *Pendidikan:* SD ke bawah, SMP, SMA, Perguruan Tinggi.
    * *Status Pekerjaan:* Berusaha Sendiri, Berusaha dibantu buruh, Buruh/Karyawan, Pekerja Bebas, Pekerja Keluarga.

## 🛠️ Metodologi & Tools

Analisis dilakukan menggunakan pendekatan kuantitatif dengan alur sebagai berikut:

1.  **Statistik Deskriptif:** Melihat distribusi frekuensi profil tenaga kerja.
2.  **Uji Chi-Square ($\chi^2$):** Menguji hipotesis independensi antar variabel.
3.  **Cramér's V:** Mengukur kekuatan hubungan (asosiasi) antar variabel.
4.  **Analisis Korespondensi (Correspondence Analysis):** Teknik multivariat untuk memvisualisasikan kedekatan antar kategori dalam ruang dua dimensi.

**Tools:**
* **IBM SPSS Statistics 25**: Pengolahan data statistik utama.
* **Microsoft Excel**: Pra-pemrosesan dan tabulasi data.

## 🔍 Temuan Kunci (Key Findings)

Berdasarkan hasil analisis data, ditemukan beberapa *insight* penting:

### 1. Hubungan yang Signifikan
Terdapat hubungan yang sangat signifikan antara tingkat pendidikan dan pilihan status pekerjaan di Kabupaten Banyumas.
* *Nilai $\chi^2$ Hitung:* **116.585,09** (> $\chi^2$ Tabel 24.996).
* *Kekuatan Hubungan:* **0,205 (Cramér's V)**, yang menunjukkan kategori hubungan "Sedang".

### 2. Pola Asosiasi (Hasil Analisis Korespondensi)
Peta persepsi menunjukkan pengelompokan yang jelas antara jenjang pendidikan dan jenis pekerjaan:

* **Lulusan SD & SMP:** Cenderung bekerja di sektor informal sebagai *Berusaha Sendiri* (Wiraswasta kecil), *Pekerja Bebas*, atau *Pekerja Keluarga*.
* **Lulusan SMA:** Mendominasi sektor formal sebagai *Buruh/Karyawan/Pegawai*.
* **Lulusan Perguruan Tinggi:** Memiliki asosiasi terkuat dengan status *Berusaha dibantu buruh tetap* (Wirausaha skala menengah-besar yang menciptakan lapangan kerja).

## 📈 Visualisasi

![Plot Korespondensi](link-gambar-plot-anda-disini.png)

> *Gambar: Peta Korespondensi menunjukkan kedekatan antara kategori pendidikan (lingkaran biru) dan status pekerjaan (lingkaran merah).*

## 💡 Rekomendasi Kebijakan

Hasil analisis ini menyarankan strategi intervensi yang berbeda untuk setiap jenjang:
1.  **Pendidikan Dasar:** Fokus pada pelatihan keterampilan praktis dan kewirausahaan mikro.
2.  **Pendidikan Tinggi:** Penguatan relevansi kurikulum dengan kebutuhan industri dan dorongan untuk menciptakan lapangan kerja formal.

---

### 👤 Author
**Abdur Rochman Azis**
* Mahasiswa Matematika, Universitas Jenderal Soedirman
* abdure040818@gmail.com

---
*Laporan ini disusun sebagai bagian dari Praktik Kerja Lapangan di Dinas Tenaga Kerja, Koperasi, dan UKM Kabupaten Banyumas (2025).*
