# Pemograman Web
~~~
Nama   = Endrik
NIM    = 311910088
Kelas  = TI.19.C.1
Universitas Pelita Bangsa
~~~
## 1. MEMBUAT LIST
## 1.1  Membuat dokumen HTML
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

## 1.2 Membuat Ordered List
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

## 1.3 Membuat Unorderd List
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

## 1.4 Membuat Description List
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
## 2. MEMBUAT TABEL
## 2.1 Membuat Tabel
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

## 2.2 Mengatur Margin dan Padding
Untuk mengatur margin dan padding pada cel data, tambahkan atribut cellpadding dan 
cellspacing pada tag table.
~~~
<table border="1" cellpadding="4" cellspacing="4">
~~~
![tabel3](https://user-images.githubusercontent.com/81820421/114279206-af61f280-9a5d-11eb-95e8-4244d3ae1b24.JPG)

## 2.3 Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk 
menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara 
horizontal). 
~~~
<table border="1" cellpadding="6" cellspacing="0">
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
 <td rowspan="3">Teknik</td>
 <td>Teknik Informatika</td>
 </tr>
 <tr>
 <td>2.</td>
 <td>Teknik Industri</td>
 </tr>
 <tr>
 <td>3.</td>
 <td>Teknik Lingkungan</td>
 </tr>
 </tbody>
</table>
~~~
![tabel4](https://user-images.githubusercontent.com/81820421/114279358-737b5d00-9a5e-11eb-9614-c92ac84402ad.JPG)
## 3. MEMBUAT FORM
## 3.1 Membuat form 
Buat file baru dengan nama lab3_form.html seperti berikut.
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
 <h1>Membuat Form</h1>
 </header>
</body>
</html>
~~~
![tform1](https://user-images.githubusercontent.com/81820421/114279942-43818900-9a61-11eb-82ed-920c4aa54fad.JPG)
# Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:
~~~
<form action="proses.php" method="post">
 <fieldset>
 <legend>Data Pelanggan</legend>
 <p>
 <label for="nama">Nama</label>
 <input type="text" id="nama" name="nama">
 </p>
 <p>
 <label for="alamat">Alamat</label>
 <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
 </p>
 <p>
 <label>Jenis Kelamin</label>
 <input id="jk_l" type="radio" name="kelamin" value="L" /><label
for="jk_l">Laki-laki</label>
 <input id="jk_p" type="radio" name="kelamin" value="P" /><label
 or="jk_p">Perempuan</label>
 </p>
 <p><input type="submit" value="Login"></p>
 </fieldset>
</form>
~~~
![tform2](https://user-images.githubusercontent.com/81820421/114280268-a7588180-9a62-11eb-9481-cdba9265648e.JPG)
## 3.2 Menabahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.
~~~
<style>
 form p > label {
 display: inline-block;
 width: 100px;
 }
 form input[type="text"], form textarea {
 border: 1px solid #197a43;
 }
 form input[type="submit"] {
 border: 1px solid #197a43;
 background-color: #197a43;
 color: #ffffff;
 font-weight: bold;
 padding: 5px 15px;
 }
</style>
~~~
![tform3](https://user-images.githubusercontent.com/81820421/114280397-34033f80-9a63-11eb-9811-037dc0556a96.JPG)

## Pertanyaan dan Tugas
1. Buatlah form yang menampilkan dropdown menu dan listbox dengan multiple selection. menampilkan dropdown menu
~~~
<!doctype html>

<html>

    <head>

        <title>Latihan 3</title>

        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">

        <link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/css/select2.min.css" rel="stylesheet" />

    </head>

    <body style="background: rgb(230, 173, 216)">

        <div style="width: 500px; padding: 15px; margin:200px auto;">

            <div class="form-group">

               <h1>Program Fakultas Studi</h1>

                <label>Universitas Pelita Bangsa</label>

                <select id="paket" name="paket[]" class="form-control" multiple="multiple">

                    <option value=""></option>

                    <option value="Teknik Informatika">Teknik Informatika</option>
                    <option value="Teknik Industri">Teknik Industri</option>
                    <option value="Teknik Lingkungan">Teknik Lingkungan</option>
                    <option value="Akuntansi">Akuntansi</option>
                    <option value="Manajemen">Manajemen</option>
                    <option value="Bisnis Digital">Bisnis Digital</option>

                </select>
            </div>
        </div>
</body>
</html>
~~~
![soal1](https://user-images.githubusercontent.com/81820421/115106869-6f38cd80-9f91-11eb-9b66-c64733c6c557.JPG)










