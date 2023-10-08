# praktikum_pemweb1
# Praktikum 1 Pemrograman Web
Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab1_tag_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

## 1.Membuat Paragraf
```
<!-- Ini adalah paragraf pertama -->
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
HTML.</p>
<!-- Ini adalah paragraf kedua -->
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
tag dasar html.</p>
```
![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/35150113-e658-4b10-a3b2-ede79326ae0e)


## 2.Menambahkan Judul
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>
<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/16888158-2513-4c69-9237-4de94c18c105)


## 3.Memformat teks
```
 <center>
    <!-- judul paragraf pertama -->
    <h1>Belajar Dasar HTML</h1>
    </center>   
    <p style="text-align: center;">Kami sedang belajar <mark>HTML dasar,</mark> pada matakuliah <b>Pemrograman Web</b>
        di Prodi <I>Teknik Informatika </I> <Universitas> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama
        yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
        tag-tag dasar HTML.</p>

    <center>
    <!-- judul paragraf kedua -->
    <h2>Paragraf Pada HTML</h2>
    </center>
    <p style="text-align: right;">Ini merupakan sebuah paragraf yang terdiri dari beberapa
        kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
        dengan menggunakan tag dasar html.</p>
```

![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/2663cd78-b08e-403b-916e-055721a36fc2)


## 4.Menyisipkan Gambar
```
 <center>
    <h3>Menambahkan Gambar</h3>
    </center>

    <center>
    <img src="LogoUpb.png" width="250" title="Logo Univeritas Pelita Bangsa" >
    </center>
```

![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/c2474cdd-4eb2-4ec1-9637-ac0795e45882)


## 5. Menambahkan Hyperlink
```
 <nav>
        <a href="latihan HTML Pemrograman Web.html">Dasar HTML</a>
        <a href="halaman2.html">Halaman 2</a>
        <a href="http://www.google.com">Halaman Web Eksternal Google</a>
        </nav>
    <hr>
```

![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/bd4a7f6c-137c-4497-81e2-0dfac1a61529)


## Halaman 2

![image](https://github.com/RadjaAzukio/Praktikum_PemWeb1/assets/115551911/0bcb34a3-e506-4a2d-a507-73ddcd26f811)



## Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?
```
Ketika saya salah dalam penulisan tag img yang seharusnya <img> menjadi </img>, gambar yang saya ingin tampilkan menjadi tidak tampil dalam web/browser.
```

2. Apa perbedaan dari tag `<p>` dengan tag `<br>`, berikan penjelasannya!
```
tag <br> melompati satu line cocok untuk memulai paragraf baru sedangkan tag <p> seperti menekan enter di software document editor 
```

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
```
Perbedaan atribut title dan alt yaitu pada gambar yang dihasilkan. Ketika gambar berhasil ditampilkan maka akan terlihat sebuah title, sedangkan jika gambar gagal ditampilkan maka akan menampilkan teks dalam atribut alt tersebut
```

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
```
Untuk menampilkan gambar yang proporsional sebaiknya kedua attribut tersebut diisi sesuai dengan ukuran yang kita inginkan. Dengan mengatur kedua ukuran tersebut kita dapat menyesuaikan gambar dengan lokasi penempatan gambar tersebut.
```

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
Nilai _blank akan membuka link/halaman di tab baru.
Nilai _self akan membuka link/halaman di tab saat ini.
Nilai _top membuka link/halaman dan membatalkan semua frame.
Nilai _parent membuka link/halaman pada parent frame.
``
