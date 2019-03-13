# Modul7Bag1-2
1. Berikan contoh kode keneksi untuk ke database pd php?

   Jawab :mysqli_connect($host, $uname, $pass, $db);

2. Bagaimana cara anda membuat database pada phpMySQl!

   Jawab : Pertama Silahkan Buka PhpMyAdmin. Pada menu Database, silahkan masukkan nama database yang diinginkan, kemudian klik Create. 

3. Berikan code query untuk menampilkan sebuah data yang ada pada ke database?

   Jawab : 
   
   SELECT  * FROM nama tabel WHERE primarykey field = kriteria
   
   contoh :
   $query = "SELECT * FROM dosen";
   
4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?

   Jawab : 
   
   UPDATE nama tabel SET nama field = isi field WHERE primarykey field = kriteria
   
   contoh: 
   $query = "UPDATE dosen SET nama_dosen = '$nama_dosen', telp = '$telp' WHERE id_dosen = $id_dosen";

5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?

   Jawab : 
   
   DELETE nama tabel WHERE primarykey field = kriteria
   
   contoh: $query = "DELETE FROM dosen WHERE id_dosen = $id_dosen";
   
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul7Bag1-2/blob/master/hasil/latihan%201.PNG)

![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul7Bag1-2/blob/master/hasil/latihan%202.PNG)

![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul7Bag1-2/blob/master/hasil/latihan%203.JPG)

![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul7Bag1-2/blob/master/hasil/latihan%204.JPG)

![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul7Bag1-2/blob/master/hasil/latihan%205.JPG)
