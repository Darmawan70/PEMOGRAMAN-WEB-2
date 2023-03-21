# PEMOGRAMAN-WEB-2
Praktikum 2 <br>
AHMAD DARMAWAN<br>
TI.21.A3<br>
312110581<br>

# Code Php Dasar 1
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>PHP Dasar</title>
</head>
<body>
<h1>Belajar PHP Dasar</h1>
<?php
echo "Hello World";
?>
<br>
<h2>Menggunakan Variable</h2>
<?php
$nim = "312110581";
$nama = 'AHMAD DARMAWAN';
echo "NIM : " . $nim . "<br>";
echo "Nama : $nama";
?>
</body>
</html>
```
# Output
![Screenshot_1](https://user-images.githubusercontent.com/127670493/226687475-a5634295-9c4d-426d-a737-0671cc63edbb.png)

# Code Php Dasar 2
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PHP Dasar</title>
</head>

<body>
  <!-- Variabel $_GET -->
  <h2><b>Predefine Variable</b></h2>
  <?php
  $nama = 'DARMAWAN';
  echo 'Selamat Datang ' . $_GET['nama']
  ?>
</body>
</html>
```
# Output
![Screenshot_2](https://user-images.githubusercontent.com/127670493/226688094-51fd2c0b-04fa-46c1-b852-7945c8ad0c48.png)

# Code Php Dasar 3
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>

<body>
    <h2>Form Input</h2>
    <form method="post">
        <label>Nama: </label>
        <input type="text" name="nama">
        <input type="submit" value="Kirim">
    </form>
    <?php
    $nama = 'DARMAWAN';
    echo 'Selamat Datang ' . $_POST['nama'];
    ?>
</body>

</html>
```
# Output
![Screenshot_3](https://user-images.githubusercontent.com/127670493/226688468-87fd95df-c2fc-4237-b64c-1849211c4d42.png)

# Code Php Dasar 4
```
<! html DOCTYPE>
<html lang="en">

<Head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <Basic ></title>
</Head>

<body>
  <?php
  $gaji = 5000000;
  $pajak = 0.1;
  $THP = $pajak - ($gaji *  $pajak);
  Echo "Gaji sebelum pajak = Rp.  $gaji <br>";
  Echo "Gaji yang dibawa pulang = Rp.  $THP";
  ?>
</body>

</html>
```

# Output
![Screenshot_4](https://user-images.githubusercontent.com/127670493/226688752-0fff70d4-ef29-4c3c-ae57-37938032db8e.png)

# Code Php Dasar 5
```
<! html DOCTYPE>
<html lang="en">

<Head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <Basic ></title>
</Head>

<body>
  <h2>Kondisi If</h2>
  <?php
  $nama_hari = date("l");
  if ($nama_hari == "Senin") {
    Echo "Monday";
  } elseif ($nama_hari == "Kamis") {
    Echo "Thursday";
  } else {
    Echo "Sabtu";
  }
  ?>
</body>
```
# Output
![Screenshot_5](https://user-images.githubusercontent.com/127670493/226689467-5dca3368-d62f-4ca1-aa4f-5ed6c6d67838.png)

# Code Php Dasar 6
```
<h2>Kondisi Switch</h2>
<?php
$nama_hari = date("l");
Switch ($nama_hari) {
  case "Minggu":
    Echo "Sunday";
    Break;
  case "Senin":
    Echo "Monday";
    Break;
  case "Selasa":
    Echo "Tuesday";
    Break;
  Default:
    Echo "Selasa";
}
Echo "/$nama_hari";
?>
```
# Output
![Screenshot_6](https://user-images.githubusercontent.com/127670493/226690703-329ff7fa-5351-4c02-afc0-3cd1ddaa56dd.png)

# Code Php Dasar 7
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PHP Dasar</title>
</head>

<body>
  <h2>Perulangan For</h2>
  <?php
  echo "Perulangan 45 sampai 50 <br />";
  for ($i = 45; $i <= 50; $i++) {
    echo "Perulangan ke: " . $i . '<br />';
  }
  echo "Perulangan Menurun dari 50 ke 45 <br />";
  for ($i = 50; $i >= 45; $i--) {
    echo "Perulangan ke: " . $i . '<br />';
  }
  ?>
</body>

</html>
```

# Output
![Screenshot_7](https://user-images.githubusercontent.com/127670493/226690477-2647c4ab-b444-4231-bb9e-cce16361c69d.png)


# Code Php Dasar 8
```
<h2>Perulangan While</h2>
<?php
echo "Perulangan 15 sampai 20 <br />";
$i = 15;
while ($i <= 20) {
  echo "Perulangan ke: " . $i . '<br />';
  $i++;
}
?>
```

# Output
![Screenshot_8](https://user-images.githubusercontent.com/127670493/226691088-bb7fa2e5-afba-4925-8044-dd69c8abcb95.png)

# Code Php Dasar 9
```
<h2>Perulangan Do while</h2>
<?php
echo "Perulangan 30 sampai 50 <br />";
$i = 30;
do {
  echo "Perulangan ke: " . $i . '<br />';
  $i++;
} while ($i <= 50);
?>
```
# Output
![Screenshot_9](https://user-images.githubusercontent.com/127670493/226691490-9f8d3281-9a64-450c-a78f-2f6bd247c0ad.png)
