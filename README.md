# Penerapan Metode Exponential Smoothing dalam Peramalan Curah Hujan di Kota Pekanbaru Tahun 2018-2023
Penelitian ini melakukan peramalan curah hujan di Kota Pekanbaru menggunakan data bulanan periode Januari 2018–Desember 2023. Data yang digunakan berupa curah hujan dalam satuan mm dan diperoleh dari publikasi BPS Kota Pekanbaru.

Metode yang dibandingkan terdiri dari _Single Exponential Smoothing_ (SES), _Double Exponential Smoothing_ (DES), dan _Triple Exponential Smoothing_ (TES). Ketiga metode tersebut digunakan untuk melihat metode yang paling sesuai dalam memodelkan pola curah hujan.

Hasil analisis menunjukkan bahwa data curah hujan mengalami fluktuasi bulanan yang cukup tinggi, namun secara umum terdapat kecenderungan peningkatan dari tahun ke tahun.

- SES menghasilkan nilai optimal α = 0,1528706 dan memberikan hasil peramalan yang relatif stabil karena adanya proses pelicinan terhadap fluktuasi data.
- DES menghasilkan α = 0,3008092 dan β = 0,2574797. Metode ini mampu mengikuti pola umum data dengan mempertimbangkan komponen _trend_.
- TES menghasilkan α = 0,1264625, β = 0,02809602, dan γ = 0,5177405. Metode ini mampu menangkap pola _level_, _trend_, dan terutama pola musiman curah hujan.

Berdasarkan perbandingan nilai kesalahan, _Triple Exponential Smoothing_ merupakan model terbaik karena menghasilkan nilai RMSE paling rendah, yaitu 107,89142, dibandingkan SES sebesar 117,8657 dan DES sebesar 132,1552. Nilai SSE dan MSE TES juga menjadi yang paling rendah.

Dengan model TES, dilakukan peramalan curah hujan untuk Januari 2024–Desember 2025. Hasilnya menunjukkan adanya pola naik-turun yang konsisten secara musiman, dengan curah hujan diproyeksikan relatif tinggi pada beberapa bulan tertentu, terutama menjelang akhir tahun.

Evaluasi menggunakan MAPE menghasilkan nilai 43,19%, yang berdasarkan kriteria pada laporan termasuk kategori cukup baik. Artinya, model TES cukup mampu menggambarkan pola curah hujan di Kota Pekanbaru.
