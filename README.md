# Lab 7 Web : PHP Dasar

<table border="2" cellpading="10">
  <tr>
    <td><b>Nama</b></td>
    <td>Fahmi Eko Putro Santoso</td>
  </tr>
  <tr>
    <td><b>NIM</b></td>
    <td>312010046</td>
  </tr>
  <tr>
    <td><b>Kelas</b></td>
    <td>TI.20.A1</td>
  </tr>
  <tr>
    <td><b>MataKuliah</b></td>
    <td>Pemrograman Web</td>
  </tr>
</table>

# <b>Praktikum</b>

## <b>1. Membuka Visual Code & Install XAMPP </b>
![img1](image/0-1_prepare.PNG)

## <b>2. PHP Dasar</b>
![img2](image/0-2_mulai.PNG)

## <b>3. Variable PHP</b>
![img3](image/0-3_variable.PNG)

## <b>4. Predefine Variable $_GET</b>
![img4](image/0-4_Predefine-V.PNG)

## <b>5. Form Input</b>
![img5](image/0-5_form-input.PNG)

## <b>6. Operator</b>
![img6](image/0-6_operator.PNG)

## <b>7. Klausul If</b>
![img7](image/0-7_if.PNG)

## <b>8. Switch</b>
![img8](image/0-8_switch.PNG)

## <b>9. Perulangan For</b>
![img9](image/0-9_for.PNG)

## <b>10. Perulangan While</b>
![img10](image/0-10_while.PNG)

## <b>11. Perulangan Dowhile</b>
![img11](image/0-11_dowhile.PNG)

# TUGAS
<b>1. Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang  berbeda-beda sesuai pilihan pekerjaan.</b><br>
# Jawaban: <br>

- Kode Awal, tanpa php.
![img12](image/1-kode.PNG)<br><br>

- Kemudian tambahkan kode PHP, dan jalankan.

- Setelah memilih PHP Developer
![img13](image/2-s1.PNG)<br><br>

- Setelah memilih IT Support
![img14](image/2-s2.PNG)<br><br>

- Setelah memilih Network Engineer
![img15](image/2-s3.PNG)<br><br>

- Method ``POST`` tidak akan menampilkan nilai di url, lebih aman dari ``GET``.
- Jika belum menekan ``Kirim``, perubahan takan terjadi.
- Tiap input dan pilihan menyimpan nilai, di file program itu sendiri. <i>peletakan di ``<form action="" ..></i>.
- Nama diambil dari atribut ``name=nama`` pada kode html.
- Penentuan usia, dimulai dengan penanggalan saat ini ``$today`` dikurangi dengan tanggal lahir pengguna ``$date_user``. Kemudian ambil tahunnya saja. ``->y``
- Versi awal ini dibuat pada, ``17-05-2022``. Sehingga jika dihitung dengan tanggal lahir pada gambar tersebut, belum genap 20.
- Pilihan pekerjaan dengan menggunakan array.
    - Array pertama berisi profesi ``$job_array``
    - Array kedua berisi gaji ``$salary_array``
- Kemudian, pengguna akan memilih. Dimulai dari angka <b>0, 1, dan 2.</b>
- Terakhir, tampilkan hasil seluruh proses dengan ``echo``
