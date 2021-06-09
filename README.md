# Lab10Web
# Praktikum 10

# 1. Mobil.php

Class digunakan untuk mendeklarasikan sebuah variabel yang berupa objek. Di dalam class ini akan di isi oleh properti, method dan lain-lain seperti contoh di bawah ini.

![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/mobil1.JPG)
![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/mobil2.JPG)
![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/mobil3.JPG)

Pada output di atas, mobil pertama yang mengacu pada objek dengan variabel $a memiliki mobil dengan warna biru sebagai warna default yang dimiliki method parent. Lalu warna mobil diganti warna merah menggunakan fitur contructor untuk mendefinisikan warna baru saat instansiasi objek.

Untuk mobil kedua ($b) sama seperti warna merah, warna langsung diganti dengan warna hijau dengan menggunakan method child gantiWarna lalu ditampilkan dengan method child tampilWarna.

# Form Input
Membuat form input sederhana menggunakan metode oop pada bahasa php.

Pada gambar dibawah ini terdapat method __construct yang berisi aksi pada form, displayForm() yang membentuk form html dan addField() yang berfungsi untuk menambah baris input.

![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/forminput1.JPG)
![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/forminput2.JPG)

Kode diatas tidak dapat ditampilkan pada browser, maka dari itu terdapat file berbeda dengan kode seprti dibawah ini yang memanggil file dengan kode di atas lalu membuat objek dan instansiasi objek sehingga membentuk sebuah tabel input.
![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/form1.JPG)
![imag](https://github.com/fdlhrauf/Lab10Web/blob/main/foto/form2.JPG)
