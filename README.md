Pengenalan Digit Tulisan Tangan Hasil Rekap Pemilihan Presiden 2024
Data rekap diambil dari website resmi KPU dengan jumlah 7543 gambar  yang telah disegmentasi.
Metode Ekstraksi Fitur yang Digunakan:
1. Tanpa Ekstraksi Fitur
2. Canny Edge

Metode Pengenalan Pola yang Digunakan:
1. Random Forest
2. KNN
3. Naive Bayes
4. Kmeans Clustering
5. Ensemble

Hasil yang diperoleh dari eksperimen ini dengan proporsi perbandingan data train & data test 60:40	70:30	80:20 ialah sebagai berikut:
1. Tanpa Ekstrasksi Fitur + Random Forest	83%	84%	85%
2. Canny Edge + Random Forest	76%	77%	78%
3. Canny Edge + Random Forest + XGBOOST	77%	77%	79%
4. Tanpa Ekstraksi Fitur + KNN	42%	45%	46%
5. Canny Edge + KNN	15%	14%	15%
6. Tanpa Ekstraksi Fitur + Naive Bayes	51%	52%	49%
7. Canny Edge + Naive Bayes	63%	66%	67%
8. Tanpa Ekstraksi Fitur + Kmeans + Naive Bayes + PCA	84%	81%	81%
9. Canny Edge + Kmeans + Naive Bayes + PCA	88%	85%	87%
10. Canny Edge + Random Forest + XGBOOST + PCA	35%	36%	37%
