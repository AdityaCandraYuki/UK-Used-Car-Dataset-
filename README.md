# UK Used Car Dataset
# **Business Problem Understanding** 
# Latar Belakang
Negara Inggris adalah salah satu pasar mobil terbesar di Eropa, sebagai salah satu pasar mobil terbesar di Eropa, diketahui juga bahwa masyarakat Inggris masih melirik pasar mobil bekas. Salah satu mengapa masyarakat Inggris menyukai mobil bekas adalah regulasi inspeksi kepemilikan mobil di Inggris yang ketat, sebagai hasilnya calon pembeli mendapatkan mobil bekas dengan kualitas yang baik dengan harga yang lebih terjangkau.

Sebuah perusahaan e-Commerce bernama E-autoevolution (sebuah perusahaan fiktif) yang bergerak di bisnis jual-beli mobil bekas di Inggris, ingin menganalisa tren penjualan-pembelian mobil bekas dan membuat model prediksi machine learning harga secara akurat untuk meminimalisir risiko overpricing dan underpricing yang akan membuat user e-commerce percaya akan kredibilitas paltform perusahaan klien.

# Pernyataan Masalah
Salah satu tantangan bagi platform ini adalah menentukan harga yang akurat sehingga user calon pembeli maupun penjual dapat puas terhadap rekomendasi yang ditawarkan platform. Mekanisme penjualan adalah penjual mobil bekas akan menginput fitur-fitur yang akan mempengaruhi harga jual mobilnya. Hasil tersebut akan menjadi acuan terhadap penjual dalam menentukan harga jualnya nanti.

Untuk mendukung strategi marketing perusahaan, tantangan bagi platform ini ada analisis data terhadap fitur-fitur mobil bekas yang paling diminati oleh konsumen dan mengikuti tren yang sedang berkembang di pasar mobil bekas. Selain itu, platform dapat memberikan rekomendasi harga jual yang menarik berdasarkan fitur mobil bekas dan data penjualan di pasar saat ini. Sehingga platform dapat menarik lebih banyak konsumen untuk menggunakan layanan ini dan memberikan kepuasan bagi penjual dan pembeli mobil bekas.

** *Goals*
Berdasarkan permasalahan tersebut, kami akan menganalisis tren pembelian mobil bekas di Inggris Raya. Sehingga platform dapat melakukan strategi marketing yang tepat untuk menarik calon penjual dan calon pembeli.

Selain itu, tujuan lainnya adalah membangun sebuah model machine learning yang dapat memprediksi harga mobil bekas di Inggris secara akurat sebagai alat rekomendasi dan perbandingan harga. kami ingin memastikan bahwa:

Calon pembeli mendapatkan harga yang adil dan wajar
penjual ingin memaksimalkan keuntungan dengan menetapkan harga yang tepat
Pendekatan Analitik
Analisis Deskriptif: Informasi dasar tentang dataset seperti jumlah data, jumlah kolom, tipe data pada setiap kolom, nilai minimum dan maksimum pada setiap kolom, serta nilai rata-rata pada kolom numerik
Analisis Korelasi: Informasi mengenai hubungan antara variabel-variabel pada dataset.
Maka, yang diperlukan untuk dapat menentukan harga jual mobil bekas yang tepat adalah melakukan analisa data untuk mengeksplorasi dan melihat pola pada data serta membangun model regresi sebagai suatu metode untuk menguji ada tidaknya pengaruh antara fitur dengan harga jual mobil bekas. Model-model regresi yang akan kami bandingkan melihat dari tingkat kekuratannya sehingga hasilnya akan menjadi acuan penjual mobil bekas dalam menjual mobilnya.

# Evaluasi Metrik
Evaluasi Metrik dilakukan untuk mengukur kinerja model atau algoritma yang dibangun berdasarkan fitur-fitur tersebut.

Evaluasi Metrik yang digunakan untuk model regresi adalah RMSE, MAE, dan MAPE. Selanjutnya R2 dan Adjusted R2.

Root Mean Square Error (RMSE): Mengukur kesalahan rata-rata dalam prediksi harga mobil dengan mempertimbangkan variansi kesalahan. semakin rendah nilai RMSE, semakin baik performa model.
Mean Absolute Error (MAE): Mengukur kesalahan rata-rata dalam prediksi harga mobil. Semakin rendah nilai MAE, semakin baik performa model.
Mean Absolute Percentage Error (MAPE): Mengukur kesalahan rata-rata dalam prediksi harga mobil dengan hasil yang berbentuk presentase dari harga aktual. semakin renah nilai MAPE, semakin baik performa model.
R-squared (R2): mengukur seberapa baik model dapat menjelaskan variasi dalam data. Nilai R2 berkisar antara 0 hingga 1, dan semakin mendekati 1, semakin baik performa model.
