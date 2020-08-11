# Intent
# Tugas intent modul 9 10 11

![Alt Text](hasil1.png)

# Modul 9
Pada modul ini digunakan untuk pindah dari satu activity ke activity lain
# Modul 10
Pada modul ini digunakan untuk pindah dari satu activity ke activity lain dengan membawa data
# Modul 11
Pada Modul ini digunakan untuk pindah ke halaman telepon

Memiliki tampilan kode sebagai berikut :

a. activity_main.xml

-code-

![Alt Text](1.JPG)

Linear Layout adalah jenis Layout dimana kita menempatkan 1 objek per baris atau kolom, vertical atau horizontal. 

Jadi di dalam setiap baris (vertical) atau kolom (horizontal) hanya ada 1 objek saja yang kita tempatkan.

-design-

![Alt Text](2.JPG)

b. tambahkan berkas dimen.xml

![Alt Text](3.JPG)

c.string.xml

disini kita bisa mengisi string yang diperlukan dan disii sudah ada beberapa string yang dibutuhkan dalam modul 9 dan berikutnya

![Alt Text](4.JPG)

d. MainActivity.java

Baris yang tertera berfungsi untuk memperkenalkan button yang sudah ditambahkan di layout activity_main.xml dan beberapa baris untuk menambahkan event onClick pada btn dengan java

![Alt Text](5.JPG)


![Alt Text](6.JPG)

e. membuat btnMoveActivity

package name > new > activity > empty activity >Finish

ubah Activity Name : MoveActivity untuk modul 9

- activity_move.xml

![Alt Text](7.JPG)

Relative Layout adalah Layout yang membebaskan kita untuk menempatkan objek-objek didalamnya dapat berada di atas,bawah,kiri,kanan objek lainnya atau bisa disebut dengan Relative, jadi ini merupakan Layout yang penataannya lebih bebas sehingga bisa di tata di mana saja.

hasilnya modul 9 adalah :

![Alt Text](hasil2.png)

Pada modul ini terdapat suatu objek Intent seperti berikut :

Intent(MainActivity.this,MoveActivity.class);

this digunakan untuk kelas asal sedangkan class digunakan untuk kelas tujuan

ubah Activity Name : MoveActivityWithData untuk modul 10

- activity_move_with_data.xml

tambahkan textviewer untuk menampilkan data yang dikirimkan dari activity asal

![Alt Text](8.JPG)

- MoveWithDataActivity.java

![Alt Text](9.JPG)

hasilnya modul 10 adalah :

![Alt Text](hasil3.png)

hasil modul 11 :

![alt text](hasil4.png)

Dalam modul ini terdapat kode

Uri.parse("tel:"+phoneNumber)

"tel:" berfungsi sebagai schema sedangkan phoneNumber adalah sebuah variabel


# Salsabilla Maurettasya A
# 39 - XI RPL 3







