# Modul7PHP
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(261).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(262).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(263).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(266).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(265).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(264).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(269).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(268).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(267).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(270).png)
![alt text](https://github.com/Nesta2002/Modul7PHP/blob/master/Screenshot%20(271).png)

1. Berikan contoh kode keneksi untuk ke database pd php?
      $connect = mysqli_connect($host, $uname, $pass, $db);

      if (!$connect) {
         echo "Koneksi ke database gagal : " . mysqli_connect_error();
      }
2. Bagaimana cara anda membuat database pada phpMySQl!
      1. Silakan login ke cPanel
      2. Kemudian klik menu MySQL Databases yang berada pada kolom Databases
      3. Masukkan nama database baru pada kolom New Database kemudian tekan tombol Create Database untuk membuat database baru. 
      4. Silakan kembali lagi ke halaman sebelumnya dengan menekan tombol Go Back.
      5. Tambahkan user baru pada bagian Add New User, isi nama user pada kolom Username, beserta password pada kolom Password, kemudian klik tombol Create User untuk membuat user baru.
      6. Setelah itu klik Go Back untuk kembali ke halaman sebelumnya.
      7. Jika database dan user sudah Anda buat, selanjutnya adalah menambahkan user pada database. Pada bagian Add User To Database silakan pilih user dan database melalui menu drop down yang telah Anda buat, kemudian klik tombol Add untuk menyimpan perubahan.
      8. Silakan centang pilihan ALL PRIVILEGES kemudian tekan tombol Make Changes untuk menyimpan perubahan.
3. Berikan code query untuk menampilkan sebuah data yang ada pada ke database?
      "SELECT * FROM dosen";
4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?
      "UPDATE dosen SET nama_dosen = '$nama_dosen', telp = '$telp' WHERE id_dosen = $id_dosen";
5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?
      "DELETE FROM dosen WHERE id_dosen = '$id_dosen'";
