# Credit_Card_Defaul_Prediction
Pembuatan Model Machine Learning secara Supervised untuk mengembangkan model prediksi credit card default yang efektif, dengan mempertimbangkan variabel yang relevan.

## Fitur-fitur
Fitur utama dalam proyek ini :
- Pra-pemrosesan dan eksplorasi data
- Rekayasa dan seleksi fitur
- Pelatihan dan evaluasi model

## Teknologi yang digunakan
Proyek ini akan menggunakan berbagai alat dan teknologi, termasuk:
- Bahasa pemrograman Python
- Kerangka kerja pembelajaran mesin (Scikit-learn)
- Teknik pra-pemrosesan data
- Model pembelajaran mesin

# Kesimpulan
Pada Objective, tujuan dibuat model ini adalah untuk memprediksi apakah seseorang akan diberikan decline CC warning bulan depan berdasarkan status paymentnya setiap bulan. Dari 7 model yang dibuat, ditemukan bahwa model **Logistic Regression** adalah model yang terbaik karena dapat memprediksi nilai False Positive paling kecil yaitu 26 orang serta memiliki mean score precision pada cross validation paling tinggi yaitu sebesar 0.69. Setelah itu dilakukan Hyperparameter Tuning untuk mengoptimalkan model yang telah dibuat dan didapatkan parameter terbaik adalah `solver` = `saga`, `penalty` = `L1`, dan `C`=0.1 dan dipatakan skor precision terbaiknya 0.71, yang berarti ada peningkatan skor setelah model dilakukan hyperparameter tuning.

Sehingga model ini dapat melakukan prediksi dengan probabilitas benar yaitu 0.71.
