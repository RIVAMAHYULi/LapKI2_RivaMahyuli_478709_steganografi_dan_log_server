# LapKI2_RivaMahyuli_478709_steganografi_dan_log_server

PEMBAHASAN dan ANALISIS

TUGAS 1 STEGANOGRAFI

![image](https://user-images.githubusercontent.com/99727334/224639234-dd9b6bb2-bf47-487e-ba19-1e54ac8e2288.png)

Pada gambar diatas kita bisa melihat bahwa size dari gambar sebelum dilakukan steganografi dan sesudah dilakukan steganografi berubah. Size dari gambar yang sudah dilakukan steganografi lebih besar karena pada gambar tersebut kita telah menambahkan pesan tersembunyi. Perbedaan ukuran antara kedua gambar sangat berbeda bisa mencapai 2x dari ukuran gambar sebenarnya.

Hash atau proses hashing ini adalah proses perubahan suatu data menjadi nilai yang 
lain dengan Panjang tertentu, namun pada fungsi hash MD5 sendiri akan  menerima inputan sembarang dan akan berubah menjadi message digest yang panjangnya tetap yaitu menjadi 128 bit.

![image](https://user-images.githubusercontent.com/99727334/224641026-67180ded-c0a8-479d-9673-8abd09377aa6.png)

dari gambar diatas kita bisa mengetahui bahwa nilai hash adalah nilai numerik dengan panjang data yang tetap. Nilai numerik kedua gambar berbeda tetapi memiliki panjang data yang sama. nilai hash digunakan untuk mengindentifikasi data


TUGAS 2 LOG SEVER
File log adalah file yang digunakan untuk merekam peristiwa tertentu yang dihasilkan oleh aplikasi, layanan, atau sistem operasi itu sendiri. Biasanya file log ini disimpan sebagai teks biasa. File log merupakan sumber yang sangat diperlukan untuk pemecahan masalah.File log biasanya berisi informasi teks biasa yang dapat dilihat oleh hampir semua program yang dapat menangani teks (editor teks, misalnya). Namun, karena kemudahan, kegunaan,dan kecepatan, beberapa alat lebih umum digunakan daripada yang lain. Bagian ini berfokus pada empat program berbasis baris perintah: cat, more, less, dan tail.Fitur cat, berasal dari kata 'concatenate', alat berbasis baris perintah yang digunakan untuk membaca dan menampilkan konten file di layar. Karena kemudahannya dan dapat membuka file teks dan menampilkannya di terminal teks saja, cat banyak digunakan hingga hari ini. 

1. Membaca file teks besar dengan perintah cat memiliki beberapa kelemahan, di antaranya:

- Keterbatasan Memori: Ketika menggunakan cat pada file teks yang sangat besar, sistem mungkin tidak memiliki cukup memori untuk menampilkan seluruh isi file dalam satu kali tampilan. Ini dapat membuat proses membaca file menjadi lambat atau bahkan terhenti.

- Tidak Ada Paginasi: cat tidak memiliki fungsi paginasi, yang berarti bahwa seluruh isi file ditampilkan secara langsung di layar tanpa pemisahan. Hal ini dapat membuat sulit bagi pengguna untuk membaca dan menavigasi isi file yang besar.

- Tidak Ada Pencarian: Ketika menggunakan cat, tidak ada kemampuan untuk mencari isi file secara langsung. Ini dapat membuat sulit bagi pengguna untuk menemukan informasi tertentu di dalam file yang besar.

- Tidak Ada Penanganan Kesalahan: Jika file yang dibuka dengan cat rusak atau tidak dapat dibaca, tidak ada pemberitahuan atau pesan kesalahan yang akan ditampilkan. Hal ini dapat menyebabkan pengguna kehilangan informasi penting atau menghabiskan waktu yang lama mencari penyebab masalah.

Oleh karena itu, untuk membaca file teks besar dengan lebih efektif, disarankan untuk menggunakan alat yang dirancang khusus untuk membaca file besar seperti less atau more yang memiliki fitur paginasi, pencarian, dan penanganan kesalahan yang lebih baik

2. 
