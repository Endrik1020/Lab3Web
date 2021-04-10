# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
## 1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat List</h1>
 </header>
</body>
</html>
~~~
![1a](https://user-images.githubusercontent.com/81820421/114278233-f994a500-9a58-11eb-9dc4-f6060778f0db.JPG)
![1b](https://user-images.githubusercontent.com/81820421/114278235-fb5e6880-9a58-11eb-839e-9d4ed6a768a7.JPG)

## 2. Membuat Ordered List
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
~~~
<section id="order-list">
 <h2>Ordered List</h2>
 <ol>
 <li>Pemrograman Web</li>
 <li>Sistem Informasi</li>
 <li>Basis Data 2</li>
 </ol>
</section>
~~~
![2a](https://user-images.githubusercontent.com/81820421/114278483-4462ec80-9a5a-11eb-83ad-4ab7c0c77d58.JPG)

## 3. Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada 
section unordered-list, seperti berikut.
~~~
<section id="unorder-list">
 <h2>Unordered List</h2>
 <ul type="square">
 <li>Jaringan Komputer</li>
 <li>Struktur Data</li>
 <li>Algoritma &amp; Pemrograman</li>
 </ul>
</section>
~~~
![3](https://user-images.githubusercontent.com/81820421/114278508-65c3d880-9a5a-11eb-916c-fd4850327c0d.JPG)

## 4. Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
~~~
<section id="unorder-list">
 <h2>Description List</h2>
 <dl>
 <dt>Fakultas Teknik</dt>
 <dd>Teknik Industri</dd>
 <dd>Teknik Informatika</dd>
 <dd>Teknik Lingkungan</dd>
 <dt>Fakultas Ekonomi dan Bisnis</dt>
 <dd>Akuntansi</dd>
 <dd>Manajemen</dd>
 <dd>Bisnis Digital</dd>
 </dl>
</section>
~~~
![4](https://user-images.githubusercontent.com/81820421/114278722-4ed1b600-9a5b-11eb-83bb-5034d1406986.JPG)

## 5. Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
~~~
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>HTML Lanjutan</title>
</head>
<body>
 <header>
 <h1>Membuat Table</h1>
 </header>
</body>
</html>
~~~
![tabel1](https://user-images.githubusercontent.com/81820421/114278832-c9023a80-9a5b-11eb-91af-79c73a06970f.JPG)
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<table border="1" cellpadding="4" cellspacing="0">
 <thead>
 <tr>
 <th>No.</th>
 <th>Fakultas</th>
 <th>Program Studi</th>
 </tr>
 </thead>
 <tbody>
 <tr>
 <td>1.</td>
 <td>Teknik</td>
 <td>Teknik Informatika</td>
 </tr>
 <tr>
 <td>2.</td>
 <td>Teknik</td>
 <td>Teknik Industri</td>
 </tr>
 <tr>
 <td>3.</td>
 <td>Teknik</td>
 <td>Teknik Lingkungan</td>
 </tr>
 </tbody>
</table>
~~~
![tabel2](https://user-images.githubusercontent.com/81820421/114278972-7412f400-9a5c-11eb-973b-aae568aea68a.JPG)

## 6. Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan 
cellspacing pada tag table.
~~~
<table border="1" cellpadding="4" cellspacing="4">
~~~
![tabel3](https://user-images.githubusercontent.com/81820421/114279206-af61f280-9a5d-11eb-95e8-4244d3ae1b24.JPG)



