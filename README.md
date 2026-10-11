# Analisis Statistika Deskriptif Harga Rumah di Jakarta Selatan

**Tugas Statistika dan Probabilitas | Kelompok 06 | Kelas 3TIF**

## Deskripsi
Proyek ini menganalisis harga, luas tanah, dan luas bangunan rumah di Jakarta Selatan menggunakan statistika deskriptif. Analisis dilakukan dengan Python (library **Pandas**) di Google Colab, sesuai materi Lembar Perkuliahan Pertemuan 4.

## Anggota Kelompok
| No | Nama | NIM |
|----|------|-----|
| 1 | Adenia Faridhotul Musthofa | 2455301211 |
| 2 | Arta Lita Sihombing | 2455301215 |
| 3 | Wulandari | 2455301240 |

**Dosen Pengampu:** Mona Elviyenti, S.Si., M.Si.

## Dataset
- **File:** `HARGA_RUMAH_JAKSEL.xlsx`
- **Sumber:** Kaggle ([tambahkan link dataset])
- **Jumlah data:** 1.001 baris, menjadi 931 baris setelah 70 data duplikat dihapus

| Kolom | Keterangan |
|-------|------------|
| `HARGA` | Harga rumah (Rupiah) |
| `LT` | Luas tanah (m²) |
| `LB` | Luas bangunan (m²) |
| `JKT` | Jumlah kamar tidur |
| `JKM` | Jumlah kamar mandi |
| `GRS` | Ketersediaan garasi (ADA / TIDAK ADA) |
| `KOTA` | Kota (JAKSEL) |

## Isi Analisis
1. **Pengorganisasian data**: pembersihan data dan tabel frekuensi (garasi, kelas harga, JKT, JKM)
2. **Penyajian data**: grafik batang, pie chart, grafik garis, histogram, dan boxplot
3. **Statistika deskriptif** untuk harga, LT, dan LB:
   - Ukuran pemusatan: mean, median, modus
   - Ukuran penyebaran: standar deviasi, varians, range, min, max, IQR
   - Kuartil (Q1, Q2, Q3)
   - Bentuk distribusi: skewness dan kurtosis
4. **Deteksi outlier** dengan aturan 1,5 × IQR
5. **Perbandingan harga** menurut ketersediaan garasi

## Cara Menjalankan
1. Buka file `3TIF_06_StatistikaDeskriptif_HargaRumahJaksel.ipynb` di [Google Colab](https://colab.research.google.com/).
2. Unggah `HARGA_RUMAH_JAKSEL.xlsx` lewat panel **Files** di sebelah kiri Colab.
3. Jalankan semua sel secara berurutan (**Runtime → Run all**).

## Struktur Repository
```
├── README.md
├── HARGA_RUMAH_JAKSEL.xlsx
└── 3TIF_06_StatistikaDeskriptif_HargaRumahJaksel.ipynb
```

## Teknologi
- Python 3
- Pandas
- Google Colab
