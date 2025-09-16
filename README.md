# posttest2_PBO
Program ini dirancang untuk mengelola dan memfasilitasi pencarian data kuliner di Samarinda. Aplikasi ini membantu pengguna untuk mencatat tempat-tempat kuliner dan menu-menu di dalamnya, serta menyediakan fitur-fitur pencarian yang memudahkan pengguna mencari kriteria kuliner yang diinginkan. 

# Deskripsi Program
Perkembangan program selanjutnya adalah pemisahan fitur eksplorasi kuliner di luar CRUD dasar yang awalnya pada . Program menyediakan fungsi pencarian, filter, dan rekomendasi untuk membantu pengguna menemukan kuliner sesuai kebutuhan. Selain itu, struktur program sudah dirancang menggunakan pendekatan MVC (Model–View–Controller).

# Fitur-Fitur Utama
1. Create (Buat)
   * Tambah Tempat Kuliner: Menambahkan data tempat kuliner baru, lengkap dengan nama, lokasi, dan rating.
   * Tambah Menu: Menambahkan menu baru ke tempat kuliner yang sudah ada. 

2. Read (Baca)
   * Menampilkan seluruh data tempat kuliner dan menu yang tercatat di dalam sistem.

3. Update (Perbarui)
   * Perbarui Tempat: Mengubah nama, lokasi, atau rating dari tempat kuliner.
   * Perbarui Menu: Mengubah nama, jenis, harga, atau rating dari menu tertentu.

4. Delete (Hapus)
   * Hapus Tempat: Menghapus data tempat kuliner beserta seluruh menu di dalamnya.
   * Hapus Menu: Menghapus menu dari sebuah tempat kuliner.

5. Eksplorasi
   * Cari Kuliner: Mencari tempat atau menu berdasarkan kata kunci.
   * Filter Kuliner: Melakukan pencarian spesifik dengan filter multi-level, yaitu:
     * Filter Rating: Menyaring menu berdasarkan rating
     * Filter Harga: Menyaring menu berdasarkan rentang harga (< Rp 15.000, Rp 15.000 - Rp 30.000, atau > Rp 30.000).
   * Rekomendasi Makanan: Menampilkan daftar menu dengan rating tertinggi yang tercatat dalam sistem.

# Alur Program
Terdapat perubahan tempat fitur yaitu fitur search, filter dan rekomendasi yang dipindahkan pada menu utama. pengguna bisa input angka 3 untuk menggunakan fiturnya.

<img width="459" height="253" alt="image" src="https://github.com/user-attachments/assets/f8abb74c-f1f1-47ba-9646-a33689caff5f" />

## Fitur Search, filter dan rekomendasi

Pengguna dapat memilih kembali ketika masuk pada submenu fitur yang bisa kita sebut fitur eksplorasi.

<img width="466" height="157" alt="image" src="https://github.com/user-attachments/assets/36d894e8-fe8f-4c89-bdd4-ea9da18ef9cd" />

## Fitur Search (cari kuliner)

Pengguna bisa menginputkan kata kunci yang sesuai atau sudah tercatat pada program

1. Kata kunci dengan nama makanan
   
   <img width="733" height="239" alt="image" src="https://github.com/user-attachments/assets/f2420540-6c32-4c7b-b579-1e0fffb8c818" />

2. Kata kunci dengan lokasi/nama tempat

   <img width="771" height="247" alt="image" src="https://github.com/user-attachments/assets/35d65ad2-2ae2-4d74-a783-9be564a1ae71" />

   <img width="768" height="238" alt="image" src="https://github.com/user-attachments/assets/d4c44049-e18e-410a-80d4-c93f2955653c" />

3. Kata kunci lain

  <img width="748" height="422" alt="image" src="https://github.com/user-attachments/assets/e118f98d-9ce2-46fe-a878-2df58fa7da45" />

## Fitur filter

Menu filter akan ditampilkan setelah menginputkan angka 2. Disini pengguna bisa menggunakan 2 fitur. penggunaan juga bisa digunakan sekaligus

