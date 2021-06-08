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

