# Latihan - Titanic Machine Learning Supervised

## Tentang Dataset Titanic
Dataset Titanic adalah salah satu dataset yang paling populer dan sering digunakan dalam pembelajaran mesin, statistik, dan analisis data. Dataset ini berisi informasi tentang penumpang kapal RMS Titanic, yang tenggelam setelah menabrak gunung es pada tahun 1912. Dataset Titanic sering digunakan sebagai contoh dalam pengajaran dasar-dasar pembelajaran mesin, terutama untuk masalah klasifikasi biner, di mana tujuannya adalah untuk memprediksi apakah seorang penumpang selamat atau tidak berdasarkan fitur-fitur tertentu. Anda dapat mengakses dataset ini di [Kaggle Titanic Competition](https://www.kaggle.com/competitions/titanic).

## Deskripsi Dataset Titanic
Dataset Titanic mencakup beberapa kolom yang mewakili berbagai fitur penumpang, serta kolom target yang menunjukkan apakah penumpang tersebut selamat atau tidak. Berikut adalah deskripsi umum dari kolom-kolom yang sering ditemukan dalam dataset Titanic:

- **PassengerId**: ID unik untuk setiap penumpang.
- **Survived**: Kolom target yang menunjukkan apakah penumpang selamat (1) atau tidak selamat (0).
- **Pclass**: Kelas tiket penumpang (1 = kelas pertama, 2 = kelas kedua, 3 = kelas ketiga).
- **Name**: Nama penumpang.
- **Sex**: Jenis kelamin penumpang (male = laki-laki, female = perempuan).
- **Age**: Usia penumpang (beberapa nilai kosong).
- **SibSp**: Jumlah saudara kandung atau pasangan yang ikut berlayar.
- **Parch**: Jumlah orang tua atau anak yang ikut berlayar.
- **Ticket**: Nomor tiket penumpang.
- **Fare**: Tarif yang dibayar untuk tiket.
- **Cabin**: Nomor kabin penumpang (banyak nilai kosong).
- **Embarked**: Pelabuhan tempat penumpang naik ke kapal (C = Cherbourg, Q = Queenstown, S = Southampton).

## Tujuan Analisis
Dataset Titanic sering digunakan untuk melatih model pembelajaran mesin untuk memprediksi apakah seorang penumpang selamat atau tidak berdasarkan fitur-fitur seperti kelas tiket, jenis kelamin, usia, dan sebagainya. Beberapa tujuan utama analisis dataset Titanic meliputi:

1. **Prediksi Keselamatan**: Menggunakan model klasifikasi untuk memprediksi apakah penumpang selamat atau tidak.
2. **Analisis Eksploratori Data (EDA)**: Memahami distribusi data, mengidentifikasi pola atau korelasi antara fitur, serta menemukan wawasan tentang penumpang dan keselamatan mereka.
3. **Pemodelan dan Evaluasi**: Membangun dan mengevaluasi model pembelajaran mesin seperti Random Forest Classifier, Logistic Regression, XGBoost, dan K-Nearest Neighbors, serta membandingkan kinerja model berdasarkan metrik evaluasi seperti akurasi, presisi, recall, F1-score, dan ROC-AUC.

## Contoh Penggunaan
1. **Visualisasi Data**: Menyusun grafik untuk memperlihatkan perbedaan tingkat keselamatan berdasarkan variabel seperti kelas, jenis kelamin, dan usia.
2. **Feature Engineering**: Mengembangkan fitur baru, seperti mengkategorikan usia (anak-anak, dewasa, manula) atau mengintegrasikan informasi dari beberapa kolom untuk menciptakan variabel baru.
3. **Pembersihan Data**: Menangani nilai yang hilang, menghapus data yang tidak wajar, dan melakukan transformasi untuk meningkatkan kualitas dataset.

## Hasil Analisis
1. **Logistic Regression** memiliki akurasi tertinggi (0.798) dan juga unggul dalam recall, F1-Score, serta ROC AUC, yang menunjukkan kinerja yang seimbang.
2. **Random Forest Classifier** memiliki precision tertinggi (0.810), yang berarti lebih baik dalam meminimalkan prediksi positif palsu.
3. Rincian lengkap hasil dan metrik kinerja untuk setiap model tersedia dalam laporan.

## Kesimpulan
Dataset Titanic memberikan landasan yang ideal untuk memahami konsep dasar dalam analisis data dan pembelajaran mesin, khususnya dalam masalah klasifikasi. Melalui dataset ini, kita dapat mengeksplorasi berbagai teknik mulai dari pembersihan data, analisis eksploratori, hingga pemodelan prediktif. Implementasi berbagai algoritma seperti Random Forest, Logistic Regression, XGBoost, dan K-Nearest Neighbors menunjukkan bagaimana metode yang berbeda dapat dioptimalkan untuk mencapai hasil terbaik.

Selain itu, tantangan seperti penanganan data yang hilang dan fitur kategorikal memberikan wawasan penting dalam mempersiapkan data untuk analisis dunia nyata. Eksplorasi lebih lanjut dengan teknik ensemble atau seleksi fitur dapat meningkatkan kinerja model secara keseluruhan.

---

Jika Anda memiliki saran atau masukan, jangan ragu untuk menghubungi saya melalui [LinkedIn](https://www.linkedin.com/in/jafier-andreas/).
