# praktikum 1 - pemrograman web

``` 
farhan afrizal m
311910609
ti.19.a.2
universitas pelita bangsa 
```
# langkah 1
## Buka VS Code dan buat file HTML baru. Setelah itu buat struktur dasar HTML
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

</body>
</html>
```
![image](https://user-images.githubusercontent.com/57083770/113126787-38994e00-9242-11eb-903a-1516321b29d4.png)

# LANGKAH 2
## Membuat 2 buah paragraf dan atur atribut paragraf (Rata Kiri / Rata Kanan / Rata Tengah / Sama Rata)
```
<!-- Ini adalah paragraf pertama -->
<p align="center">Kami sedang belajar \HTML dasar, pada matakuliah Pemrograman
    Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>

<!-- Ini adalah paragraf kedua -->
<p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa
    kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
    dengan menggunakan tag dasar html.</p>
```    
![image](https://user-images.githubusercontent.com/57083770/113127135-988ff480-9242-11eb-8c61-7178680cc48c.png)

# LANGKAH 3
## Menambahkan judul menggunakan Tag Heading (h1, h2, h3, h4, h5, h6). Semakin besar angka Tag Heading, Semakin kecil ukuran Headingnya.
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```
![image](https://user-images.githubusercontent.com/57083770/113127358-e0168080-9242-11eb-910d-93f7c9dfb484.png)

# LANGKAH 4
## Memformat Teks menggunakan format-format teks yang ada seperti ```<b>, <strong>, <i>, <em>, <mark>, <small>, <dell>, <ins>, <sub>, dan <sup>.```

```<p align="left">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman
    Web</b> di Prodi <i>Teknik Informatika</i> <ins>Universitas Pelita Bangsa</ins>. Pelajaran pertama
    yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
    tag-tag dasar HTML.</p>
```
![image](https://user-images.githubusercontent.com/57083770/113127764-56b37e00-9243-11eb-8044-ec6ffd26ad08.png)

# LANGKAH 5
## Menyisipkan Gambar dan mengatur ukuran gambar. Sebelum menyisipkan gambar, file HTML yg sudah dibuat dijadikan satu bersama dengan gambar yg akan disisipkan.
![image](https://user-images.githubusercontent.com/57083770/113128155-b3af3400-9243-11eb-97ce-bad157b81168.png)
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>
<!-- menambahkan gambar pada dokumen -->
<img src="LOGO_UPB.png" width="200" title="Logo Univeritas Pelita Bangsa">
```
![image](https://user-images.githubusercontent.com/57083770/113128275-d5a8b680-9243-11eb-87c3-f4d6555501e8.png)

# langkah 6
## Menambahkan Hyperlink. Tambahkan hyperlink pada dokumen sebelum heading 1.
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```
![image](https://user-images.githubusercontent.com/57083770/113128622-31733f80-9244-11eb-882d-7df8e369d704.png)

# LANGKAH 7
## Membuat halaman ke 2 yg akan terhubung dengan halaman pertama menggunakana Hyperlink.
```
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>

<h1>Halaman Ke 2</h1>

<p align="justify">Ini adalah halaman kedua.</p>

</body>
</html>
```
![image](https://user-images.githubusercontent.com/57083770/113129026-a34b8900-9244-11eb-87b4-36c2d748136a.png)

# Jawab Pertanyaan Berikut
## 1.Lakukan perubahan pada code sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
   ```Ada error ketika saya salah penulisan Heading  <h1> tidak ditutup dengan </h1> jadi tidak terjadi perubahan.```

## 2.Apa perbedaan dari tag ```<p>``` dengan tag ```<br>``` berikan penjelasannya!
``` Dari hasil praktek saya sendiri, perbedaan  tag <br> jarak enter nya lebih jauh 1 line dibandingkan
dengan tag <p> yg jarak enter nya tidak terlalu jauh.
```
## 3.Apa perbedaan atribut ```title``` dan ```alt``` pada tag ```<img>```, berikan penjelasannya!
```atribut tittle pada tag <img> digunakan untuk memberi judul pada gambar yg disisipkan, sedangkan
atribut alt pada tag <img> digunakan untuk memberi deskripsi pada gambar yg disisipkan
```
## 4.Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```Untuk mempertahankan proporsi gambar, namun tetap membuat gambar menjadi besar/kecil, cantumkan
hanya salah satu atribut saja (width saja atau height saja, namun tidak keduanya). Misalkan
jika kita menetapkan atribut width=200px (tanpa mencantumkan height), maka web browser akan
menampilkan gambar dengan lebar 200px, dan menghitung secara otomatis tinggi gambar agar gambar
tetap proporsional.
```
## 5.Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai antribut tersebut? 
```Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
```
