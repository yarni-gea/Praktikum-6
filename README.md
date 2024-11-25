# Praktikum-6

# Program input data 

# mahasiswa 

Program sederhana untuk mengelola data nilai mahasiswa menggunakan Python dengan struktur data Dictionary.

# flow chart 

![image](https://github.com/user-attachments/assets/aa065533-c69f-41ea-bb43-38ddae6c6e1b)

# Demo program 

fitur tambah 

![image](https://github.com/user-attachments/assets/10eb195a-ecd4-4579-a96e-1375c869cfa9)

fitur lihat

![image](https://github.com/user-attachments/assets/335cdc7d-5bdc-4699-8045-efce6af593de)

# deskripsi pemrograman 

Program ini merupakan implementasi sistem manajemen data nilai mahasiswa dengan fitur CRUD (Create, Read, Update, Delete) menggunakan bahasa pemrograman Python.

Program menyimpan data dalam bentuk dictionary dengan NIM sebagai key dan data mahasiswa sebagai value.

# fitur program 

Lihat Data (L)

Menampilkan daftar nilai seluruh mahasiswa

Format tampilan menggunakan tabel dengan header yang jelas

Menampilkan "TIDAK ADA DATA" jika belum ada data yang tersimpan

Tambah Data (T)

Input data mahasiswa baru (NIM, Nama, Nilai Tugas, UTS, UAS)

Perhitungan nilai akhir otomatis dengan bobot:

Tugas: 30%

UTS: 35%

UAS: 35%

Data langsung ditampilkan setelah penambahan

Ubah Data (U)

Mencari data berdasarkan NIM

Memungkinkan perubahan semua komponen data

Menampilkan pesan error jika NIM tidak ditemukan

Data langsung diperbarui setelah perubahan

Hapus Data (H)

Menghapus data berdasarkan NIM

Konfirmasi penghapusan data

Menampilkan pesan error jika NIM tidak ditemukan

Cari Data (C)

Mencari dan menampilkan data berdasarkan NIM

Menampilkan detail lengkap data mahasiswa

Menampilkan pesan error jika NIM tidak ditemukan

# struktur program 

# class data nilai

          class data nilai :
            def_init_(self):
              self.data = {} # Dictionary untuk menyiapkan data

# metode-metedo dalam class

 tampilkan_menu()

Menampilkan menu utama program

Format: [(L)ihat, (T)ambah, (U)bah, (H)a

tampilkan_daftar()

Menampilkan data dalam format tabel

Menggunakan string formatting untuk alignment

Menghitung nilai akhir otomatis

tambah_data()

Input dan validasi data baru

Menyimpan data ke dictionary

Menampilkan data setelah penambahan

ubah_data()

Mencari data berdasarkan NIM

Input data baru

Update dictionary

Menampilkan data setelah perubahan

hapus_data()

Mencari dan menghapus data berdasarkan NIM

Konfirmasi penghapusan

Menampilkan data setelah penghapusan

cari_data()

Mencari dan menampilkan detail data

Format tampilan yang rapi

# cara pengguna

Jalankan program dengan perintah:

python program_nilai.py

Pilih menu dengan memasukkan huruf sesuai pilihan:

L: Lihat data

T: Tambah data

U: Ubah data

H: Hapus data

C: Cari data

K: Keluar program

Ikuti instruksi yang muncul untuk setiap operasi

# Alogaritma program

Inisialisasi Program

Buat instance class DataNilai

Tampilkan menu utama

Loop Utama Program

Terima input pilihan menu

Jalankan metode sesuai pilihan

Ulangi sampai pilihan 'K' (Keluar)

Pengelolaan Data

Data disimpan dalam dictionary

NIM sebagai key

Data mahasiswa sebagai value dalam bentuk dictionary

Perhitungan Nilai

Nilai Akhir = (Tugas * 30%) + (UTS * 35%) + (UAS * 35%)

Hasil ditampilkan dengan 2 desimal

# persyartan sistem

Python 3.x

Tidak memerlukan library eksternal

# kontribusi

Silakan berkontribusi dengan cara:

Fork repository

Buat branch baru

Commit perubahan

Push ke branch

Buat Pull Request

Lisensi

Program ini dibuat untuk tujuan pembelajaran dan bebas digunakan sesuai kebutuhan.







