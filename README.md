# Struktur Kontrol PHP

Struktur kontrol dalam bahasa pemrogaman adalah suatu perintah yang kita gunakan untuk mengatur jalannya suatu program. Dengan struktur kontrol kita bisa mengatur
bagaimana jalannya program yang kita kehendaki. Contoh struktur kontrol adalah if-else, switch, for, foreach, while, do-while.

Struktur kontrol dibagi menjadi 2, yaitu struktur kontrol keputusan dan struktur kontrol perulangan
- Struktur kontrol keputusan, digunakan untuk memutuskan jika suatu kondisi terjadi.
- Struktur kontrol perulangan, digunakan untuk mengulang suatu perintah sesuai kehendak kita.


### Struktur Kontrol Keputusan

#### IF
IF, dijalankan untuk pengambilan keputusan, digunakan untuk memeriksa suatu blok code dijalankan atau tidak.

```PHP
if (kondisi == true) {
    //perintah
} elseif {
    //perintah
} else {
    //perintah
}
```
- elseif, merupakan pilihan jika suatu kondisi ditemukan.
- else, dijalankan jika kondisi salah.

#### Switch
SWITCH, biasanya digunakan untuk mencocokan suatu pilihan yang disimpan dalam variable.

```PHP
switch ($variable) {
	case pilihan1:
    	//perintah
        break;
    case pilihan2:
    	//perintah
        break;
    case pilihan3:
    	//perintah
        break;
    default:
    	//perintah
        break;
}
```
- jumlah case tergantung berapa banyak pilihan yang kita gunakan.


### Struktur Kontrol Perulangan

#### For
FOR, digunakan untuk mengulang suatu kondisi sampai nilainya false, for digunakan apabila kita tahu dengan pasti sampai berapa perulangan yang kita butuhkan.
```PHP
for (inisiasi; kondisi; iterasi) {
    //perintah
}
```
- inisiasi biasa diisi untuk mendeklarasi variable, untuk awal dari sebuah perulangan.
- kondisi digunakan untuk mengecek apakah suatu kondisi bernilai true.
- iterasi dijalankan setiap akhir dari satu kondisi.

#### Foreach
FOREACH, digunakan untuk memecah suatu array.
```PHP
foreach ($array as $key => $isi) {
    //perintah
}
```

#### While
While, kegunaannya sama seperti for, tapi while digunakan apabila kita tidak tahu pasti berapa perulangan yang akan dieksekusi.
While dibagi menjadi 2 yaitu, while dan do while, bedanya do while adalah apapun kondisinya do while akan di jalankan sekali di awal.

##### While
```PHP
while (kondisi) {
    //perintah
}
```
##### Do While
```PHP
do {
    //perintah
} while (kondisi);
