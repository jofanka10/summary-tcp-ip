# Summary TCP/IP

- Nama: Jofanka Al-Kautsar Pangestu Abady
- NRP: 5027241107
- mata Kuliah: Keamanan dan Jaringan Komputer (C)


## 1. OSI Layer
OSI Layer merupakan singkatan dair Open System Interconnection Layer. Ini merupakan konsep untuk memahami cara kerja pengiriman data melalui jaringan.

Untuk lapisannya sebagai berikut.
- Application, yaitu tempat aplikasi berinteraksi dengan jaringan. Contoh: HTTP, SSH.
- Persentation, berfungsi untuk memastikan data disajikan dalam format yang benar. Contoh: JPEG, MPEG.
- Session, yaitu lapisan yang bertanggung jawab untuk memulai, mengelola, dan mengakhiri sesi dalam jaringan.
- Transport, yaitu proses pengiriman data secara keseluruhan. Contoh: TCP, UDP.
- Network, yang bertanggung jawab untuk pengalamatan logis dan menentukan rute jaringan terbaik. Contoh: IP, IGMP.
- Data Link, yaitu layer yang berfungsi untuk mengatur aliran data dalam satu jaringan lokal. Contoh: MAC Address.
- Pyshical, yaitu alat fisik yang digunakan dalam proses pengiriman data melalui jaringan.


## 2. TCP/IP

- TCP/IP adalah singkatan dari Transmission Control Protocol/Internet Protocol. Ini adalah model arsitektur jaringan yang menjadi fondasi utama dari internet.
- TCP/IP dirilis pada era awal internet, dimana keamanan jaringan bukanlah hal yang sangat penting.
- TCP/IP memiliki beberapa layer, yaitu Application, Transport, Network, Data Link, dan Pyshical.
- Jika layer paling bawah (pyshical) diekspoitasi, maka semua layer yang di atasnya ikut terancam.


## 3. IP PDU
IP PDU merupakan singkatan dari IP Protocol Data Unit. Ini adalah istilah dsar dalam jaringan yang mengacu pada satuan data yang ditransfer di antara setiap lapisan dalam model jaringan.

## 4. IPv4
- IPv4 merupakan kepanjangan dari Internet Protocol verion 4. Ini adalah salah satu versi utama dari IP yang menyediakan sistem pengalamatan unik untuk setiap perangkat yang terhubung ke internet.
- IPv4 berisi nilai biner 4-bit (0100).
- Differented Services (DiffServ) adalah seperangkat aturan jaringan untuk mengelola lalu lintas data dan memberikan layanan yang beragam.
- Time to Live (TTL) adalah sebuah value yang berfungsi untuk membatasi umur paket. Mengapa dibatasi? Jika tidak, maka kemungkinan data yang berlalu lalang di jaringan menjadi tidak terkendali.

## 5. IPv6
- IPv6 merupakan versi terbaru dari IPv4. Ini berisi 4-bit biner dengan nilai 0110.
- IPv6 menggunakan sistem pengalamatan 128-bit, dengan bentuk seperti ini `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.
- Memiliki Payload Length (ukuran data aktual) berupa field 16-bit.
- Tidak seperti IPv4, IPv6 menggunakan Hop Limit, menggantikan TTL pada IPv4.
- Source dan destination address sama-sama benbentuk field 128-bit.

## 6. IP Vulnerabilities
IP Vulnerabilites adalah celah keamanan pada IP sehingga peretas dapat menyusup ke dalam jaringan. Ini akan membuat jaringan terganggu, mulai dari bandwith yang melambat, hingga dapat terjadi gangguan dalam jaringan.

IP Vulnerabilites dapat berupa:
- ICMP Attacks, yaitu serangan yang berbentuk pesan error. 
- Denial-of-Service (DoS) attack, yaitu serangan yang menyebabkan lalu lintas data menjadi kewalahan.
- Distributed Denial-of-Service (DDoS) attack, jenis serangannya sama dengan DoS attack, namun perbedaannya terletak pada penyebaran dan skalanya. Pada DoS attack, sumbernya hanya pada satu perangkat, sedangkan pada DDoS attack sumbernya pada banyak perangkat.
- Session Hijacking, yaitu peretas menyamat sebagai pengguna yang sah dalam jaringan.
- Man-in-the-middle attack (MiTM), yaitu peretas menyusup di tengah-tengah komunikasi. Kedua pihak mengira mereka bertransaksi hanya kedua pihak saja, padahal mereka sedang disusupi peretas.
- Address spoofing attacks, yaitu peretas memalkukan alamat sumber untuk menyamarkan identitas mereka.

## 7. TCP
- TCP merupakan singkatan dari Transmission Protool Control. Ini adalah protokol komunikasi yang bertanggung jawab untuk memastikan paket data dikirim dan diterima dengan aman dalam jaringan.
- TCP berguna untuk mencegah pengirim membanjiri penerima dengan data.
- Cara kerja TCP yaitu:
  
  a. Pengirim mengirim paket SYN ke penerima untuk meminta koneksi.

  b. Penerima menerima paket SYN dan meresponsnya dengna paket SYN-ACK.

  c. Pengirim merespons dengan paket ACK.
  

- TCP attack dapat berupa:
  
  a. TCP SYN Flood Attack
  
  b. TCP Rest Atatck
  
  c. Four-Way Handshake
  
  d. TCP Session Hijacking
  

## 8. UDP
- UDP merupakan singkatan dari User Datagram Protocol. UDP bekerja lebih sederhana dibandingkan dengan TCP, memungkinkan UDP dapat mengirimkan data dengan lebih cepat.
- UDP memiliki rentan terkena serangan lebih tinggi daripada TCP.
- UDP cocok digunakan untuk streamig video dan audio. Selain itu, UDP juga cocok digunakan pada platform game online.
- UDP attack dapat berupa UDP Flood Attack dan UDP Applification Attack.


