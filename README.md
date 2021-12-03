<p align="center">
<a href="https://ibb.co/zsnrpRQ"><img src="https://github.com/scoder37/MyWA-MD/blob/main/Screenshot_20211203-101528.png?raw=true" alt="l3" border="0"><a>
</p>
<h1 align="center">MyWA MD Bot Hosting</h1>
<h3 align="center">[BOT MULTIDEVICE]</h3>

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/scoder37/zroot)

[![Grup WhatsApp](https://img.shields.io/badge/WhatsApp%20Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/GyF5zdb2aK15pAexpvHhNC)

## ABOUT MY BOT
MyWA MD adalah bot whatsapp multi device (bot md) yang dijalankan pada hosting
dikode-team.com
bot ini dirancang menggunakan library baileys-md

## INSTALASI

* Download & Install Git [`Klik Disini`](https://git-scm.com/downloads)
* Download & Install NodeJS [`Klik Disini`](https://nodejs.org/en/download)
* Downloads & Install FFmpeg [`Klik Disini`](https://ffmpeg.org/download.html)
* Add Ffmpeg to Variable Path
* Download & Install ImageMagick [`Klik Disini`](https://imagemagick.org/script/download.php)
* Register Amirul Dev Get Notification [`Klik Disini`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/scoder37/zroot.git
cd zroot
npm i
npm update
edit api get notif (config.js)
node .
```

### Payment Gateway & Mutasi
* Ovo, Gopay, Shopeepay, Bca, Bri, Bni (Mutasi)
* Qris, Dana, Bca, Bri, Bni, Mandiri, Briva, Gopay, Shopeepay, Ovo (Payment)
* Alfamart, Alfamidi, Indomaret (Comingsoon)

---------

### Arguments
$ node . [ session ] --options
* contoh: node . kayla --read

#### List Options
* --self : membuat self mode
* --read : mengaktifkan auto read chat & story
* --prf [prefix] : membuat prefix tertentu
* --srv : jika dijalankan di heroku
* --bigqr : jika qr unicode tidak mendukung
* --restrict : aktifkan untuk mencegah nomor diblokir wa
* --db [url server] : untuk menggunakan db eksternal

#NB:
jika menggunakan db eksternal, seever harus memiliki spesifikasi seperti berikut

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```





## Arguments `node . [--options] [<session name>]`

#### Contoh: `node . --self --restrict --autoread`

### `--self`

Aktifkan mode self (Mengabaikan yang lain)

### `--prefix <prefixes>`

* `prefixes` dipisahkan oleh masing-masing karakter
Setel awalan

### `--server`

Digunakan untuk [heroku](https://heroku.com/) atau pindai melalui situs web

### `--db <json-server-url>`

Gunakan db eksternal alih-alih db lokal, 
Contoh Server `https://json-server.nurutomo.repl.co/`
Code: `https://repl.it/@Nurutomo/json-server`

`node . --db 'https://json-server.nurutomo.repl.co/'`

Server harus memiliki spesifikasi seperti ini

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

Jika qr unicode kecil tidak mendukung

### `--restrict`

Mengaktifkan plugin terbatas (yang dapat menyebabkan nomor Anda **diblokir** jika digunakan terlalu sering)

* Administrasi Grup `add, kick, promote, demote`

### `--img`

Aktifkan pemeriksa gambar melalui terminal

### `--autoread`

Jika diaktifkan, semua pesan masuk akan ditandai sebagai telah dibaca

### `--nyimak`

Tidak ada bot, cukup cetak pesan yang diterima dan tambahkan pengguna ke database

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

---------

 [![amiruldev20](https://raw.githubusercontent.com/scoder37/scoder37/main/IMG-20210915-WA0020.jpg?size=100)](https://github.com/amiruldev20) | [![scoder37](https://raw.githubusercontent.com/scoder37/scoder37/main/IMG-20210915-WA0020.jpg?size=100)](https://github.com/scoder37)
----|----
[Amirul Dev](https://github.com/amiruldev20) | [Kayla](https://github.com/scoder37)
 Creator | Developer
