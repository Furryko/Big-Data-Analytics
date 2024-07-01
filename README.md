# Perbandingan Prediksi Harga GPU Termurah Menggunakan KNN dan Deep Learning

## Deskripsi

Penelitian ini bertujuan untuk memprediksi harga terendah GPU berdasarkan harga tertinggi di Amerika serikat, dengan menggunakan metode algoritma K-Nearest Neighbors (KNN) dan deep learning. Untuk dataset yang saya dapatkan dari sumber internet dan saya gunakan untuk penelitian ini yang isinya terdiri dari harga GPU yang di publikasikan di berbagai situs web penjualan hardware komputer. Dataset tersebut di bersihkan, dinormalisasi, dan dibagi menjadi set pelatihan dan pengujian. Model KNN dan deep learning di latih dan di evaluasi menggunakan Mean Absolute Error (MAE). Hasil menunjikan bahwa deep learning lebih baik daripada KNN dalam memprediksi harga terendah.

## Cara Penggunaan

### Menggunakan Jupyter Notebook

1. Clone repositori ini.
2. Instal library yang diperlukan dengan menjalankan perintah `pip install -r requirements.txt`.
3. Buka Jupyter Notebook dengan menjalankan perintah `jupyter notebook`.
4. Buka file notebook `.ipynb` yang ada di repositori ini.
5. Jalankan setiap sel di notebook untuk melihat hasilnya.
6. Pastikan file ` GPU_Price_Index.csv` ada di direktori yang sama dengan notebook.

### Menggunakan Google Colab

1. Import notebook `.ipynb` ke Google Colab.
2. Upload file ` GPU_Price_Index.csv` ke Colab.
3. Google Colab biasanya sudah memiliki banyak library yang diperlukan, namun untuk memastikan semua library terinstal, Anda bisa menjalankan perintah `!pip install -r requirements.txt` di sel pertama.
4. Jalankan setiap sel di notebook untuk melihat hasilnya.

### Menggunakan File `.py`

1. Clone repositori ini.
2. Instal library yang diperlukan dengan menjalankan perintah `pip install -r requirements.txt`.
3. Jalankan skrip dengan perintah `python script_name.py` (ganti `script_name.py` dengan nama file `.py` Anda).
4. Pastikan file ` GPU_Price_Index.csv` ada di direktori yang sama dengan skrip.

## Penulis

- [Rifan Warosy Sirojudin]( https://github.com/Furryko)

## Lisensi

Repositori ini dilisensikan di bawah MIT License.
