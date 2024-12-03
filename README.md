# Analisis Data Ekonomi Dunia: PCA, K-Means, dan GMM

Repositori ini berisi notebook dan kode Python yang digunakan untuk analisis data ekonomi dunia dengan berbagai metode clustering dan optimasi, termasuk PCA (Principal Component Analysis), K-Means, dan Gaussian Mixture Model (GMM). 

## Struktur File
1. **worldEcon.ipynb**  
   Notebook ini mencakup:
   - Eksplorasi data ekonomi global.
   - Pembersihan data, termasuk penanganan *missing values* dan normalisasi data.
   - *Feature selection* untuk memilih fitur-fitur terbaik.
   - Analisis PCA untuk reduksi dimensi.
   - Implementasi algoritma K-Means untuk clustering.
   - Evaluasi model K-Means menggunakan metrik *silhouette score*.

2. **gmm.ipynb**  
   Notebook ini mencakup:
   - Penerapan Gaussian Mixture Model (GMM) untuk clustering data ekonomi.
   - Eksperimen tuning parameter GMM secara luas untuk menemukan konfigurasi terbaik.
   - Penggunaan *GridSearchCV* untuk mempermudah pencarian parameter optimal.
   - Evaluasi GMM menggunakan metrik *silhouette score*.

## Fitur Utama
- **PCA**  
  Digunakan untuk mengurangi dimensi dataset dan mempercepat pemrosesan model clustering.

- **K-Means Clustering**  
  - Implementasi menggunakan beberapa jumlah cluster untuk menemukan konfigurasi terbaik.
  - Evaluasi menggunakan *silhouette score*.

- **Gaussian Mixture Model (GMM)**  
  - Eksperimen dengan berbagai parameter seperti jumlah komponen, tipe kovarians, dan *regularization*.
  - Evaluasi model dengan *silhouette score*.

- **Tuning Parameter**  
  *GridSearchCV* digunakan untuk eksperimen parameter model yang lebih efisien.

## Prasyarat
Sebelum menjalankan notebook ini, pastikan Anda telah menginstal pustaka berikut:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Cara Penggunaan
1. Clone repositori ini ke komputer Anda.
2. Pastikan semua dependensi yang disebutkan di atas sudah terinstal.
3. Jalankan notebook `worldEcon.ipynb` untuk eksplorasi awal data dan penerapan K-Means dengan PCA.
4. Jalankan notebook `gmm.ipynb` untuk eksperimen dengan Gaussian Mixture Model.

## Evaluasi Model
- **K-Means Clustering**  
  Model ini dievaluasi berdasarkan *silhouette score* untuk menentukan jumlah cluster terbaik.

- **GMM**  
  Model GMM juga dievaluasi dengan *silhouette score* untuk menentukan konfigurasi parameter yang optimal.

## Lisensi
Proyek ini dilisensikan di bawah [MIT License].
