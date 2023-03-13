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

2. Membaca file log dengan menggunakan more memiliki beberapa kelemahan, di antaranya:

- Tidak Ada Filterisasi: Ketika membaca file log dengan menggunakan more, tidak ada cara untuk melakukan filter atau memperbaiki output. Jadi, pengguna harus membaca semua baris log dalam file, bahkan jika tidak semua baris log relevan.

- Tidak Ada Parsing: more tidak dapat memecah file log menjadi bagian yang lebih kecil, sehingga lebih mudah untuk dianalisis. Pengguna harus melakukan parsing secara manual untuk memahami informasi yang terdapat dalam file log.

- Tidak Ada Pengelompokan: more juga tidak dapat mengelompokkan baris log ke dalam kategori yang relevan. Ini dapat membuat sulit bagi pengguna untuk memahami pola atau tren dalam file log yang mungkin diperlukan untuk melakukan analisis atau memecahkan masalah.

- Tidak Ada Waktu Nyata: more hanya dapat menampilkan file log yang ada, dan tidak dapat menampilkan informasi log secara waktu nyata. Ini berarti bahwa pengguna mungkin tidak dapat melihat log terbaru, yang mungkin sangat penting dalam situasi tertentu.

Oleh karena itu, meskipun more dapat digunakan untuk membaca file log, terutama jika file log relatif kecil, ada banyak kelemahan yang perlu dipertimbangkan. Untuk analisis log yang lebih kompleks, disarankan untuk menggunakan alat analisis log yang lebih canggih dan terstruktur.

3.Perintah tail dan tail -f digunakan untuk menampilkan beberapa baris terakhir dari sebuah file teks. Namun, keduanya memiliki perbedaan dalam cara mereka menampilkan output.

Perintah tail secara default akan menampilkan 10 baris terakhir dari sebuah file dan kemudian keluar dari program. Ini cocok untuk menampilkan konten terakhir dari sebuah file yang tidak berubah.Sementara itu, perintah tail -f akan menampilkan konten terakhir dari sebuah file dan kemudian terus memantau file tersebut untuk menampilkan setiap baris baru yang ditambahkan ke file tersebut secara real-time. Ini berguna untuk melihat aktivitas yang sedang terjadi pada sebuah file, seperti log file dari aplikasi.

Jadi perbedaan utama antara tail dan tail -f adalah bahwa tail hanya menampilkan konten terakhir dari sebuah file, sedangkan tail -f terus memantau file untuk menampilkan konten baru yang ditambahkan ke file.

4. Mengapa perintah cat harus dijalankan sebagai root??

Perintah cat adalah perintah standar di sebagian besar sistem operasi Unix dan digunakan untuk membaca, menggabungkan, dan menampilkan isi file ke layar. Dalam kebanyakan kasus, perintah cat tidak perlu dijalankan sebagai root atau superuser, dan pengguna biasa dapat menjalankannya dengan baik.Namun, dalam beberapa situasi, pengguna harus menjalankan perintah cat sebagai root atau superuser. Ini biasanya terjadi ketika pengguna mencoba membaca isi file yang hanya dapat diakses oleh pengguna dengan hak akses superuser, seperti file konfigurasi sistem atau file log sistem.

Dalam situasi seperti itu, perintah cat harus dijalankan sebagai root atau superuser agar memiliki akses ke file yang diinginkan. Namun, sebaiknya pengguna tidak menjalankan perintah cat sebagai root jika tidak perlu, karena menjalankan perintah sebagai root dapat membuka celah keamanan pada sistem. Oleh karena itu, sebaiknya pengguna hanya menjalankan perintah cat sebagai root jika benar-benar diperlukan untuk mengakses file yang hanya dapat diakses oleh superuser.


5. Jelaskan kenapa harus mensinkronkan waktu dan tanggal komputer dengan benar?

Mensinkronkan waktu dan tanggal komputer dengan benar sangat penting karena banyak proses dan aplikasi pada komputer yang bergantung pada waktu yang akurat. Beberapa alasan mengapa waktu yang tepat sangat penting adalah sebagai berikut:

- Penjadwalan tugas: Banyak aplikasi dan sistem operasi menggunakan waktu yang akurat untuk menjadwalkan tugas. Jika waktu yang tidak tepat digunakan, maka tugas-tugas ini mungkin tidak dijalankan pada waktu yang diinginkan atau bahkan tidak dijalankan sama sekali.

- Sistem Logging: Sistem logging pada komputer sangat penting untuk memantau aktivitas sistem dan membantu dalam debugging. Jika waktu sistem tidak akurat, maka logging dapat menjadi sulit diinterpretasikan atau bahkan dapat menimbulkan kesulitan dalam mencari kejadian yang terjadi pada waktu tertentu.

- Transaksi Keuangan: Banyak aplikasi keuangan menggunakan waktu untuk melacak transaksi dan pembayaran. Jika waktu yang tidak akurat digunakan, maka ada risiko kesalahan dalam transaksi dan pembayaran.

- Keamanan: Banyak sistem keamanan menggunakan waktu untuk memvalidasi kredensial dan melacak akses. Jika waktu yang tidak tepat digunakan, maka sistem keamanan mungkin menjadi rentan dan dapat membuka celah keamanan yang tidak diinginkan.

Dengan demikian, mensinkronkan waktu dan tanggal komputer dengan benar sangat penting untuk memastikan bahwa proses dan aplikasi yang berjalan pada komputer dapat berfungsi dengan baik dan dapat diandalkan.
