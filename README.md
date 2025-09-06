Praktikum 1: Membangun Layout di Flutter

Langkah 1: Membuat Project Baru

Pilih New Flutter Project pada halaman awal android Studio
<img width="791" height="649" alt="1" src="https://github.com/user-attachments/assets/cc7c46a4-e210-420a-a872-6db4d72f4ed6" />


Pilih Flutter pada bagian kiri
<img width="786" height="720" alt="2" src="https://github.com/user-attachments/assets/36b2b501-62bd-4ec2-b220-643b56ec722f" />


Ganti nama Project dan next
<img width="783" height="714" alt="3" src="https://github.com/user-attachments/assets/a9311ebc-b4c7-4d30-9a45-f8f1ac9e5ad4" />


Berikut hasilnya:
<img width="1387" height="983" alt="4" src="https://github.com/user-attachments/assets/ca7d7e5d-cec8-4864-8327-a20ad232bf68" />



Langkah 2: Buka file lib/main.dart
Buka file main.dart lalu ganti dengan kode berikut. Isi nama dan NIM Anda di text title.
Berikut Hasilnya:
<img width="913" height="558" alt="5" src="https://github.com/user-attachments/assets/e03c27df-3275-46f6-b3c4-3d9e001e4ff6" />



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
<img width="719" height="916" alt="6" src="https://github.com/user-attachments/assets/920ca2ec-c15b-4a30-bc36-5725e513c8f5" />



Praktikum 2: Implementasi Button Row

Langkah 1: Buat Method Column_buildButtonColumn
<img width="658" height="577" alt="7" src="https://github.com/user-attachments/assets/04827118-7fe1-49e2-bfbb-233c82e9e182" />


Langkah 2: Buat Widget Button Selection
<img width="1042" height="357" alt="8" src="https://github.com/user-attachments/assets/769e85eb-a9a0-4058-9e50-5fc79ab65ff4" />


Langkah 3: Tambah Button Section Ke Body
<img width="808" height="440" alt="9" src="https://github.com/user-attachments/assets/8eb77f6f-2b9b-4d5e-8a79-ba41d6ee7d00" />



Praktikum 3: Implementasi text Section

Langkah 1: Buat widget textSection
tentukan bagian teks sebagai variabel. Masukkan teks ke dalam Container dan tambahkan padding di sepanjang setiap tepinya. Tambahkan kode berikut tepat di bawah deklarasi buttonSection:
<img width="325" height="203" alt="10" src="https://github.com/user-attachments/assets/90c84e79-911d-4a98-9f7e-03d04837abe4" />


Langkah 2: Tambahkan text section ke body
Tambahkan widget variabel textSection ke dalam body seperti berikut:
<img width="310" height="89" alt="11" src="https://github.com/user-attachments/assets/1e9ef99d-a504-48e0-997b-ee9eba3a62ef" />



Praktikum 4: Implementasi image section

Langkah 1: Siapkan aset gambar
Anda dapat mencari gambar di internet yang ingin ditampilkan. Buatlah folder images di root project layout_flutter. Masukkan file gambar tersebut ke folder images, lalu set nama file tersebut ke file pubspec.yaml seperti berikut:
<img width="632" height="418" alt="12" src="https://github.com/user-attachments/assets/c8e265b4-97d8-41d2-b69a-0aaea6bd4521" />


Langkah 2: Tambahkan gambar ke body
Tambahkan aset gambar ke dalam body seperti berikut:
<img width="251" height="129" alt="13" src="https://github.com/user-attachments/assets/75ef765e-6cf3-48d6-ae2e-d3f98c7bce2d" />


Langkah 3: Terakhir, ubah menjadi ListView
Pada langkah terakhir ini, atur semua elemen dalam ListView, bukan Column, karena ListView mendukung scroll yang dinamis saat aplikasi dijalankan pada perangkat yang resolusinya lebih kecil.
<img width="314" height="285" alt="14" src="https://github.com/user-attachments/assets/d79e1f42-a972-4be5-98d6-6f6b30f2054f" />

