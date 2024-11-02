Algoritma Latihan 1:
![Diagram Tanpa Judul drawio (2)](https://github.com/user-attachments/assets/5e388b41-66ac-4f95-9878-c0cb0e2c02ed)
![Capture22](https://github.com/user-attachments/assets/d53e63a3-68e9-4539-9afc-41eee5eb688e)
PENJELASANNYA 
print : berfungsi untuk mencetak atau menampilkan objek ke perangkat keluaran (layar) atau ke file teks.
import : fungsi lanjut yang dipanggil oleh statement import.
random : untuk menentukan suatu pilihan.
range : merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu.
uniform: digunakan untuk menampilkan bilangan float random dengan batas awal bilangan x, dan batas akhir bilangan y.

Algoritma Latihan 2 
![Diagram Tanpa Judul drawio (3)](https://github.com/user-attachments/assets/6bf5d258-3ec3-4638-95ea-9d5026509728)
PENJELASANNYA 
1. Inisialisasi Variabel untuk Angka Terbesar
   Variabel max_numberdiatur ke None. Hal ini dilakukan untuk memulai dengan nilai kosong sehingga kita dapat membandingkannya dengan input pengguna dan memperbaruinya untuk menyimpan angka terbesar. Hal ini juga membantu dalam memeriksa apakah ada angka yang dimasukkan saat menampilkan hasil.
2. Petunjuk Tampilan
   print("Masukan bilangan (masukan 0 untuk berhenti):")
   Baris ini mencetak pesan yang menginstruksikan pengguna untuk memasukkan angka dan 0berhenti menggunakannya. Pesan ini penting untuk memandu pengguna agar tahu kapan harus berhenti memasukkan angka.
3. Mulai Loop untuk Input Pengguna
   while True:
    user_input = input("Masukkan angka: ")
   Program ini menggunakan while Trueperulangan, yang akan terus berjalan hingga suatu breakpernyataan ditemukan.
Di dalam loop ini, program meminta pengguna untuk memasukkan angka. Input ini dianggap sebagai string.
4. Konversi Input ke Integer
   number = int(user_input)
   String input kemudian diubah menjadi bilangan bulat. Hal ini penting karena kita perlu membandingkan nilai numerik untuk menemukan angka terbesar.
5. Periksa Kondisi Keluar
   if number == 0:
    break
   Program akan memeriksa apakah angka yang dimasukkan adalah 0. Jika 0dimasukkan, berarti pengguna ingin berhenti, sehingga loop berakhir menggunakan break.
6. Perbarui Angka Terbesar jika Diperlukan
   if max_number is None or number > max_number:
    max_number = number
   putaran belum dihentikan, program akan memeriksa apakah max_numbersalah satu None(yang menunjukkan ini adalah angka pertama yang dimasukkan) atau apakah angka yang baru numberlebih besar daripada angka saat ini max_number.
Jika salah satu kondisi bernilai benar, max_numberakan diperbarui ke yang baru number, memastikan selalu berisi angka terbesar yang telah dimasukkan sejauh ini.
7. Menampilkan Angka Terbesar Setelah Loop Berakhir
   if max_number is not None:
    print("Bilangan terbesar adalah:", max_number)
else:
    print("Tidak ada bilangan yang diinputkan")
   Setelah putaran berakhir (ketika pengguna memasukkan 0), program akan memeriksa apakah max_numbertelah ditetapkan ke nilai apa pun (artinya pengguna memasukkan setidaknya satu angka).
Jika max_numberbukan None, ia akan mencetak angka terbesar.
Jika max_numbermasih None, berarti pengguna tidak memasukkan angka apa pun, sehingga program akan mencetak pesan yang menyatakan tidak ada angka yang dimasukkan.
![33333](https://github.com/user-attachments/assets/f299c9dc-4ef8-4828-8707-da5e219b9b02)

Tugas Praktikum 3

![Diagram Tanpa Judul drawio (6)](https://github.com/user-attachments/assets/096dc037-531f-4c39-976f-8bf2dba036f7)


![Ca](https://github.com/user-attachments/assets/6b844bf0-ece7-4aaf-ad78-5f5a7bfcbe99)


Fungsi hitung_lababiasanya 
   pada sebuah fungsi dalam pemrograman yang digunakan untuk menghitung laba dari suatu usaha atau investasi. Fungsi ini dapat menerima beberapa parameter, seperti modal awal,
1. Definisi dan Struktur Fungsihitung_laba
  1. Definisi Umum :
      Fungsi hitung_labaadalah suatu blok kode yang dirancang untuk melakukan perhitungan laba berdasarkan input yang diberikan. Fungsi ini dapat digunakan untuk mengotomatisasi perhitungan laba dalam berbagai konteks, seperti investasi, usaha dagang, atau proyek tertentu.
2. Parameter : Fungsi ini mungkin memiliki beberapa parameter, seperti:
modal : Jumlah investasi awal.
persentase : Persentase laba yang diperoleh setiap periode.
period : Jumlah periode waktu (misalnya bulan) untuk menghitung laba.
3. Proses
 laba=modal:persentase/100
4. Output : Fungsi ini akan mengembalikan total laba yang dihitung selama periode yang ditentukan.
 
