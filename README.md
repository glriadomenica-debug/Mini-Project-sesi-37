#DATABASE SYSTEM (LEARNING MANAGEMENT SYSTEM)

Proyek ini merupakan sistem database untuk learning management system yang digunakan untuk mengelola data user, category dan course.

**Fitur**
* Manajemen user role (Admin, Instructor dan Student)
* Manajemen course
* Manajemen category
* Relasi antar tabel dalam database
* Query SQL untuk menampilkan data di tabel dan kolum

**Struktur tabel di Database**
`users`
`categories`
`courses`

**Tools yang digunakan**
* Xampp
* Dbeaver
* DrawSQL (Perancang Database - ERD)

**cara Menjalankan Database**
1. Buka Xampp (run Mysql)
2. Buka Dbeaver (Buat database baru)
3. Import file SQL dan Jalankan script pembuatan tabel

Case Study LMS
1. SQL Fundamentals
Kerjakan query berikut:
* Tampilkan seluruh data course.
* Tampilkan nama course dan harga saja.
* Tampilkan course dengan harga antara 50.000 sampai 200.000.
* Tampilkan course yang memiliki kuota 0 ATAU harga di atas 500.000.
* Tampilkan 5 course dengan harga tertinggi.

2. Aggregate & Conditional Logic 
Kerjakan query berikut:
* Hitung total user yang terdaftar.
* Hitung total course yang tersedia.
* Hitung jumlah course per kategori.
* Hitung rata-rata harga course per kategori.
* Tampilkan kategori yang memiliki lebih dari 3 course.

3. Join Statements
Gunakan INNER JOIN atau LEFT JOIN sesuai kebutuhan:
* Tampilkan daftar course beserta nama kategorinya.
* Tampilkan semua kategori meskipun belum memiliki course.
* Tampilkan semua user meskipun belum pernah mengupload course.
* Tampilkan daftar course beserta nama instructor yang membuat course tersebut.
* Tampilkan jumlah course yang dibuat oleh masing-masing instructor.

**Author**
Gloria Domenica Ferreira Da Costa E Silva
