---
title: "Pendahuluan"
date: 2018-10-25T10:07:32+07:00
draft: false
---

_No furniture so charming as books_ - **Sydney Smith**

# Pendahuluan

SLiMS _Library Management System_ (SLiMS) adalah _Open Source Software_ (OSS) berbasis web untuk memenuhi kebutuhan automasi perpustakaan (_library automation_) skala kecil hingga skala besar. Dengan fitur yang. dapat dikatakan, lengkap dan masih terus aktif dikembangkan, SLiMS dapat digunakan oleh perpustakaan yang memiliki koleksi, anggota dan staf banyak di lingkungan jaringan, baik itu jaringan lokal (_intranet_) maupun internet.

SLiMS merupakan aplikasi berbasis web dengan pertimbangan _cross-platform_, dapat berjalan dengan baik di atas _platform_ sistem operasi seperti MacOS,MS-Windows, dan GnU/Linux. Sepenuhnya dikembangkan menggunakan perangkat lunak kode sumber terbuka yaitu: PHP _Web Scripting Language_, ([http://www.php.net](www.php.net)) dan MySQL _Database Server_ ([http://www.mysql.com](www.mysql.com)). Untuk meningkatkan interaktifitas agar bisa tampil seperti aplikasi desktop, juga digunakan teknologi AJAX (_Asynchronous JavaScript And XML_). Aplikasi seperti PhpThumb dan Simbio (_development platform_ yang digunakan dan dikembangkan dari proyek Igloo) juga digunakan oleh SLiMS. Karena itu, SLiMS menggunakan Lisensi Publik GnU (GPL) v3 untuk **menjamin kebebasan dalam mendapatkan, memodifikasi dan mendistribusikan kembali** (_rights to use, study, copy, modify, and redistribute computer programs_). Lebih jauh tentang GPLv3 bisa dibaca di [http://www.gnu.org/licenses/gpl-3.0.html](http://www.gnu.org/licenses/gpl-3.0.html).

Pada saat itu, ketika masih disebut Senayan, versi 1 dan 2 tidak dirilis ke publik karena masih tahap ujicoba dan sedang dalam penyempurnaan. Sejak (Senayan) versi 3, Senayan dianggap sudah stabil untuk dirilis ke publik dan sudah waktunya diujicoba oleh komunitas pustakawan. Diharapkan dengan _peer-to-peer review_ oleh publik, Senayan semakin stabil dan fitur-fiturnya bisa semakin beragam dan mengakomodasi banyak kebutuhan. Kunjungi [Situs SLiMS](http://slims.web.id) untuk informasi lebih lanjut tentang SLiMS.

# Fitur SLiMS

* _Online Public Access Catalog_ (OPAC) dengan pembuatan _thumbnail_ yang di-_generate-on-the-fly_. _Thumbnail_ berguna untuk menampilkan sampul buku. Mode penelusuran tersedia untuk yang sederhana (_Simple Search_) dan tingkat lanjut (_Advanced Search_).
* Detail _record_ (cantuman) juga tersedia format XML (_Extensible Markup Language_) untuk kebutuhan _web service_.
* Manajemen data bibliografi yang efisien meminimalisasi redundansi data.
* Manajemen _masterfile_ untuk data referensial seperti GMD (_General Material Designation_), Tipe Koleksi, Penerbit, Pengarang, Lokasi, Supplier, dan lain-lain.
* Sirkulasi dengan fitur:
  * Transaksi peminjaman dan pengembalian;
  * Reservasi koleksi;
  * Aturan peminjaman yang fleksibel;
  * Informasi keterlambatan dan denda.
* Manajemen keanggotaan.
* Inventarisasi koleksi (_stock taking_).
* Laporan dan Statistik.
* Pengelolaan terbitan berkala.
* Dukungan pengelolaan dokumen multimedia (.flv,.mp3, dlsb.) serta dokumen dijital.
* SLiMS mendukung beragam format bahasa termasuk bahasa yang tidak menggunakan penulisan selain latin.
* Menyediakan berbagai bahasa pengantar (Indonesia, Inggris, Spanyol, Arab, Jerman, Bengali, Persia, Melayu, Portugis Brasil, Thailand, Jepang).
* Dukungan Modul _Union Catalog Service_.
* Penghitung Pengunjung perpustakaan.
* _Member Area_ untuk melihat koleksi sedang dipinjam oleh anggota.
* Modul sistem dengan fitur:
  * Konfigurasi sistem global;
  * Manajemen modul;
  * Manajemen pengguna (grup pengguna dan pengguna aplikasi);
  * Pengaturan hari libur;
  * Pembuatan _barcode_ otomatis;
  * Utilitas untuk backup.

Berbagai fitur lainnya yang tidak dapat kami sebutkan pada pendahuluan ini. Silakan anda melanjutkan membaca bab-bab berikutnya pada dokumentasi ini.

