# Lab9Web

| INDIRA ALINE         | 312010042          |
|----------------------|--------------------|
|  TI.20.A.1           |  PEMROGRAMAN WEB   |
|  PERTEMUAN  11       | PRAKTIKUM 9        |

Dipertemuan kali ini kita akan mempelajari **php modular** 

## LANGKAH - LANGKAH PRAKTIKUM

## 1). MENJALANKAN XAMPP SERVER
![menjalankan-xampp-server](img/mysql_server.png)

**PENJELASAN**

Menjalankan xampp server localhost.

## 2).BUAT FOLDER BARU DENGAN NAMA **lab9_php_modular** 
![folder-php_modular](img/new_folder.png)

**PENJELASAN**

Kemudian jalanlan pada localhost server dengan mengakses URL: http://localhost/Lab9Web/lab9_php_modular/
![local-server](img/index.png)

## 3). BUAT FILE BARU DENGAN NAMA **header.php**
![header](img/header.png)

**PENJELASAN**

Buat header seperti contoh di atas.

 **code header**
 
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
 ```
 
## 4). BUAT FILE BARU DENGAN NAMA **footer.php**
![footer](img/footer.png)

**PENJELASAN**

Buat **footer.php** dan codenya.

**code footer**

```html
<footer>
            <p>&copy; 2022, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

## 5). BUAT FILE BARU DENGAN NAMA **home.php**
![home](img/home.png)

**PENJELASAN**

Buat **home.php** dan codenya.

**code home**

```php
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

## 6). BUAT FILE BARU DENGAN NAMA **about.php**
![about](img/about.png)

**PENJELASAN**

Buat **about.php** dan codenya.

**code about**

```php
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
```

## 7). TAMPILAN DIBROWSER NYA

* Tampilan **home** page pada browser yang menggunakan modular ***header*** dan ***footer***
![home-page](img/home_browser.png)

* Tampilan **about** page pada browser yang menggunakan modular ***header*** dan ***footer***
![about-page](img/about_browser.png)

--------------------------------------------------------------------------------

## PERTANYAAN DAN TUGAS

* Implementasikan konsep modularisasi pada kode program **praktikum 8** tentang database, sehingga setiap halamannya template tampilan yang sama.

## 1) BUAT FOLDER BARU **lab9_tugas**

**PENJELASAN**

Buat file baru atau salin file pada **praktikum 8** lalu implementasikan dengan menambahkan modular **header** dan **footer**

## HASIL

* Tampilan pada bagian **Home** 
![home-page](img/tugas.png)


* Tampilan pada bagian **Tambah Barang**
![page-tambah-barang](img/tugas1.png)


* Tampilan pada bagian **Ubah Barang**
![page-ubah-barang](img/tugas2.png)

## TERIMAKASIH