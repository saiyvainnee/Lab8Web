# Lab8Web

# buat data barang di MYSQL
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/e826d320-5b25-41f0-8f58-bf2852c5b95b" />

# Buat file dengan nama koneksi php
```
<?php
$host  = "localhost";
$user = "root";
$pass = "";
$db = "latihan1";

$conn = mysqli_connect($host, $user, password: $pass, database: $db);
if ($conn == false ) {
    echo "koneksi ke server gagal.";
    die ();
} else echo "koneksi berhasil";
?>
```
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f1963f27-e8b3-4bcd-ac68-104f30dcb553" />
