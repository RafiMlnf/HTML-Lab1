## Lab1Web

## 1. Menyusun struktur HTML dan membuat judul Web

- Langkah awal dimulai dengan menyusun struktur standar HTML
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
    </head>
    <body>
  </html>
  ```
- Lalu menambahkan judul Web dengan menambahkan tag ```<title>``` dan menambahkan standarisasi meta bahasa dan simbol agar kompabiliti dan dapat diakses di berbagai perangkat dengan: ```<meta charset="UTF-8">``` pada isi header: ```<head>```.
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <title>Tag HTML Dasar</title>
      </head>
      <body>
  </html>
  ```
- ```<meta charset="UTF-8">``` Juga berguna untuk menghindari masalah encoding. Biasanya menyebabkan karakter yang salah ditampilkan atau berubah menjadi karakter aneh. Jika di cek di w3c tanpa menyertakan ini, hasilnya error.
  ![b1](https://github.com/RafiMlnf/Lab1Web/assets/115614668/eb9fec40-dbb0-4527-80ec-7cc79ad56d49)

- #### Ini adalah kode program pada langkah pertama
  ![image](https://github.com/RafiMlnf/Lab1Web/assets/115614668/40d72e91-fb2a-4900-b39a-f192ca245809)
- #### Tidak ada tampilan pada langkah pertama, karena hanya membuat struktur dan judul Web saja, jadi saat dibuka web tidak menampilkan apapun (hanya latar/background putih).
------------------------------------------------------------

## 2. Menambah isi berupa paragraf
- Langkah kedua, tambahkan deskripsi/komentar/paragraf atau isian yang sesuai dengan tugas pada modul pemrograman web, pada bagan struktur ```<body> ... </body>```.
  
  ![image](https://github.com/RafiMlnf/Lab1Web/assets/115614668/737a220d-846d-484a-8d62-79c3a48bb124)

- #### Ini adalah tampilan awal pada Web sebelum dimasukkan performatan teks, dan masih berupa teks biasa.
  ![a1](https://github.com/RafiMlnf/Lab1Web/assets/115614668/d348d60f-297d-4b0d-91c3-4bd5c9b2d56b)

------------------------------------------------------------

## 3. Menambahkan judul paragraf dan melakukan pemformatan teks
- Langkah ketiga. Sesuai intruksi modul, ubah tampilan teks pada web dengan melakukan pemformatan teks.
  
  ![image](https://github.com/RafiMlnf/Lab1Web/assets/115614668/2eb954b1-8046-411b-a3b6-a731f3076df6)

  |   Tag   | Fungsi |
  | ------- | -------------------------------------------------------------------------------------------- |
  | ```<.. align="...">``` | Berfungsi untuk mengatur posisi paragraf agar lebih rapi dan sesuai dengan kebutuhan dokumen |
  | ```<mark>``` | Memberi mark/penanda berwarna kuning                                                         |
  | ```<strong>``` | Selain menebalkan teks, juga memberi penekanan semantik dan dianggap penting                 |
  | ```<i>``` | Memiringkan teks                                                                             |
  | ```<u>``` | Memberi garis bawah pada teks                                                                |

- #### Ini adalah tampilan web setelah diberi pemformatan teks
  
  ![a3](https://github.com/RafiMlnf/Lab1Web/assets/115614668/6704b780-b1db-4774-88fb-229dcf0e333f)
  
- Kemudian saya ganti tanda kutip 2 dengan quotes pada line 12 dan 20 ```<p align="...">``` menjadi ```<p align=”...”>```, sehingga posisi alignment paragraf kembali ke default. Dengan kutip 2 juga bisa dengan memberi alignment left atau justify.
  
  ![a2](https://github.com/RafiMlnf/Lab1Web/assets/115614668/52a616c3-cba2-4e5c-a2bc-2ffb1cef8dbe)

------------------------------------------------------------

## 4. Menyisipkan / menambahkan gambar
- Pindahkan file gambar yang akan ditampilkan ke web ke folder yang sama dengan file html
- Beri sub judul gambar/paragraf ```<h3>Menambahkan Gambar</h3>```
- Kemudian ketik tag dibawahnya ```<img```
- ```html
  <img src="LOGO_UPB.png" width="200" title="Logo Universitas Pelita Bangsa" alt="LOGO_UPB">

  img src = "sumber gambar" isi dengan nama file gambar dan ekstensinya
  width   = "lebar gambar"
  title   = "judul gambar"
  alt     = "..." masukkan teks alternatif yang akan ditampilkan sebagai pengganti gambar jika tidak dapat dirender.
  ```
- Ini kode program setelah menyisipkan gambar
  
  ![03](https://github.com/RafiMlnf/Lab1Web/assets/115614668/13b1993e-f3da-4bc8-a3e6-891f0aa4e970)

- Maka tampilan web akan menampilkan gambar yang tadi disisipkan
  
  ![a4](https://github.com/RafiMlnf/Lab1Web/assets/115614668/7eb7e1d3-ac19-4b21-a194-c6c709a4a89c)

## 5. Menambah Hyperlink
- Tambahkan tag navigasi ```<nav>``` yang akan ditampilkan diatas header
- Dan tambahkan tag hyperlink ```<... href="link sumber">" - "</..>```. Isi ```" - "``` dengan teks alternatif teks agar link yang disematkan untuk hyperlink akan diganti dengan teks yang lebih sederhana
- Saya tambahkan hyperlink untuk pergi ke halaman 2 dan website google
- Tambahkan juga tag ```<hr>``` horizontal line, sebagai pembatas navigasi dan header
  ```html
  <nav>
      <a href="Lab1_tag_dasar.html">Dasar HTML</a>
      <a href="Lab1_hal2_dasar.html">Halaman 2</a>
      <a href="http://www.google.com">Halaman Web Eksternal Google</a>
  </nav>
  <hr>

  Dasar HTML           = Hyperlink ke halaman utama web
  Halaman 2            = Hyperlink ke halaman 2 web
  Web Eksternal Google = Hyperlink ke website google
  ```
- Ini adalah navigasi hyperlink yang akan ditampilkan di web
  
  ![a5](https://github.com/RafiMlnf/Lab1Web/assets/115614668/0b338592-a054-4303-9321-40ce42724deb)
  
  ------------------------------------------------------------
- ### Hasil akhir kode program dan tampilan web
  ![04](https://github.com/RafiMlnf/Lab1Web/assets/115614668/755b4d2d-0d84-48a1-a54a-b1b0237b12bf)

  ### Tampilan utama web
  ![a7](https://github.com/RafiMlnf/Lab1Web/assets/115614668/1b515787-728b-467a-8380-d25554fcc086)

  ### Tampilan halaman 2 web
  ![a6](https://github.com/RafiMlnf/Lab1Web/assets/115614668/bba98d54-da17-4942-9e84-be544282082d)
