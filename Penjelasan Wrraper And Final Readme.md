# PBO-teori
# 1. WRAPPER CLASS

Wrapper Class merupakan tipe data bawaan Java yg berupa objek. Wrapper class ini
menyediakan mekanisme untuk membungkus (wrap) tipe data primitive menjadi sebuah
objek sehingga bisa digunakan dalam kegiatan yg berhubungan dengan objek, Wrapper 
Class bersifat immutable yaitu apabila ada 2 buah variabel yg memegang nilai yg
sama, maka satu variable diganti nilainya maka yg lain pun tidak ikut berubah
nilainya.

a. Integer merupakan wrapper di dalam java yaitu kata primitif dari tipe data int.
Dan variabel a diatas merupakan sebuah objek baru dari tipe data integer dan yang
langsung diberi nilai 10.
b. int merupakan bilangan bulat yang sering dipakai dalam pemrograman. Pada
program diatas tipe data int juga membuat sebuah objek baru dengan nama i yang
kemudian memanggil tipe data integer dengan objeknya yaitu a dan kemudian
memanggil nilai nya.
c. Selanjutnya System.out.println (SOP) mencetak nilai dari tipe data diatas
dengan memanggil objek i.
d. Dan pada output kita dapat melihat bahwa nilai yang dicetak adalah 10 yaitu
nilai dari primitif diatas yaitu integer.


# 2. PERBEDAAN FINAL, FINALY, DAN FINALIZE

apa bedanya final, finally dan finalize?

*final adalah keyword untuk mendeklarasikan bahwa sebuah variabel/atribut tidak
dapat diubah lagi isinya (konstan), jika final disebutkan di method, artinya
method tersebut tidak dapat di override oleh subclassnya, jika final disebutkan
di class, artinya class tersebut tidak dapat diturunkan lagi

*finally merupakan tag dalam try-finally yang digunakan untuk memastikan bahwa
kode didalam finally akan dieksekusi walaupun dalam try sukses / gagal.

*finalize merupakan methode kelas Object yang dieksekusi saat garbace collection
menghapus sebuah object yang sudah tidak terpakai.
