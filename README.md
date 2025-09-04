# codelab02_dart
NIM = 23417290113
NAMA = Michelle Dorani Shiba

1. Pada kode tersebut saya menggunakan perulangan for yang dimulai dari nilai i=18 dan terus berkurang (i--) hingga lebih besar dari 8. Sehingga pada tiap iterasi, program akan mencetak kalimat "Nama saya Michelle, sekarang berumur ${i}" dengan nilai i yang berubah mulai dari 18 hingga 9.

2. Karena bahasa Dart adalah inti dari framework Flutter. Memahami Dart adalah dasar untuk bekerja dengan Flutter; pengembang perlu mengetahui asal-usul bahasa Dart, bagaimana komunitas mengerjakannya, kelebihannya, dan mengapa itu adalah bahasa pemrograman yang dipilih untuk Flutter.

3. a. Dasar Dart dan Flutter
- Dart adalah bahasa inti dari Flutter
- Dibutuhkan karena moder, efisien, dan mendukung
- Dart mendukung OOP, encapsulation, inheritance, abstraction, dam polymorphism

b. Kelebihan Dart
- Productive tooling: dukungan IDE, analisis kode, dan ekosistem paket.
- Garbage collection: otomatis mengelola memori.
- Type annotations (opsional): menjaga keamanan dan konsistensi data.
- Statically typed: aman dengan fitur type-safe & type inference.
- Portability: dapat dikompilasi ke JavaScript maupun kode native (ARM, x86).

c. Evolusi Dart
- Diluncurkan tahun 2011, stabil tahun 2013, major update di Dart 2.0 (2018).
- Awalnya untuk web (pengganti JavaScript), kini fokus ke mobile development (Flutter).
- Dirancang agar kuat, fleksibel, dan berperforma tinggi.

D. Cara Kerja Dart
- Dua cara eksekusi:
  1. Dart VM (Virtual Machine) -> mendukung pengembangan dengan JIT (Just-In-Time) -> cepat untuk debugging & hot reload.
  2. Kompilasi ke JavaScript (dart2js) -> untuk aplikasi web.
- Mendukung AOT (Ahead-Of-Time compilation) → hasil optimal untuk performa produksi.

E. Struktur Bahasa Dart
- Mirip dengan C/JavaScript -> mudah dipelajari.
- Semua data adalah objek (tidak ada primitive types seperti di Java).
- Operator: aritmatika (+, -, *, /, ~/), perbandingan (==, !=, >, <, >=, <=), logika (&&, ||, !), increment/decrement (++/--).
- Mendukung function dan class untuk modularisasi kode.

4. Null Safety digunakan untuk mencegah kesalahan yang diakibatkan oleh akses tidak disengaja ke variabel yang disetel ke null,  sedangkan Late Variables digunakan untuk mendeklarasikan variabel non-nullable yang akan diinisialisasi setelah deklarasinya. Pada gambar yang saya unggah di folder img, contoh ekseskusi Null Safety (soal4a.jpg) sesuai kode program yang saya buat memang tidak memiliki output apapun, namun dapat terlihat bahwa variabel nama yang saya deklarasikan tidak menyebabkan error NullPointerException. Di sisi lain sontoh eksekusi Late Variable (soal4b.jpg) sesuai kode program yang saya buat menghasilkan output "Michelle", kode tersebut menunjukkan bahwa dengan menggunakan keyword "late" variabel tersebut akan dapat diinisialisasi sebelum digunakan, bukan langsung saat dideklarasikan.