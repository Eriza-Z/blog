---
layout: "../../layouts/BlogPost.astro"
title: "SSL - ErZ Blog"
description: "Pengertian, serta fungsi dari SSL"
pubDate: "18 September 2022"
heroImage: "https://mergoreb.sirv.com/Blog/Hero%20SSL.png?w=250&format=webp&q=50"
updatedDate: "18 September 2022"
---

Ketika kalian datang atau masuk kesebuah website, mungkin kalian pernah melihat logo gembok dibelakang URL seperti berikut ini:<br> 
<img src="https://mergoreb.sirv.com/Blog/SSL.jpg?format=webp&q=70" width="160" height="50" alt="SSL" /><br>
Jika kalian bertanya, apa kah itu? Itu adalah SSL, disini, saya akan membahas tentang apa itu SSL, apa fungsi, serta mengapa harus menggunakan SSL?

## Apa itu SSL?
Pertama-tama, kita harus mencari tahu, apa arti dan maksud dari SSL. SSL atau Secure Socket Layer adalah sebuah protokol keamanan yang berbasis enskripsi yang dimana digunakan untuk mengamankan koneksi dan data dari Webserver (Server Hosting) dan Client (Pengunjung Web).

SSL pertama kali di kembangkan oleh Netscape pada tahun 1995 yang digunakan untuk memastikan privasi, otentikasi, dan integritas data dalam komunikasi Internet.

Sekarang, SSL merupakan standar protokol keamanan pada website yang digunakan untuk melindungi jutaan hingga milyaran data setiap harinya.

## Apa saja data yang dienkripsi oleh SSL?
SSL mengenkripsi informasi sensitif seperti data kartu kredit,username,password dan informasi penting ditransmisikan cari server ke client atau sebaliknya dengan aman karena data yang dikirim akan diacak.

Sebelum membuat koneksi SSL, Webserver atau Server dari suatu web harus memiliki sertifikat SSL terlebih dahulu.

Ketika seseorang mengaktifkan protokol SSL di server web mereka, mereka diminta untuk menjawab pertanyaan yang akan membangun identitas mereka. Pertanyaannya seputar informasi tentang situs dan perusahaan. Setelah sertifikat SSL berhasil diminta (buat), server web menciptakan dua kunci kriptografi, yaitu Public Key dan Private Key.

Sesuai namanya, Public Key adalah kunci diberikan ke browser bersama dengan certificate ketika secure connection antara browser dan server terbentuk, Public Key ini akan digunakan oleh browser untuk mengenkripsi data yang akan dikirim ke Server sedangkan Private Key adalah kunci yang sifatnya sangat rahasia dan tidak ada boleh sampai bocor karena kunci ini yang digunakan untuk membongkar enkripsi data dari dan ke server. Kunci ini digunakan oleh server untuk mendecrypt informasi terenkripsi dari browser.

## Apa keuntungan dari SSL?
1. Menaikkan rank pada Search Engine
2. Menghindari Pencurian Data
3. Meningkatkan Reputasi Website
4. Mematuhi Aturan Transaksi
5. Menghindari Salah Kirim Data

## Jenis-jenis SSL.
SSL dibagi menjadi 3 macam berdasarkan cara validasi atau aktivasi nya.
1. Domain Validation (DV SSL).<br>
Sertifikat SSL level DV hanya memerlukan kepemilikan domain, berupa validasi DNS atau email.

2. Organization Validated SSL (OV SSL).<br>
SSL ini sebenarnya sama seperti DV SSL. Namun, pemilik domain harus melakukan verifikasi dengan menunjukkan bukti kepemilikan dan legitimasi domain. Ini dilakukan penerbit sertifikat atau CA (Certificate Authority) seperti GeoTrust, Comodo SSL, dan lain-lain untuk memastikan bahwa domain didaftarkan dengan informasi nama bisnis, lokasi, dan informasi legal lainnya.

3. Extended Validated SSL (EV SSL).<br>
Untuk mendapatkan EV SSL, pemilik domain wajib memverifikasi kepemilikan domain dengan beberapa dokumen legal. Hal ini karena SSL ini digunakan oleh mereka yang memiliki badan usaha terpercaya seperti PT, CV, dan Departemen Negara.

Selain itu, SSL dibagi juga berdasarkan jumlah Domain yang dienkripsi.
1. Single Domain SSL.<br>
SSL single domain adalah SSL yang hanya bisa mengamankan hanya satu domain saja, tidak bisa lebih dari satu domain.

2. Wildcard SSL.<br>
Wildcard SSL adalah sertifikat SSL yang memiliki karakter wildcard (bintang) pada domain. Bintang ini bertugas untuk mengamankan beberapa nama sub domain yang terhubung dengan domain utama

3. Multi Domain SSL
ini adalah SSL yang bisa memberikan keamanan di banyak domain, syarat utama membeli SSL ini adalah domain yang akan di secure haruslah aktif. Sertifikat ini biasanya dipakai perusahaan yang memiliki banyak domain dan mencari harga terjangkau jika dibandingkan dengan membeli SSL satu persatu.

<br>
<br>

### Referensi: 
[Cloudflare](https://www.cloudflare.com/learning/ssl/what-is-ssl/#:~:text=SSL%2C%20or%20Secure%20Sockets%20Layer,modern%20TLS%20encryption%20used%20today.)<br>
[Niagahoster](https://www.niagahoster.co.id/blog/apa-itu-ssl/)<br>
[Domainesia](https://www.domainesia.com/panduan/apa-itu-ssl/)