<img width="348" height="185" alt="image" src="https://github.com/user-attachments/assets/ed8094ca-7698-45cc-993b-33bdd52d4214" />

1. filter harga
   
   setelah menginput angka 1 untuk filter harga dan memilih rentang harganya, pengguna akan kembali pada menu filter. input angka 3 untuk menampilkan hasil dari filter. Kuliner yang ditampilkan hanya memiliki harga menu sesuai rentang harga yang dipilih.

   <img width="771" height="747" alt="image" src="https://github.com/user-attachments/assets/3b8172cc-ce2f-46a1-a1e9-11ab8f7e9683" />
   
2. Filter rating

    Program dibuat untuk menampilkan minimal rating yang diinput. setelah input maka pengguna bisa langsung menampilkan hasil filter dengan input angka 3 pada menu filter.
   
   <img width="757" height="687" alt="image" src="https://github.com/user-attachments/assets/a9b5779f-366c-41fd-b38a-55eae393b809" />

3. Penggunaan lebih dari 1 filter
   Jika pengguna ingin melihat menu kuliner dengan rentang harga dan rating yang sesuai prefernsi, bisa memilih untuk input filter terlebih dahulu lalu menambahkan filter kembali. Jika sudah, maka tampilkan hasil filter dengan input angka 3.

- Pilih filter pertama
  
  <img width="363" height="326" alt="image" src="https://github.com/user-attachments/assets/19c76cd7-0111-4292-b926-ff7dd8fc44e2" />

- pilih filter kedua

  <img width="382" height="192" alt="image" src="https://github.com/user-attachments/assets/5ce92e0f-b671-41f0-a9a2-ea87b596acae" />

- tampilkan hasil filter

  <img width="771" height="525" alt="image" src="https://github.com/user-attachments/assets/3de123df-21e8-46d7-b55c-f2f7cdfa0f0f" />

## Fitur Rekomendasi

Input angka 3 untuk melihat rekomendasi berdasarkan rating tertinggi

<img width="740" height="290" alt="image" src="https://github.com/user-attachments/assets/aa5425d3-fe90-483c-83be-c18ac8d6e01f" />

## Kembali ke menu utama
Ketika ingin kembali ke menu utama, pengguna bisa input angka 4 untuk kembali.

# Validasi Input

1. Pengulangan
   jika pengguna tidak menginputkan angka yang sesuai, bukan angka, ataupun input kosong, maka program akan menanykan kembali pilihan input kepada pengguna.
   
   <img width="525" height="459" alt="image" src="https://github.com/user-attachments/assets/0fc97fbb-b983-4335-bfa7-6a0282a76d32" />
   <img width="381" height="463" alt="image" src="https://github.com/user-attachments/assets/dc2e1cb9-b082-4861-9ba3-3dd1ccd315b2" />
   <img width="512" height="389" alt="image" src="https://github.com/user-attachments/assets/fd943bbc-fa22-4bf2-9237-7570d82a8812" />

2. menanyaka kembali keputusan pengguna
   
   <img width="401" height="191" alt="image" src="https://github.com/user-attachments/assets/b0c14dba-d315-43ab-8583-ab725c001279" />





# Penerapan MVC
Program ini dikembangkan menggunakan pola arsitektur MVC (Model–View–Controller) untuk memisahkan antara data, logika bisnis, dan tampilan, sehingga kode lebih terstruktur, mudah dipelihara, dan dapat dikembangkan lebih lanjut.
1. Model
Package model berisi representasi data berupa kelas **TempatKuliner** dan **MenuKuliner**. *class* ini mendefinisikan atribut (field) dan menyediakan constructor serta getter/setter untuk mengelola data.
2. Service
Package service berisi kelas **KulinerService**. yang menangani seluruh logika program. Package berisi operasi CRUD, pencarian, filter dan rekomendasi dijalankan. Package ini menjadi penghubung antara Model dan Main.
3. Main
Package main berisi kelas KulinerApp sebagai titik masuk program (main method). Package ini mengatur alur interaksi dengan pengguna melalui menu berbasis console, menerima input, serta memanggil fungsi dari KulinerService.
