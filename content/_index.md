---
title: ""
date: 2018-10-25T09:54:01+07:00
draft: false
---
# SLiMS

## 7 Hari Mahir SLiMS
Dokumentasi ini saya susun secara meningkat. Dari yang menantang ke biasa. Nah belajar nya dari yang biasa dulu. Bab 0 ada dibawah bab tertinggi di atas. Total ada 14 bab. Setiap hari Anda belajar 2 bab. Baca praktek , baca praktek. Akan cepat memahami jika baca manual. 

Hindari trial eror tanpa baca manual - nanya ke nanya group - gak dijawab nyinyar nyinyir , kapan maju ha ha ...

Hari Ke | Bab Yang Dipelajari | Alokasi Waktu
--- | --- | ---
Hari ke 1 | Bab Pendahuluan dan Bab 0 Opac| 4 Jam
Hari ke 2 | Bab 1 Install  dan Bab 2 Bibliografi | 4 Jam
Hari ke 3 | Bab 3 Membership dan Bab 4 Circulation | 4 Jam
Hari ke 4 | Bab 5 Stoctake dan Bab 6 Reporting | 4 Jam
Hari ke 5 | Bab 7 Serial Control dan Bab 8 System | 4 Jam
Hari ke 6 | Bab 9 Master File dan Bab 10 Tips n Trick | 4 Jam
Hari ke 7 | Bab 11 Visitor Counter dan Bab 12 UCS | 4 Jam
**7 hari** | **14 Bab** | **28 Jam**

## Demo SLiMS
Anda dapat mencoba demo SLiMS , klik menu Demo diatas
Login menggunakan akun 

* username : **admin**
* passwod : **admin**

## SLiMS 
SLiMS _Library Management System_ (SLiMS) adalah _Open Source Software_ (OSS) berbasis web untuk memenuhi kebutuhan automasi perpustakaan (_library automation_) skala kecil hingga skala besar. Dengan fitur yang. dapat dikatakan, lengkap dan masih terus aktif dikembangkan, SLiMS dapat digunakan oleh perpustakaan yang memiliki koleksi, anggota dan staf banyak di lingkungan jaringan, baik itu jaringan lokal (_intranet_) maupun internet.

![](assets/slims_logo_baru.png)

SLiMS merupakan aplikasi berbasis web dengan pertimbangan _cross-platform_, dapat berjalan dengan baik di atas _platform_ sistem operasi seperti MacOS,MS-Windows, dan GnU/Linux. Sepenuhnya dikembangkan menggunakan perangkat lunak kode sumber terbuka yaitu: PHP _Web Scripting Language_, ([http://www.php.net](www.php.net)) dan MySQL _Database Server_ ([http://www.mysql.com](www.mysql.com)). Untuk meningkatkan interaktifitas agar bisa tampil seperti aplikasi desktop, juga digunakan teknologi AJAX (_Asynchronous JavaScript And XML_). Aplikasi seperti PhpThumb dan Simbio (_development platform_ yang digunakan dan dikembangkan dari proyek Igloo) juga digunakan oleh SLiMS. Karena itu, SLiMS menggunakan Lisensi Publik GnU (GPL) v3 untuk **menjamin kebebasan dalam mendapatkan, memodifikasi dan mendistribusikan kembali** (_rights to use, study, copy, modify, and redistribute computer programs_). Lebih jauh tentang GPLv3 bisa dibaca di [http://www.gnu.org/licenses/gpl-3.0.html](http://www.gnu.org/licenses/gpl-3.0.html).

## Dokumentasi SLiMS Berdasar SLiMS 8.3.1 Akasia

Web ditulis menggunakan [MD MarkDown](https://en.wikipedia.org/wiki/Markdown) . Online menggunakan [Hugo](https://hugo.io) Hugo Static Site Generator v0.49.2 linux/386 BuildDate: 2018-10-11T09:49:19Z

## Intro

_Menggunakan piranti lunak_ free open source software _itu ibarat kita mengutip pernyataan dari karya orang lain dalam bidang akademik. Penulis asli ga minta apa-apa kok, minta duit juga engga, cuman minta nama dan karya dia disebutin dengan baik dan benar, udah segitu doang. Engga susah kan?_ (**Arie Nugraha, Core Programmer SLiMS**)

Pembaruan di SLiMS 8.3.1 Akasia:

* _Added : Installer auto generate database_
* _Added : Node server for UCS_
* _Added : Node server for P2P_
* _Added : Scope note in vocabulary control_
* _Added : Chatting tools_
* _Modified : Password change due to encryption method_
* _Added : User ID in database_
* _Fixed : Auto focus on current stock take menu_
* _Fixed : Download access for PDF_
* _Fixed : Biblio ID for item import_
* _Fixed: Rename uploaded file from attachment_
* _Added: Application APIs_
* _Modified: Only admin login who can initiate stock opname_

## Beberapa catatan penting perubahan pada SLiMS 8 Akasia

### _Sysconfig_ (Konfigurasi sistem)

Terdapat perubahan letak (_path_) berkas sysconfig.local.inc.php sejak SLiMS 8 Akasia. Berkas sysconfig.local.inc.php berada di dalam direktori "config."
![](assets/config1.png)

### _Shortcut_ (Pemintas)

Mulai SLiMS 5 Meranti, SLiMS mengimplementasikan fitur pemintas yang dapat digunakan untuk berpindah menu tanpa menggunakan tetikus. Pemintas tersebut berlaku untuk MODUL dan SUBMODUL. Pemintas modul menggunakan perpaduan Shift+Tombol Fungsi (F1-F8 dan Esc), sedangkan pemintas submodul menggunakan perpaduan Ctrl+Angka 1-8, pada bagian yang mempunyai submodul banyak ada yang juga menggunakan perpaduan Ctrl+Alt+Angka.

Pada SLiMS 8 Akasia fitur pemintas melalui _keyboard_ dihilangkan. Sebagai gantinya, pengguna dapat melakukan pengaturan pemintas dengan cara memilih modul apa saja yang akan dimasukkan di dalam menu pemintas.

Semua modul SLiMS dapat dimasukkan ke dalam menu Pemintas

![](assets/shortcut.png)

Penambahan modul pada pemintas dilakukan melalui pada _Shortcut Settings_.

![](assets/shortcut1.png)

### _Browser_ (Peramban)

Dengan dukungan HTML 5, kami merekomendasikan peramban web untuk membuka SLiMS 8 Akasia sebagai berikut:

1. Mozilla Firefox;
2. Google Chrome;
3. Opera.



