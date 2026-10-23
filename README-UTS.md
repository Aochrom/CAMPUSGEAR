# Hasil Pengujian

|No.|Skenario|Hasil yang Diharapkan|Hasil Aktual|Status (Lulus/Gagal)|
|---|---|---|---|---|
|1|Pencarian nama barang yang tersedia|Barang ditemukan|Barang ditemukan|Lulus|
|2|Pencarian barang yang tidak ada|Pesan tidak ditemukan|Muncul pesan tidak ditemukan|Lulus|
|3|Pencarian dan filter kategori bersamaan|Hasil sesuai kedua kondisi|Hasil muncul sesuai kedua kondisi|Lulus|
|4|Filter barang dengan stok lebih dari 0|Hanya barang tersedia tampil|Hanya barang tersedia tampil|Lulus|
|5|Input NIM kurang dari 8 digit|Ditolak|Submission ditolak|Lulus|
|6|Input jumlah melebihi stok|Ditolak|Submission ditolak|Lulus|
|7|Peminjaman dengan data valid|Transaksi tersimpan dan stok berkurang|Transaksi tersimpan dan stok berkurang|Lulus|
|8|Pembatalan peminjaman|Stok dikembalikan|Stok dikembalikan|Lulus|
|9|Pembatalan transaksi yang sama dua kali|Tidak terjadi pengembalian stok ganda|Tidak memungkinkan terjaadi pembatalan yang sama dua kali|Lulus|
|10|Refresh setelah peminjaman dan pembatalan|Data transaksi dan stok tetap konsisten|Data tetap konsisten|Lulus|  


# Penggunaan Generative AI
Proyek ini melibatkan Generative AI dalam penyelesaiannya.  

- Penyusunan styling menggunakan file `styles.css`.
- Kemampuan laman web dalam menampilkan hasil secara real time menggunakan function `tampilkanRiwayat()`
- Implementasi model DOM pada `main.js`
- Implementasi riwayat peminjaman yang beroperasi berdasarkan ID Transaksi saat peminjaman berhasil.