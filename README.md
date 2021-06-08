 # Praktikum 9: PHP Modular
# Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode. 

![Untitled](https://user-images.githubusercontent.com/56244029/121239135-08fe6600-c8c3-11eb-9d5e-edcd580dc33f.png)

 2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver
(htdocs)

![2](https://user-images.githubusercontent.com/56244029/121239275-3ba85e80-c8c3-11eb-8a7a-315926ffaa29.png)

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
# Langkah-langkah Praktikum
# Buat file baru dengan nama header.php
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
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

![3](https://user-images.githubusercontent.com/56244029/121240076-2bdd4a00-c8c4-11eb-955c-b5696f731504.png)

# Buat file baru dengan nama footer.php
```
            <footer>
                <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

![4](https://user-images.githubusercontent.com/56244029/121240231-4ca59f80-c8c4-11eb-9925-63d2ab6c2277.png)

# **Buat file baru dengan nama home.php**
```
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

![5](https://user-images.githubusercontent.com/56244029/121240363-6fd04f00-c8c4-11eb-87fe-f5d3cd435c7e.png)

# Buat file baru dengan nama about.php
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

![6](https://user-images.githubusercontent.com/56244029/121240465-9098a480-c8c4-11eb-98f7-5bde3915bd6e.png)

# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang
database, sehingga setiap halamannya memiliki template tampilan yang sama.

# Buat folder baru dengan nama lab9 pada docroot webserver
(htdocs)

![1](https://user-images.githubusercontent.com/56244029/121241012-216f8000-c8c5-11eb-96c5-55c16b978379.png)

# Buat file baru dengan nama koneksi.php pada folder (c:\xampp\htdocs\lab9)

![2](https://user-images.githubusercontent.com/56244029/121241189-5d0a4a00-c8c5-11eb-9d39-f8179d1400e3.png)

# Buat file baru dengan nama header.php pada folder (c:\xampp\htdocs\lab9)

![3](https://user-images.githubusercontent.com/56244029/121241395-9773e700-c8c5-11eb-8f6f-8f1e47a7d1cb.png)

# Buat file baru dengan nama footer.php pada folder (c:\xampp\htdocs\lab9)

![4](https://user-images.githubusercontent.com/56244029/121241759-fd606e80-c8c5-11eb-99cb-f1b2050a7756.png)

# Buat file baru dengan nama home.php pada folder (c:\xampp\htdocs\lab9)

![5](https://user-images.githubusercontent.com/56244029/121241947-31d42a80-c8c6-11eb-8369-399eb92db85c.png)

![6](https://user-images.githubusercontent.com/56244029/121241967-3698de80-c8c6-11eb-9d2d-37b6aa346741.png)

# Buat file baru dengan nama tambah.php pada folder (c:\xampp\htdocs\lab9)

![7](https://user-images.githubusercontent.com/56244029/121242280-9099a400-c8c6-11eb-8f40-2ca07317914c.png)

![8](https://user-images.githubusercontent.com/56244029/121242287-92fbfe00-c8c6-11eb-8d3e-9bea66307761.png)

![9](https://user-images.githubusercontent.com/56244029/121242298-95f6ee80-c8c6-11eb-88ac-d57efc3cd8b5.png)

# Buat file baru dengan nama hapus.php pada folder (c:\xampp\htdocs\lab9)

![10](https://user-images.githubusercontent.com/56244029/121242450-c6d72380-c8c6-11eb-82ef-83a6a39224ba.png)

# Buat file baru dengan nama syle.css pada folder (c:\xampp\htdocs\lab9)

![11](https://user-images.githubusercontent.com/56244029/121242705-11f13680-c8c7-11eb-9282-1127b352df41.png)
