# lab1-web
# Lab 1 HTML Dasar

### Langkah 1: Struktur Dasar HTML
- Membuat file HTML dasar dengan nama `lab1_tag_dasar.html`.
- <!DOCTYPE html>
<html>
<head>
    <title>tag HTML Dasar</title>
</head>
<body>
    <!--Ini adalah paragraf pertama--> 
    <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
     Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami
     dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
     tag-tag dasar HTML.</p>
    <!--Ini adalah paragraf kedua--> 
    <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang
    saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan
    menggunakan tag dasar HTML.</p> 
</body>
</html>

![image](https://github.com/user-attachments/assets/32e6e384-9156-47eb-be84-85dcc3cde70a)
# disini kita akan melakukan penambahan align="center": Teks akan rata tengah.

<!DOCTYPE html>
<html>
<head>
    <title>tag HTML Dasar</title>
</head>
<body>
    <!--Ini adalah paragraf pertama--> 
    <p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
     Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami
     dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
     tag-tag dasar HTML.</p>
    <!--Ini adalah paragraf kedua--> 
    <p align="center">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat
     yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan
     menggunakan tag dasar html.</p> 

</body>
</html>

![image](https://github.com/user-attachments/assets/f2ad22c1-541d-4a5b-a548-670580af0851)
#align="justify": Teks akan rata kiri dan kanan.
#align="left": Teks akan rata kiri.
#align="right": Teks akan rata kanan.








### Langkah 2: Menambahkan Judul dan Paragraf
<!DOCTYPE html>
<html>
<head>
    <title>tag HTML Dasar</title>
</head>
<body>
    <!--judul paragraf pertama--> 
    <h1>Belajar Dasar HTML</h1>
    <!--paragraf pertama dengan teks diratakan di tengah-->
    <p align="center">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi
    Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami
    dapat adalah membuat tampilan web sederhana dalam rangka mengenal 
    tag-tag dasar HTML.</p>
    <!--judul paragraf kedua--> 
    <h2>Paragraf pada HTML</h2>
    <!--paragraf kedua dengan teks diratakan di tengah-->
    <p align="center">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat
    yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan
    menggunakan tag dasar HTML.</p> 

</body>
</html>

![image](https://github.com/user-attachments/assets/c8ebc429-6981-4fc2-97c5-f297673f08e7)
#disini kita tau bahwa judul pertama lebih besar dari pada judul kedua,
#biasanya untuk mengumpulkan conten menjadi bagian-bagian kecil




### Langkah 3: Memformat teks
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
    <!--judul paragraf pertama--> 
    <h1>Belajar Dasar HTML</h1>
    <!--paragraf pertama dengan pemformatan teks-->
    <p align="justify">
        Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah <b>Pemrograman Web</b> di Prodi 
        <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa.</u> Pelajaran pertama yang kami dapat adalah 
        membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <!--judul paragraf kedua--> 
    <h2>Paragraf pada HTML</h2>
    <!--paragraf kedua dengan pemformatan teks-->
    <p align="justify">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung 
        sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar <b>html</b>.
    </p>

</body>
</html>

![image](https://github.com/user-attachments/assets/0997707f-ef4f-4974-89ac-85c6ce4c08f9)
#Tag <mark>: Menyoroti teks "HTML dasar", membuatnya terlihat lebih mencolok.
#Tag <b> untuk Menjadikan teks "Pemrograman Web" dan "html" menjadi tebal, menonjolkan informasi penting.
#Tag <i> untuk Menjadikan "Teknik Informatika" menjadi miring, menonjolkan penekanan yang berbeda.
#Tag <u> untuk Menambahkan garis bawah pada "Universitas Pelita Bangsa", memberikan penekanan tambahan.
#Atribut align="justify" untuk Meratakan teks dalam paragraf agar terlihat lebih rapi di kedua sisinya.







### Langkah 4: Menambahkan gambar
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
    <!--judul paragraf pertama--> 
    <h1>Belajar Dasar HTML</h1>
    <!--paragraf pertama dengan pemformatan teks-->
    <p align="justify">
        Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah <b>Pemrograman Web</b> di Prodi 
        <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa.</u> Pelajaran pertama yang kami dapat adalah 
        membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <!--judul paragraf kedua--> 
    <h2>Paragraf pada HTML</h2>
    <!--paragraf kedua dengan pemformatan teks-->
    <p align="justify">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung 
        sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar <b>html</b>.
    </p>
    <!--Menambahkan Gambar-->
    <h3>Menambahkan Gambar</h3>
    <img src="image.png" title="Logo Universitas Pelita Bangsa" width="200px">

</body>
</html>

![image](https://github.com/user-attachments/assets/b6507865-041c-42e0-8bf6-ebaa1e296277)
#digunakan atribut witdh dan height dengan nilai integer yang disesuaikan. 







###  langkah 5: menambah hyperlink
<!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
</head>
<body>
    <!--menambahkan link navigasi--> 
    <nav> 
        <a href="lab1_tag_dasar.html">Dasar HTML</a> 
        <a href="lab1_halaman2.html">Halaman 2</a> 
        <a href="http://www.google.com">Halaman Web Eksternal Google</a> 
     </nav>
     <hr> 
    <!--judul paragraf pertama--> 
    <h1>Belajar Dasar HTML</h1>
    <!-- paragraf pertama dengan pemformatan teks -->
    <p align="justify">
        Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah <b>Pemrograman Web</b> di Prodi 
        <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa.</u> Pelajaran pertama yang kami dapat adalah 
        membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.
    </p>
    <!--judul paragraf kedua--> 
    <h2>Paragraf pada HTML</h2>
    <!--paragraf kedua dengan pemformatan teks-->
    <p align="justify">
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung 
        sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar <b>html</b>.
    </p>
    <!--Menambahkan Gambar-->
    <h3>Menambahkan Gambar</h3>
    <img src="image.png" title="Logo Universitas Pelita Bangsa" width="200px">

</body>
</html>

![image](https://github.com/user-attachments/assets/c20443e8-769f-405c-99c7-a3a7a6c0ebba)
#disini saya membuat halam file lagi dengan nama lab1_halaman2 lalu saya isi dokumen


