# Pengenalan-Keamanan-Jaringan
## Daftar Isi
- [Pengenalan Keamanan Jaringan](#pengenalan-keamanan-jaringan)
- [Web Exploitation](#web-exploitation)
- [Cryptography](#cryptography)
- [Forensic](#forensic)
- [Reverse Engineering](#reverse-engineering)
- [Binary Exploitation](#binary-exploitation)

## Pengenalan Keamanan Jaringan
Keamanan Jaringan adalah materi tentang mengetahui suatu kelemahan sebuah program atau aplikasi yang berjalan. Dalam melakukan pencarian kelemahan tersebut dapat melalui berbagai macam <i>tools</i>. Terdapat berbagai metode dalam melakukan pencarian kelemahan yaitu <i>Black box</i> dan <i>white Box</i>.

- <b>Black box</b> adalah metode dengan menggunakan program atau aplikasi tanpa mengetahui <i>source code</i>. Metode ini melakukan pendekatan <i>user</i> secara umum, dengan melihat respon dari perintah yang dimasukan user.
- <b>White box</b> adalah metode dengan melihat <i>source code</i> dari program atau aplikasinya. Metode ini melakukan pendekatan <i>developer</i>, dengan cara ini kita akan mencari kelemahan berdasarkan alur program dan algoritmanya.

Dalam dunia industri kita juga mengenal istilah <b>Red Team</b> dan <b>Blue Team</b>. Dua tim ini digunakan untuk meningkatkan keamanan dari program yang dikerjakan dengan tugas, <b>Red Team</b> akan melakukan berbagai skenario penyerangan sedangkan <b>Blue Team</b> melakukan analisis untuk meningkatkan keamanan program tersebut.
## Web Exploitation
## Cryptography
<i>Cryptography</i> adalah materi yang mengulas tentang jenis-jenis sandi yang digunakan untuk menyamarkan informasi/pesan. Pada perang dunia ke-2 tentara Nazi menyebarkan informasi kepada seluruh pasukannya melalui udara dan dapat diterima oleh sembarang orang. Namun dalam pengirimannya, pesan tersebut telah dienkripsi dengan menggunakan mesin [Enigma](https://en.wikipedia.org/wiki/Enigma_machine). Sehingga walaupun pesannya diterima oleh orang lain, isi pesan tersebut tidak dapat diperoleh. <i>Cryptography</i> telah berkembang jauh sebelumnya, hal itu dapat dibuktikan dengan adanya [<i>Caesar chiper</i>](https://en.wikipedia.org/wiki/Caesar_cipher#History_and_usage) yaitu teknik mengganti huruf dalam pesan dengan 13 huruf setelahnya. Contohnya huruf A menjadi N dan huruf Z menjadi M. Dua contoh tersebut menggunakan <i>Symmetric-key</i>, artinya untuk melakukan <i>encrpytion</i> dan <i>decryption</i> harus menggunakan <i>key</i> yang sama. Sedangkan <i>Asymmetric-key</i> menggunakan <i>key</i> yang berbeda dalam proses <i>encrpytion</i> dan <i>decryption</i>. Contoh sederhananya adalah <i>public key</i> dan <i>private key</i>, dimana <i>public key</i> digunakan untuk melakukan enkripsi dan <i>private key</i> digunakan untuk dekripsi. Untuk lebih pahamnya dalam melihat contoh video berikut [ini](https://www.youtube.com/watch?v=AQDCe585Lnc).<br>
Tantangan dalam mempelajari topik ini adalah, banyaknya algoritma ekripsi yang ada. Sehingga kita diharapkan dapat memahami algoritma dari setiap enkripsi, selain itu kalian juga akan mempelajari <i>Poly-Alphabetic Cipher, Transposition Cipher, Substitution Cipher, </i>dan <i>Polygrammic Cipher</i>.
## Forensic
<i>Forensic Digital</i> adalah cabang yang mempelajari bagaimana cara untuk mengumpulkan informasi dari sebuah data digital. Salah satu contoh sederhananya, bagaimana kita dapat mengambil informasi dari sebuah <i>memory dump</i> yang telah disediakan. Kadang dalam kategori <i>Forensic</i> terdapat beberapa soal yang sebenarnya merupakan kategori <i>Steganografi</i>. Hal ini dikarenakan <i>Steganografi</i> adalah ilmu untuk menyembunyikan informasi kedalam sebuah media. Selain itu terdapat juga beberapa kategori <i>Networking</i> seperti soal yang mengharuskan kita untuk mendapatkan informasi dari sebuah <i>network packet</i> yang nantinya kita analisis. File yang akan kita analisis dapat berupa file teks, gambar, bahkan audio. Untuk itu dalam kategori ini kita akan lebih bergantung dengan penggunaan <i>tool</i> yang telah tersedia. Dalam persoalan nyata, <i>forensic digital</i> bukanlah perkara mudah karena kita harus memperhatikan kaidah dalam memperlakukan alat bukti dari sebuah kejadian.<br>
Kegiatan <i>Forensic</i> akan dilakukan setelah sebuah <i>incident</i> terjadi. Biasanya yang akan mengurus barang bukti pertama kali adalah bagian <i>internal</i>. Diharapkan ketika penanganan pertama tidak terjadi perusakan barang bukti.
## Reverse Engineering
## Binary Exploitation