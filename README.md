# EDA-Sirkulasi-Perpustakaan
Tugas UTS Data Science - Exploratory Data Analysis Dataset Perpustakaan (Magister Ilmu Komputer Amikom Purwokerto)
# Exploratory Data Analysis (EDA): Pola Peminjaman & Keterlambatan Buku Perpustakaan

**Tugas Ujian Tengah Semester (UTS) - Mata Kuliah Data Science (PSIKS2W002)**
* **Nama:** Arif Tri Wicaksono
* **NIM:** 26MA4D015
* **Program Studi:** Magister Ilmu Komputer, Universitas Amikom Purwokerto

## Deskripsi Proyek
Proyek ini melakukan analisis eksploratif mendalam (Bab 1 - Bab 9) terhadap dataset sirkulasi perpustakaan (`library_data.csv`) untuk memahami pola perilaku peminjaman dan faktor penyebab keterlambatan pengembalian buku (`overdue_status`).

## Struktur Repositori
* `library_data.csv` : Dataset transaksi peminjaman perpustakaan (1.000 baris, 8 fitur).
* `EDA_Perpustakaan.ipynb` : Kode Python lengkap untuk pembersihan data, rekayasa fitur, dan visualisasi grafik.
* `Laporan_EDA_Perpustakaan.pdf` : Laporan tertulis lengkap dari Bab 1 hingga Bab 9.

## Temuan Utama (Key Insights)
* **Tingkat Keterlambatan:** Sebanyak 62,7% transaksi mengalami keterlambatan pengembalian.
* **Ambang Batas Kritis:** Seluruh peminjaman dengan durasi $\le 7$ hari dikembalikan tepat waktu, sedangkan $> 7$ hari berstatus terlambat ($r = 0,83$).
