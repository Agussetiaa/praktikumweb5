Langkah-langkah Praktikum
Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal javascript</title>
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
Output :

<img width="960" alt="Screenshot 2023-10-26 010400" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/247d828e-a826-4e06-a1c5-944d6a113dc0">

Javascrip Dasar
Pemakaian Alert sebagai property window.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alert box</title>
</head>
<body>
    <script language="javascript">
        window.alert("Ini sebuah pesan untuk anda")
    </script>
</body>
</html>
```
Output:

<img width="344" alt="Screenshot 2023-10-26 011619" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/ddc49d76-0b6a-4891-bd68-ee0246e1cf70">

Pemakaian method dalam objek
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>script javascript</title>
</head>
<body>
    Percobaan Memakai javascript : <br>
    <script language="javascript">
        document.write("Selamat Mencoba Javascript <br>");
        document.write("Semoga Sukses");
    </script>
</body>
</html>
```

Output:

<img width="484" alt="Screenshot 2023-10-26 012333" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/0dbaae35-caf6-43bc-bc94-bd38e88cd8d5">

Pemakaian Prompt

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pemasukan data</title>
</head>
<body>
    <script language="javascript">
        var nama = prompt("Siapa nama anda?", "Masukan nama anda");
        document.write("hai, " + nama )
    </script>
</body>
</html>
```

Output :

<img width="339" alt="Screenshot 2023-10-26 012843" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/4492bacf-d874-4110-8dfe-4d6d234d7915">

<img width="487" alt="Screenshot 2023-10-26 012859" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/25f0d095-7b5f-46d1-ad71-ff6e8ac7ca49">


Pembuatan fungsi dan cara pemanggilannya
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh program javascript</title>
    <script language = "javascript">
        function pesan() {
            alert ("Memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload= pesan()>
</body>
</html>
```

Output :

<img width="339" alt="Screenshot 2023-10-26 013658" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/cd2c95bd-259b-4ddd-825a-c26eafa3ba31">

Dasar Pemrograman Di Javascript
Operasi dasar aritmatika
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh program javascript</title>

    <script language="javascript">
        function test (val1, val2)
        {
            document.write("<br>" + "perkalian = val1*val2" + "<br>")
            document.write(val1*val2)
            document.write("<br>" + "pembagian = val1:val2" + "<br>")
            document.write(val1/val2)
            document.write("<br>" + "penjumlahan = val1*val2" + "<br>")
            document.write(val1+val2)
            document.write("<br>" + "pengurangan = val1-val2" + "<br>")
            document.write(val1-val2)
            document.write("<br>" + "modulus = val1%val2" + "<br>")
            document.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmatic" onclick=test(9,4)>
</body>
</html>
```

Output :

<img width="105" alt="Screenshot 2023-10-26 021442" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/562850e4-1c3b-4282-90d4-fa06620b470a">

<img width="473" alt="Screenshot 2023-10-26 021426" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/f70ba9b2-a0bd-428c-a50f-ad5108b877b5">


Seleksi kondisi (if..else)

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh if-else</title>
</head>
<body>
    <script language = "javascript">
        var nilai = prompt("nilai (0-100) :", 0);
        var hasil = "";
        if (nilai >= 60)
        hasil = "Lulus";
        else
        hasil = "Tidak Lulus";
        document.write("Hasil :" + hasil);
    </script>
</body>
</html>
```

Output :

<img width="341" alt="Screenshot 2023-10-26 022222" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/f5ddb5e2-0741-4e3d-858d-ae0c3e024d8a">

<img width="112" alt="Screenshot 2023-10-26 022550" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/365eace6-760d-4ddc-a376-1dbf61b586d9">

Penggunaan operator switch untuk seleksi kondisi
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh program javascript</title>
    <script language="javascript">
        function test()
        {
            val1 = window.prompt("Input nilai (1-9): ")
            switch (val1)
            {
                case "1":
                    document.write("bilangin Satu")
                    break
                case "2":
                    document.write("bilangin Dua")
                    break
                case "3":
                    document.write("bilangin Tiga")
                    break
                case "4":
                    document.write("bilangin Empat")
                    break
                case "5":
                    document.write("bilangin Lima")
                    break
                default:
                    document.write("bilangan lainnya")
                
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

Output :
1. Jika di isi

<img width="115" alt="Screenshot 2023-10-26 073950" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/ac19f2aa-e816-4322-a815-0c813825338a">

<img width="344" alt="Screenshot 2023-10-26 074725" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/83f95bfb-a989-4bdd-a3f3-565e8a8fa383">

<img width="163" alt="Screenshot 2023-10-26 074828" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/662f4c27-fdbf-4bf9-9691-3842fadd0257">

2. Jika tidak di isi

<img width="339" alt="Screenshot 2023-10-26 073922" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/a7867781-fd05-483c-930e-6081acc6abb8">

<img width="148" alt="Screenshot 2023-10-26 073935" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/29bca7ee-81ec-4a30-9013-f8353f7f0a9e">

Pembuatan Form
Form Input
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script language="javascript">
        function test () {
            var val1 = document.kirim.T1.value
            if (val1%2 == 0)
            document.kirim.T2.value="Bilangan genap"
            else
            document.kirim.T2.value="Bilangan ganjil"
        }
    </script>
</head>
<body>
    <from method="post" name="kirim">
        <p> BIL <input type="text" name="T1" size="20"> 
        Merupakan BIL <input type="text" name="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </from>
</body>
</html>
```

output :

<img width="478" alt="Screenshot 2023-10-26 202550" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/b0f8f397-dc97-4df7-a463-706132dc551e">

Form Button.
```
<!DOCTYPE html>
<html lang="en">
<head> 
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Object Document</title>
</head>
<body>
    <script language="javascript">
    function ubahwarnaLB(warna) {
        document.bgColor = warna;
    }
    function ubahwarnaLD(warna) {
        document.fgColor = warna;
    }
    </script>
    <h1>TES</h1>
    <from>
        <input type="button" value="Latar belakang hijau" onclick="ubahwarnaLB('green')">
        <input type="button" value="Latar belakang putih" onclick="ubahwarnaLB('white')">
        <input type="button" value="Text Kuning" onclick="ubahwarnaLD('yellow')">
        <input type="button" value="Text Biru" onclick="ubahwarnaLD('blue')">
    </from>
    <script language="javascript">
        document.write("dimodifikasi terakhir pada" + document.lastModified);
    </script>
</body>
</html>
```

Output :
- Klik latar belakang putih

<img width="479" alt="Screenshot 2023-10-26 204956" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/d4cffbea-d37f-45d4-b74c-abbe4d589a71">

- Klik latar belakang hijau

<img width="479" alt="Screenshot 2023-10-26 205010" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/87614e4d-fcf0-4ca3-9627-3b86301adef9">

- klik Text Kuning

<img width="479" alt="Screenshot 2023-10-26 205040" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/31a38986-5c5e-4945-b587-8ae8c395d1e8">

- Klik Text Biru

<img width="478" alt="Screenshot 2023-10-26 205052" src="https://github.com/Agussetiaa/praktikumweb5/assets/115542822/0e6f06fc-93f6-4a8a-9b06-eaba39487826">


HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
```
