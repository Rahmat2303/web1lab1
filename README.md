# web1lab1
## Belajar tag HTML

### Struktur HTML
Ini merupakan struktur HTML

![Gambar 1](screenshot/ss1.PNG)

Dan ini tampilannya di browser

![Gambar 2](screenshot/ss11.PNG)

### Membuat paragraf
Untu membuat paragraf pada HTML, menggunakan tag **<p>**
Ini tampilannya

![Gambar 3](screenshot/ss21.PNG)

Dan ini tampilannya di browser

![Gambar 4](screenshot/ss22.PNG)

Menyisipkan align=”center” dan align=”right” pada tag **<p>**

![Gambar 5](screenshot/ss31.PNG)

Dan ini hasilnya

![Gambar 6](screenshot/ss32.PNG)

### Menambahkan Judul
Untuk judul paragraf pertama menggunakan tag <h1> dan untuk judul paragraf yang kedua menggunakan tag <h2>
![Gambar 7](screenshot/ss41.PNG)

Ini tampilannya di browser
![Gambar 8](screenshot/ss42.PNG)

Terlihat perbedaanya, judul yang pertama lebih besar dari judul yang kedua.

### Memformat teks
Agar background teks menjadi warna kuning menggunakan tag <mark></mark>
Agar teks menjadi tebal menggunakan tag <b></b>
Agar teks menjadi miring menggunakan tag <i></i>
Agar teks mempunyai garis bawah menggunakan tag <u></u>

Ini gambarnya
![Gambar 9](screenshot/ss51.PNG)

Dan ini tampilannya di browser
![Gambar 10](screenshot/ss52.PNG)

###  Menyisipkan Gambar
Simpan file gambar di folder web1lab1
![Gambar 11](screenshot/ss61.PNG)

Sebelumnya tambahkan dulu judul dengan menggunakan tag <h3></h3>

Untuk bisa Menyisipkan gambar menggunakan tag <img>
di dalam tag <img> tersebut di sertakan src kemudian di isi nama file gambar.
Di sertakan juga width dan height untuk mengatur lebar dan panjang gambar.
Dan si sertakan title="Logo Universitas Pelita Bangsa" agar ketika gambar tidak muncul akan muncul tulisan Logo Universitas Pelita Bangsa.
Ini contoh kodingannya
![Gambar 12](screenshot/ss62.PNG)

Dan ini tampilannya di browser
![Gambar 13](screenshot/ss63.PNG)

### Menambahkan Hyperlink
Untuk menambahkan link navigasi menggunakan tag <a></a>
di dalam tag tersebut terdapat href yang diisi oleh nama file, kemudian di antara tag <a></a> diisi dengan nama link yang ingin digunakan. Dan tag <a></a> tersebut di buungkus oleh tag <nav></nav> kemudian dibawahnya ditambah tag <hr> agar muncul garis lurus.
![Gambar 14](screenshot/ss71.PNG)

Dan ini tampilannya di browser
![Gambar 15](screenshot/ss72.PNG)

### Jawab Pertanyaan Berikut
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
   error ketika terjadi kesalahan penulisan tag?
   Jawab :

2. Apa perbedaan dari tag "<p>" dengan tag "<br>", berikan penjelasannya!
    Jawab : Tag <p> merupakan tag untuk menuliskan paragraf, sedangkan tag <br> untuk membuat garis baru.

3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
    Jawab : atribut title merupakan tag ketika di sorot oleh mouse akan muncul tulisan yang diisi pada atribut title, namun tidak muncul ketika tidak disorot oleh mouse.
    Sedangkan atribut alt untuk mengetahui user ketika gambar tidak muncul akan muncul tulisan yang diisi pada atribut alt, contohnya Logo Universitas Pelita Bangsa
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
    proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
    Jawab : sebaiknya harus diisi semuanya agar gambar menjadi lebih enak dilihat. Karena ukuran gambarnya sudak di atur.
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
    _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
    Jawab :
    -Ketika atribut target diisi _blank, maka yang terjadi ketika kita mngklik link tersebut akan membuka tab baru.
    -Ketika atribut target diisi _self,  maka yang terjadi ketika kita mngklik link tersebut akan membuka di tab tersebut.
    -Ketika atribut target diisi _top,  maka yang terjadi ketika kita mngklik link tersebut masih akan membuka di tab baru dengan  layar penuh.
    -Ketika atribut target diisi _parent,  maka yang terjadi ketika kita mngklik link tersebut browser akan menampilkan semua dokumen yang dilink ke parent frame.
