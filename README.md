#  Laporan Praktikum – **Lab 5 JavaScript**

##  Identitas

* **Nama:** Dedi Ramadhan
* **NIM:** 312410171
* **Kelas:** TI.24.A1
* **Mata Kuliah:** Pemrograman Web

---

##  Tujuan

1. Mengenal dasar penggunaan **JavaScript** dalam halaman HTML.
2. Mempelajari berbagai metode pemrograman JavaScript seperti event, fungsi, kondisi, form, dan DOM.
3. Mengimplementasikan JavaScript untuk interaktivitas pada halaman web.


##  Hasil dan Penjelasan Setiap Metode

###  **Kode Awal – Pengenalan JavaScript**

```html
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <title>Mengenal JavaScript</title> 
</head> 
<body> 
    <h1>Pengenalan JavaScript</h1> 
    <h3>Contoh document.write dan console.log</h3> 
    <script> 
        document.write("Hello World");
        console.log("Hello World"); 
    </script> 
</body> 
</html> 
```

📸 ![hasil](https://github.com/user-attachments/assets/2298f43c-fafa-4423-8da2-35b518c0afe7)

---

###  **Pemakaian Alert sebagai Property Window**

```html
<html>
<head>
  <title>alert box</title>
</head>
<body>
  <script>
    window.alert("ini merupakan pesan untuk anda");
  </script>
</body>
</html>
```

📸 ![alert](https://github.com/user-attachments/assets/14cd59b2-07ff-4fc1-a283-9d128a674dcb)

---

###  **Pemakaian Method dalam Objek**

```html
<html>
<head>
  <title>skrip javascript</title>
</head>
<body>
  percobaan memakai javascript:<br>
  <script>
    document.write("selamat mencoba javascript<br>");
    document.write("semoga sukses!");
  </script>
</body>
</html>
```

📸 ![method](https://github.com/user-attachments/assets/a272a9b1-c3c8-49da-80e4-e9a8a4989d7d)

---

###  **Pemakaian Prompt**

```html
<html>
<head>
  <title>pemasukan data</title>
</head>
<body>
  <script>
    var nama = prompt("siapa nama anda?", "masukkan nama anda");
    document.write("hai, " + nama);
  </script>
</body>
</html>
```

📸 ![prompt](https://github.com/user-attachments/assets/34a43891-99a5-45b6-b903-c6ee72dd97c1)
📸 ![prompt hasil](https://github.com/user-attachments/assets/6cda65c2-a5ab-4e94-9b3f-9b99c9e68561)

---

###  **Pembuatan Fungsi dan Pemanggilannya**

```html
<html>
<head>
  <title>contoh program javascript</title>
  <script>
    function pesan() {
      alert("memanggil javascript lewat body onload");
    }
  </script>
</head>
<body onload="pesan()">
</body>
</html>
```

📸 ![fungsi](https://github.com/user-attachments/assets/a1437187-926b-4509-9837-77918c3a3878)

---

###  **Operasi Dasar Aritmatika**

```html
<html>
<head>
  <title>contoh program javascript</title>
  <script>
    function test(val1, val2) {
      document.write("<br>perkalian : " + (val1 * val2));
      document.write("<br>pembagian : " + (val1 / val2));
      document.write("<br>penjumlahan : " + (val1 + val2));
      document.write("<br>pengurangan : " + (val1 - val2));
      document.write("<br>modulus : " + (val1 % val2));
    }
  </script>
</head>
<body>
  <input type="button" value="arithmetic" onclick="test(9,4)">
</body>
</html>
```

📸 ![aritmatika](https://github.com/user-attachments/assets/9ab8c25c-1413-402a-a3ab-799f20d39a99)
📸 ![aritmatika hasil](https://github.com/user-attachments/assets/2b3fa261-9ee9-46dc-9f72-6bbad22d1d0d)

---

###  **Seleksi Kondisi (if...else)**

```html
<html>
<head>
  <title>contoh if-else</title>
</head>
<body>
  <script>
    var nilai = prompt("nilai (0-100):", 0);
    var hasil = "";
    if (nilai >= 60)
      hasil = "lulus";
    else
      hasil = "tidak lulus";
    document.write("hasil: " + hasil);
  </script>
</body>
</html>
```

📸 ![if else](https://github.com/user-attachments/assets/c9d88feb-93f6-4bb3-b913-49292b5475c7)
📸 ![if else hasil]([https://github.com/user-attachments/assets/656a48a1-9ba5-4](https://github.com/user-attachments/assets/656a48a1-9ba5-4)
