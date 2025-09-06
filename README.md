Praktikum 1: Membangun Layout di Flutter

Langkah 1: Membuat Project Baru

Pilih New Flutter Project pada halaman awal android Studio
![alt text](1.png)

Pilih Flutter pada bagian kiri
![alt text](2.png)

Ganti nama Project dan next
![alt text](3.png)

Berikut hasilnya:
![alt text](4.png)


Langkah 2: Buka file lib/main.dart
Buka file main.dart lalu ganti dengan kode berikut. Isi nama dan NIM Anda di text title.
Berikut Hasilnya:
![alt text](5.png)


Langkah 3: Identifikasi Layout Diagram
Langkah pertama adalah memecah tata letak menjadi elemen dasarnya:

- Identifikasi baris dan kolom.
- Apakah tata letaknya menyertakan kisi-kisi (grid)?
- Apakah ada elemen yang tumpang tindih?
- Apakah UI memerlukan tab?
- Perhatikan area yang memerlukan alignment, padding, atau borders.


Langkah 4: Implementasi Title Row
Pertama, Anda akan membuat kolom bagian kiri pada judul. Tambahkan kode berikut di bagian atas 
metode build() di dalam kelas MyApp:
Berikut Hasilnya:
![alt text](6.png)


Praktikum 2: Implementasi Button Row

Langkah 1: Buat Method Column_buildButtonColumn
![alt text](7.png)

Langkah 2: Buat Widget Button Selection
![alt text](8.png)

Langkah 3: Tambah Button Section Ke Body
![alt text](9.png)


Praktikum 3: Implementasi text Section

Langkah 1: Buat widget textSection
tentukan bagian teks sebagai variabel. Masukkan teks ke dalam Container dan tambahkan padding di sepanjang setiap tepinya. Tambahkan kode berikut tepat di bawah deklarasi buttonSection:
![alt text](10.png)

Langkah 2: Tambahkan text section ke body
Tambahkan widget variabel textSection ke dalam body seperti berikut:
![alt text](11.png)


Praktikum 4: Implementasi image section

Langkah 1: Siapkan aset gambar
Anda dapat mencari gambar di internet yang ingin ditampilkan. Buatlah folder images di root project layout_flutter. Masukkan file gambar tersebut ke folder images, lalu set nama file tersebut ke file pubspec.yaml seperti berikut:
![alt text](12.png)

Langkah 2: Tambahkan gambar ke body
Tambahkan aset gambar ke dalam body seperti berikut:
![alt text](13.png)

Langkah 3: Terakhir, ubah menjadi ListView
Pada langkah terakhir ini, atur semua elemen dalam ListView, bukan Column, karena ListView mendukung scroll yang dinamis saat aplikasi dijalankan pada perangkat yang resolusinya lebih kecil.
![alt text](14.png)
