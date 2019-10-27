## TUGAS 9 NETPRO ##

<p align="center"
  <a><strong>  NAMA KELOMPOK :  </strong></a> 
</p>
<p align="center">
  <a>  I Putu Surya Baratha (1301188566)  </a> 
</p> 

<p align="center">
  <a>  Muhammad Risdham Nur A.P (1301188603)  </a> 
</p>

<p align="center">
  <a>  Sella Tresnasari  (1301188565)  </a> 
</p> 

## HASIL RUNNING PHPLOY ##

[![Screen-Shot-2019-10-26-at-22-35-19.png](https://i.postimg.cc/HWJSN4sL/Screen-Shot-2019-10-26-at-22-35-19.png)](https://postimg.cc/7bkMGzzv)

<p align="center">
  <a> Gambar 1 </a>
</p>

[![Screen-Shot-2019-10-26-at-23-37-27.png](https://i.postimg.cc/KYqNq46L/Screen-Shot-2019-10-26-at-23-37-27.png)](https://postimg.cc/SX9CjQNN)

<p align="center">
  <a> Gambar 2 </a>
</p>

[![Screen-Shot-2019-10-27-at-12-54-52.png](https://i.postimg.cc/8kxVXmMp/Screen-Shot-2019-10-27-at-12-54-52.png)](https://postimg.cc/t7dfYPBw)

<p align="center">
  <a> Gambar 3 </a>
</p>

[![Screen-Shot-2019-10-27-at-12-53-06.png](https://i.postimg.cc/rpMVnw18/Screen-Shot-2019-10-27-at-12-53-06.png)](https://postimg.cc/Bj7fts7y)

<p align="center">
  <a> Gambar 4 </a>
</p>

##### Cara kerja & Dokumentasi penggunaan : #####

PHPLOY meruapakn sebuah tools FTP Client untuk deploy aplikasi ke server. Konsep kerja PHPloy ini adalah melakukan perubahan(upload/delete) file-file yang telah ter commit pada git ke server.

* __Gambar 1__: Lakukan clone pada github.com/banago/phploy terlebih dahulu untuk bisa menggunakan phploy. 

* __Gambar 2__ : Setelah melakukan clone, cari file phploy.phar kemudian pindahkan file tersebut ke repository git kita. Rename file tersebut menjadi phploy. Setelah itu lakukan `sudo chmod +x phploy` pada terminal agar phploy bisa di execute. Setelah phploy bisa di execute, jalankan `phploy --init` pada terminal, fungsi ini akan membuat sebuah file __php.ini__ . File ini nantinya yang akan berfungsi sebagai file untuk konfigurasi project.

* __Gambar 3__ : Setelah melakukan konfigurasi pada file phploy.ini, lakukan `phploy`. Fungsinya untuk memulai melakukan deployment terhadap git repository.

* __Gambar 4__ : `phploy -l` befungsi untuk melihat list yang di upload/dihapus sebelum melakukan push.

Untuk dokumentasi lebih lengkap, silahkan cek [PHPLOY](https://github.com/banago/phploy).

#### Credits ####
* [Baki Goxhaj](https://github.com/banago).

## HASIL RUNNING SUPfile ##

Supfile/Stack Up merupakan sebuah alat deployement sederhana yang melakukan serangkaian perintah pada beberapa host secara paralel. Berguna untuk membaca Supfile, file konfigurasi YAML, yang mendefinisikan jaringan (kelompok host), perintah dan target.

##### Cara kerja & Dokumentasi penggunaan : #####

* __Tahap 1__ : Lakukan instalasi terlebih dahulu dengan cara mendownload pressle/sup dari git menggunakan command `go get -u github.com/pressly/sup/cmd/sup`.

* __Tahap 2__ : Untuk penggunaan cukup dengan mengetik command `sup` pada terminal.<img width="345" alt="Screen Shot 2019-10-27 at 16 51 39" src="https://user-images.githubusercontent.com/54678313/67636621-2c9ab580-f905-11e9-807e-fe126a33082d.png">

#### LIST COMMAND : ####
* FULL LIST COMMAND [command](https://github.com/pressly/sup).


#### Credits ####
* [Pressly](https://github.com/pressly).





