# MovieApp
sudah selesai

![alt text](https://github.com/ManggalaKZ/MovieApp/blob/master/WhatsApp%20Image%202021-04-29%20at%2023.48.11.jpeg)
![alt text](https://github.com/ManggalaKZ/MovieApp/blob/master/WhatsApp%20Image%202021-04-29%20at%2023.48.11%20(1).jpeg)

API atau Application Programming Interface adalah sebuah interface yang dapat menghubungkan aplikasi satu dengan aplikasi lainnya. Jadi, API berperan sebagai perantara antar berbagai aplikasi berbeda, baik dalam satu platform yang sama atau lintas platform.
Perumpamaan yang bisa digunakan untuk menjelaskan API adalah seorang pelayan di restoran. Tugas pelayan tersebut adalah menghubungkan tamu restoran dengan juru masak. Tamu cukup memesan makanan sesuai daftar menu yang ada dan pelayan memberitahukannya ke juru masak. Nantinya, pelayan akan kembali ke tamu tadi dengan masakan yang sudah siap sesuai pesanan.


Retrofit adalah sebuah library android yang membantu pengembang untuk melakukan request ke sebuah endpoint REST API. Library ini dikembangkan oleh Square Inc (https://github.com/square) sebuah perusahaan yang berbasis di Amerika Serikat. Library ini menyederhanakan kode program yang digunakan untuk mengakses REST API. Tidak hanya untuk mengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit juga mendukung berbagai macam format authentikasi via http, menambahkan header pada request, menambahkan parameter serta mengirim data berupa image ke server. Untuk mengakses REST api dengan kode program bawaan android seorang programmer harus membuat banyak worker dan thread menggunakan Async Task. Hal ini bukan sebuah proses yang sederhana, apalagi jika request terhadap API tersebut menuntut adanya security, parameter khusus yang harus ditambahkan atau bahkan mengirim data selain text contoh berupa gambar ke server. Jika menggunakan Async Task dapat dipastikan programmer akan kesulitan dalam membuat program. Akan lebih baik jika semua proses yang berhubungan dengan networking tersebut ditangani oleh Retrofit. kita akan mencoba mengambil data dari http://www.omdbapi.com/?s=batman&apikey=2268147d
