# Time Series-Deep Learning Approach
Proyek ini bertujuan untuk melakukan analisis data time series pada konsumsi energi menggunakan pendekatan deep learning, khususnya dengan metode **Long Short-Term Memory (LSTM)**. Data yang digunakan dalam proyek ini adalah data konsumsi energi dari **American Electric Power (AEP)**. LSTM, sebagai jenis Recurrent Neural Network (RNN), dipilih untuk menangani data time series karena kemampuannya dalam mengingat pola jangka panjang yang ada dalam data.

## Tujuan
* Menganalisis pola konsumsi energi dari AEP dengan menggunakan teknik time series forecasting.
* Menerapkan model LSTM untuk memprediksi konsumsi energi di masa depan berdasarkan data historis.
* Mengukur performa model menggunakan metrik evaluasi seperti **Mean Absolute Error (MAE)** dan **Mean Squared Error (MSE)**.

## Langkah-Langkah dalam Proyek Ini
* **Pengumpulan dan Persiapan Data**: Mengimpor data konsumsi energi dari AEP dan melakukan pra-pemrosesan data, termasuk normalisasi dan pembagian data untuk training dan testing.
* **Pembangunan Model LSTM**: Merancang arsitektur model LSTM untuk memprediksi konsumsi energi berdasarkan data historis.
* **Pelatihan dan Evaluasi Model**: Melatih model LSTM dengan data training dan mengevaluasi kinerjanya menggunakan data testing.
* **Prediksi dan Visualisasi**: Menghasilkan prediksi konsumsi energi di masa depan dan memvisualisasikan hasilnya untuk analisis lebih lanjut.
