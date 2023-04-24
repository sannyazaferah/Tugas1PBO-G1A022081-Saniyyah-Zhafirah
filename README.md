# Tugas1PBO-G1A022081-Saniyyah-Zhafirah

1. Buatlah perbedaan functional programming dan object oriented programming dalam bahasa pemrograman pyhon, serta berikan contoh masing-masing code nya!
  Jawab:
  Functional programming dan object-oriented programming merupakan dua paradigma pemrograman yang berbeda dalam cara mereka memodelkan program dan mengorganisasikan   kode. Functional programming fokus pada fungsi dan data yang tidak dapat diubah (immutable), sedangkan Object-Oriented Programming (OOP) fokus pada objek dan         pengelolaan statusnya.Berikut adalah perbedaan antara functional programming dan object-oriented programming dalam bahasa pemrograman Python beserta contoh 
  code-nya:
  Functional Programming
  a). Fokus pada fungsi
      Functional programming memandang program sebagai sekumpulan fungsi, di mana setiap fungsi adalah sebuah unit yang mandiri dan berdiri sendiri. Fungsi dapat           menerima satu atau lebih parameter, melakukan beberapa operasi di atas data yang diberikan, dan menghasilkan hasil keluaran.
  b). Data tidak dapat diubah
      Dalam functional programming, data dianggap sebagai objek yang tidak dapat diubah (immutable). Ini berarti setiap kali kita memproses data, kita membuat             salinan data tersebut dan menghasilkan output baru.
  Pada penjelasan code1 yaitu sebuah program Python yang berfungsi untuk menambahkan nilai 3 pada setiap elemen yang ada di dalam list numbers. Berikut merupakan       penjelasan lebih rinci mengenai setiap baris kode:
  1). def increment(x):
     - Membuat sebuah fungsi bernama increment dengan parameter satu input yaitu x.
     - Fungsi ini akan mengembalikan nilai dari x ditambah 3.
  2). numbers = [1, 2, 3, 4, 5]
     - Mendefinisikan sebuah list numbers yang berisi bilangan integer dari 1 hingga 5.
  3). result = map(increment, numbers)
     - Menggunakan fungsi bawaan map() untuk mengaplikasikan fungsi increment() pada setiap elemen di dalam list numbers.
     - Mengembalikan sebuah iterator yang berisi hasil operasi yang dilakukan oleh fungsi increment().
  4). print(list(result))
     - Mengkonversi hasil dari map() menjadi list menggunakan fungsi bawaan list().
     - Mencetak list yang berisi nilai dari setiap elemen di dalam list numbers yang sudah ditambah 3.
Output dari program ini adalah [4, 5, 6, 7, 8], yaitu hasil penambahan 3 pada setiap elemen di dalam list numbers.

2. Berikan apa saja contoh pengimplementasian dari oop!
   Jawab:
   Berikut ini adalah beberapa contoh pengimplementasian dari OOP (Object Oriented Programming):
   1). Pembuatan Game: Saat membuat game, OOP memungkinkan penggunaan konsep seperti kelas, objek, pewarisan, dan polimorfisme. Setiap karakter dalam game dapat            diimplementasikan sebagai objek dengan karakteristiknya masing-masing.
   2). Pembuatan Aplikasi Desktop: OOP sangat berguna untuk mengorganisasi kode dalam aplikasi desktop, karena memungkinkan untuk memisahkan kode ke dalam kelas yang        berbeda. Ini dapat memudahkan pengembangan, pemeliharaan, dan perbaikan aplikasi.
   3). Pembuatan Website: Saat membuat website, OOP dapat digunakan untuk memisahkan kode menjadi kelas yang berbeda seperti pengolahan data, validasi, dan tampilan.        Selain itu, OOP dapat digunakan untuk membuat framework atau library yang dapat digunakan kembali dalam pengembangan website berikutnya.
   4). Pembuatan Aplikasi Mobile: Dalam pengembangan aplikasi mobile, OOP memungkinkan penggunaan kelas dan objek untuk merepresentasikan elemen yang ada di dalam          aplikasi seperti tombol, form, dan navigasi.
   5). Pembuatan Sistem Informasi: OOP memungkinkan penggunaan konsep seperti pewarisan dan polimorfisme untuk membuat hierarki kelas yang memudahkan dalam       p p        pengorganisasian dan pengelolaan data. Hal ini dapat membantu dalam pengembangan aplikasi atau sistem informasi yang kompleks.
   6). Pembuatan Robotika: Dalam pengembangan robot, OOP memungkinkan penggunaan kelas dan objek untuk merepresentasikan berbagai elemen dalam robot seperti sensor,        motor, dan logika kontrol.
   7). Pembuatan Sistem Keamanan: OOP dapat digunakan untuk membangun sistem keamanan yang kompleks dengan banyak kelas dan objek yang saling berhubungan dan                terstruktur. Misalnya, pengembangan sistem keamanan pada jaringan komputer atau sistem keamanan di gedung. 


 Berikut contoh implementasi OOP dalam kehidupan sehari - hari :
 1). Pembelian barang di toko: Ketika kita membeli barang di toko, kita dapat menggunakan konsep OOP dengan memandang setiap barang sebagai objek yang memiliki            karakteristik dan fungsi masing-masing seperti harga, merek, jenis, dan warna.
 2). Mengendarai mobil: Dalam mengemudikan mobil, kita dapat menggunakan konsep OOP dengan memandang mobil sebagai objek yang memiliki karakteristik seperti              kecepatan, kapasitas mesin, dan konsumsi bahan bakar.
 3). Olahraga: Saat berolahraga, konsep OOP dapat digunakan untuk merepresentasikan olahraga sebagai objek, dengan karakteristik seperti jenis olahraga, durasi, dan      intensitas.
 4). Menggunakan smartphone: Smartphone dapat diimplementasikan sebagai objek OOP yang memiliki berbagai karakteristik dan metode, seperti ukuran layar, kamera, dan aplikasi.
