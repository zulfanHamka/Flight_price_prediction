# Prediksi Harga Tiket Pesawat Menggunakan Machine Learning

## Deskripsi
Proyek ini bertujuan untuk menganalisis dan memprediksi harga tiket pesawat berdasarkan berbagai fitur seperti maskapai, kota asal dan tujuan, waktu keberangkatan dan kedatangan, jumlah transit, kelas penerbangan, durasi perjalanan, serta waktu pemesanan sebelum keberangkatan. Berbagai teknik machine learning diterapkan untuk menemukan model dengan akurasi terbaik.

## Tahapan Analisis
1. **Load dan Eksplorasi Dataset**
   - Memuat dataset dari Google Drive.
   - Melihat struktur data dan melakukan pembersihan data.

2. **Preprocessing Data**
   - Encoding fitur kategorikal menggunakan OneHotEncoder.
   - Normalisasi fitur numerik menggunakan StandardScaler.
   - Menghapus nilai yang hilang (missing values).

3. **Eksplorasi Data (EDA)**
   - Visualisasi distribusi harga tiket.
   - Analisis korelasi antara fitur numerik dan harga tiket.

4. **Pembangunan Model dan Evaluasi**
   - Model yang digunakan:
     - **Linear Regression**
     - **Artificial Neural Network (ANN)**
     - **Polynomial Regression**
     - **Random Forest Regression**
     - **K-Nearest Neighbors (KNN)**
   - Evaluasi performa model berdasarkan **Mean Absolute Error (MAE), Mean Squared Error (MSE), dan R-squared (R²).**

5. **Hasil dan Interpretasi**
   - Model terbaik dipilih berdasarkan performa evaluasi.
   - Analisis residual dan fitur yang paling berpengaruh terhadap harga tiket.

## Model Performance Metrics

### Linear Regression Metrics:
- **Mean Absolute Error:** 1721.9493192261361
- **Mean Squared Error:** 5529151.375753342
- **R-squared:** 0.5868427883112715

### Artificial Neural Network Metrics:
- **Mean Absolute Error:** 1015.8424445602678
- **Mean Squared Error:** 2886041.956685592
- **R-squared:** 0.7843450166928303

### Polynomial Regression Metrics:
- **Mean Absolute Error:** 1161.9804604049316
- **Mean Squared Error:** 6363123.545286392
- **R-squared:** 0.524525518847234

### Random Forest Regression Metrics:
- **Mean Absolute Error:** 413.25332070804666
- **Mean Squared Error:** 1190258.5382315065
- **R-squared:** 0.9110597874022885

### K-Nearest Neighbors Regression Metrics:
- **Mean Absolute Error:** 804.2119965989024
- **Mean Squared Error:** 2803187.906438896
- **R-squared:** 0.7905361563543627

## Kesimpulan
- Model **Random Forest Regression** memberikan performa terbaik dengan nilai **R² sebesar 0.911**, menunjukkan kemampuan prediksi yang tinggi dibandingkan model lainnya.
- Model **Artificial Neural Network** juga memiliki performa yang cukup baik dengan **R² sebesar 0.784**.
- Model **Polynomial Regression** menunjukkan performa paling rendah dengan **R² sebesar 0.524**, yang menunjukkan overfitting pada data pelatihan.

Proyek ini dapat dikembangkan lebih lanjut dengan penambahan fitur baru, peningkatan teknik preprocessing, serta eksplorasi model yang lebih kompleks untuk meningkatkan akurasi prediksi.

