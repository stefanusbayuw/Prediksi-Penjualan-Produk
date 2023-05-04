# Prediksi-Penjualan-Produk

Final Project Hacktiv8

## Background

Dalam project ini saya melakukan prediksi penjualan produk minggu selanjutnya dari Paragon. Data yang saya miliki saya lakukan pemisahan antar setiap SKU yang ada dan melakukan prediksi per produk berdasarkan SKU. Saya menggunakan Random Forest Regressor untuk melakukan prediksi penjualan produk minggu selanjutnya.

Pada model yang dibuat saya melakukan prediksi terhadap 2 produk awal berdasarkan urutan data yang saya terima. Model Random Forest Regressor yang saya buat meggunakan n_job = 6 dan n_estimator = 25 yang menghasilkan metric MAPE sebesar 0.632 pada training dan MAPE sebesar 3.34 pada Testing. Model yang dibuat underfitting karena data yang terlalu kompleks sehingga model tidak dapat mempelajari pola dengan baik.

Model dapat memprediksi penjualan minggu selanjutnya yaitu dengan prediksi penjualan pada minggu setelahnya pada data produk pertama yaitu pada minggu ke 15-2023 yaitu terjual 3 produk dan pada minggu 16-2023 dengan penjualan sebanyak 16 produk.

Untuk pengembangan kedepan dapat dilakukan pemodelan menggunakan algoritme regressor lainnya dan menggunakan metric untuk mengukur akurasi model dengan metric lainnya.
