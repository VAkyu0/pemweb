# **Website Absensi untuk Tugas Pemograman Web**

Features

Aplikasi Absensi adalah sebuah aplikasi yang digunakan untuk mengelola kehadiran dan data karyawan. Aplikasi ini memiliki fitur-fitur sebagai berikut:

- CRUD Jabatan/Posisi
- CRUD Pengguna (Admin, Operator, dan Pengguna (Karyawan))
- CRUD Hari Libur
- Absensi Kehadiran (Dapat memiliki banyak absensi dan dapat menggunakan tombol atau QR Code)
- Menggunakan Datatables (Powergrid Livewire)
- Dapat diekspor ke Excel dan CSV
- Dan masih banyak lagi...

### Langkah 1: Clone repositori melalui command-line (cmd, bash, atau yang lainnya)
- git clone https://github.com/muhammadpauzi/absensi-app.git

### Langkah 2: Masuk ke folder aplikasi
- cd absensi-app

### Langkah 3: Install semua paket
- composer install

### Langkah 4: Pilih salah satu langkah berikut:
#### 1. Untuk Windows
- copy .env.example .env
#### 2. Untuk Unix (Ubuntu, Mac OS, dan lain-lain)
- cp .env.example .env

### Langkah 5: Setelah itu, buka file .env dan atur pengaturan yang diperlukan, seperti nama database (DB_DATABASE), username, dan password
#### Buat juga database baru melalui phpmyadmin atau command-line dengan nama sesuai dengan yang ada di file .env (DB_DATABASE)
- php artisan key:generate
- php artisan migrate
- php artisan db:seed
- php artisan serve

### Langkah 6: Buka browser dengan URL: http://localhost:8000/

Jika Anda mengikuti langkah-langkah di atas dengan benar, aplikasi Absensi akan berjalan pada URL http://localhost:8000/ di browser Anda.

Selamat mencoba!
