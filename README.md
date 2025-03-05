# Praktikum_AI_Workflow
Tugas Mengimpelentasikan Scikit-Learn

# Deskripsi Proyek
Program di atas adalah contoh analisis data penjualan menggunakan Python dengan beberapa langkah utama:

1. Pembacaan Data: Program membaca data penjualan dari file CSV dan menampilkan 10 baris pertama data tersebut.
2. Pembersihan dan Transformasi Data:
   - Mengecek data yang kosong.
   - Mengubah format kolom "Tanggal" menjadi datetime.
   - Menambahkan kolom "Total Penjualan" yang dihitung dari jumlah terjual dikali harga satuan.
   - Menambahkan kolom "Keuntungan" dengan asumsi modal Rp 10.000 per produk.
3. Pembuatan Model Prediksi:
   - Menggunakan algoritma Decision Tree untuk memprediksi apakah suatu produk perlu di-restok berdasarkan jumlah terjual dan stok.
   - Data dibagi menjadi data latih dan data uji.
   - Model dievaluasi menggunakan akurasi.
4. Prediksi Restok:
   - Contoh prediksi untuk produk baru dengan jumlah terjual 8 dan stok 3.
   - Menampilkan pesan apakah produk perlu di-restok atau tidak.
5. Visualisasi Data:
   - Membuat scatter plot untuk menganalisis hubungan antara jumlah terjual, stok, dan keuntungan.
   - Warna titik menunjukkan tingkat keuntungan.
jadi dalam program ini bisa menghitung menganalisis dan memprediksi kebutuhan restok dan bisa memvisualisasikan data yang sudah diolah.

# Cara Menjalankan Kode
Unduh File Raw praktikum_ai.ipynb 
kemudian Upload di google colab dengan klik File-> Upload NoteBook -> pilih filenya -> Enter
lalu tambahkan File data_penjualan_latihan.csv ke dalam google colabss
Lalu jalankan tiap kodenya.
