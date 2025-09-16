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
