# Purwadhika-Capstone-Modul--3_E-commerce-Customer-Churn
Proyek ini bertujuan untuk memprediksi churn pelanggan di platform e-commerce menggunakan pendekatan machine learning. Churn pelanggan, atau pelanggan yang berhenti menggunakan layanan, menjadi salah satu tantangan terbesar yang dihadapi perusahaan e-commerce. Dengan prediksi yang akurat, perusahaan dapat mengambil langkah-langkah strategis untuk mempertahankan pelanggan yang berpotensi churn dan meningkatkan loyalitas pelanggan secara keseluruhan.

## Latar Belakang Masalah

Churn pelanggan sering kali dipicu oleh berbagai faktor, seperti ketidakpuasan dengan layanan, persaingan dari platform lain, atau kurangnya keterlibatan. Dalam industri e-commerce yang sangat kompetitif, kehilangan pelanggan tidak hanya berdampak pada pendapatan tetapi juga dapat menurunkan reputasi merek. Oleh karena itu, deteksi dini pelanggan yang mungkin churn sangat penting untuk mempertahankan keberlanjutan bisnis.

## Tujuan

Menganalisis pola perilaku pelanggan dan faktor yang memengaruhi churn.

Mengembangkan model prediksi churn dengan algoritma machine learning.

Mengevaluasi kinerja model menggunakan metrik evaluasi yang relevan.

Memberikan rekomendasi berbasis data untuk strategi retensi pelanggan.

## Fitur Dataset

Dataset yang digunakan dalam proyek ini memiliki fitur-fitur berikut:

CustomerID: Identifikasi unik pelanggan.

Age: Usia pelanggan.

Gender: Jenis kelamin pelanggan.

Purchase Frequency: Jumlah transaksi yang dilakukan oleh pelanggan.

Average Purchase Value: Rata-rata pengeluaran per transaksi.

Account Age: Durasi waktu akun pelanggan telah aktif di platform.

Last Purchase: Waktu sejak pembelian terakhir.

Is Churn: Label biner, 1 jika pelanggan churn, 0 jika tidak.

## Tools

Python: Bahasa pemrograman utama.

Pandas & NumPy: Untuk manipulasi data dan operasi numerik.

Matplotlib & Seaborn: Untuk visualisasi data.

Scikit-learn: Untuk pelatihan model machine learning.

Jupyter Notebook: Untuk pengembangan dan dokumentasi interaktif.

## Langkah Implementasi

1. Persiapan Data

Memuat dataset dari sumber yang tersedia.

Menangani data yang hilang dan outlier.

Menstandarkan fitur numerik untuk pelatihan model.

2. Analisis Data Eksploratif (EDA)

Menyelidiki distribusi data dan pola anomali.

Menggunakan heatmap untuk mengidentifikasi korelasi antara fitur.

Membuat visualisasi distribusi churn berdasarkan fitur-fitur utama.

3. Pengembangan Model

Melatih beberapa algoritma seperti Logistic Regression, Random Forest, dan Gradient Boosting.

Menggunakan teknik validasi silang untuk memastikan model tidak overfitting.

Melakukan tuning hyperparameter menggunakan GridSearchCV.

4. Evaluasi Model

Menggunakan metrik seperti:

Accuracy: Tingkat ketepatan prediksi keseluruhan.

Precision: Ketepatan untuk label churn.

Recall: Kemampuan mendeteksi pelanggan churn.

F1-Score: Harmoni antara precision dan recall.

ROC-AUC: Ukuran kemampuan model membedakan antara churn dan non-churn.

## Kesimpulan

Model terbaik yang dikembangkan menggunakan Random Forest mencapai akurasi 87%, dengan nilai precision 85%, dan ROC-AUC 0.92.

Analisis fitur menunjukkan bahwa "Purchase Frequency" dan "Last Purchase" adalah indikator utama churn.
