1.	 Konsep Program yang Diangkat
Judul Konsep: Sistem Manajemen Perpustakaan Sederhana
Deskripsi Singkat:
Program ini akan memodelkan sistem perpustakaan di mana terdapat entitas seperti Buku, Anggota, dan Petugas. Sistem ini akan menggunakan prinsip OOP yaitu:
•	Class & Object
•	Encapsulation
•	Inheritance (Pewarisan)
•	Array

2.	 Penjelasan Konsep OOP pada Program
a.	Class & Object
Program terdiri dari beberapa class:
•	Buku: berisi informasi tentang buku (judul, penulis, ISBN).
•	Anggota: mewakili peminjam buku.
•	BukuPelajaran dan BukuFiksi: adalah subclass dari Buku.
Fungsi dalam Program:
•	Kita bisa memodelkan dunia nyata (buku, anggota) dalam bentuk object.
•	Object punya atribut (judul, penulis, genre) dan method (tampilInfo()).

b.	 Encapsulation
Atribut-atribut disimpan dengan access modifier private atau protected, dan diakses melalui method getter & setter.
Fungsi dalam Program:
•	Data nama dan id di Anggota hanya bisa diakses melalui method.
•	Melindungi integritas data, misalnya mencegah data dimodifikasi sembarangan.

c.	 Inheritance (Pewarisan)
Class BukuPelajaran dan BukuFiksi adalah turunan dari class Buku. Dan diturunkan lagi ke subclass Buku Pelajaran IPS dan Buku Pelajaran Fiksi.
Fungsi Nyata dalam Program:
•	Menyimpan beberapa buku sekaligus dalam satu struktur data.
•	Bisa melakukan perulangan (for) untuk menampilkan semua buku di perpustakaan.
•	Cocok untuk sistem yang punya banyak data dinamis (seperti daftar buku).

d.	Array
Program menyimpan daftar buku dalam array.
Fungsi Nyata dalam Program :
•	Menyimpan beberapa buku sekaligus dalam satu struktur data.
•	Bisa melakukan perulangan (for) untuk menampilkan semua buku di perpustakaan.
•	Cocok untuk sistem yang punya banyak data dinamis (seperti daftar buku).
