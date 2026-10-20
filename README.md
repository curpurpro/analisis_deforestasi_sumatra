# analisis_deforestasi_sumatra

# Analisis Kehilangan Tutupan Pohon di Sumatra

## Deskripsi Proyek

Proyek ini menganalisis perubahan kehilangan tutupan pohon di wilayah Sumatra pada periode 2001–2025 menggunakan Python dan Google Earth Engine. Hasil analisis disajikan dalam bentuk tabel, grafik tren tahunan, dan visualisasi spasial.

Proyek ini dibuat sebagai studi kasus penerapan pengolahan data geospasial, komputasi awan, dan visualisasi data untuk mendukung analisis lingkungan.

## Tujuan

- Menganalisis estimasi kehilangan tutupan pohon dari tahun ke tahun.
- Memvisualisasikan tren kehilangan tutupan pohon di Sumatra.
- Menampilkan distribusi spasial kehilangan tutupan pohon.
- Memahami penerapan komputasi awan dalam pengolahan data geospasial berskala besar.

## Teknologi

- Python
- Google Colab
- Google Earth Engine
- geemap
- Pandas
- Matplotlib

## Sumber Data

Hansen Global Forest Change, tersedia melalui Google Earth Engine dengan ID dataset:

`UMD/hansen/global_forest_change_2025_v1_13`

## Cara Menjalankan

1. Buka notebook `analisis_deforestasi_sumatra.ipynb` menggunakan Google Colab.
2. Pasang pustaka yang dibutuhkan.
3. Autentikasi dan inisialisasi Google Earth Engine menggunakan akun yang memiliki akses.
4. Jalankan sel kode secara berurutan.
5. Periksa tabel, grafik, dan visualisasi yang dihasilkan.

## Hasil

Hasil proyek mencakup grafik tren tahunan dan visualisasi spasial kehilangan tutupan pohon. File hasil yang telah diekspor tersedia pada folder `hasil/`.

## Keterbatasan

Kehilangan tutupan pohon tidak selalu identik dengan deforestasi permanen. Estimasi luas juga dipengaruhi oleh resolusi analisis, cakupan wilayah, dan metode perhitungan. Hasil perlu divalidasi sebelum digunakan sebagai dasar kesimpulan definitif.

## Hubungan dengan HPC

Proyek ini memanfaatkan infrastruktur komputasi awan Google Earth Engine untuk pemrosesan data geospasial. Pendekatan tersebut berkaitan dengan komputasi berskala besar, tetapi proyek ini tidak melakukan benchmark atau membangun klaster HPC sendiri.

## Lisensi dan Atribusi

Cantumkan atribusi serta ketentuan penggunaan dataset sesuai dokumentasi resmi Hansen Global Forest Change dan Google Earth Engine.
