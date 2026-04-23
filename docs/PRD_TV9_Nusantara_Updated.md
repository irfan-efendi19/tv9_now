# Product Requirements Document (PRD): TV9 Nusantara (Updated)

## 1. Ringkasan Produk (Executive Summary)
TV9 Nusantara adalah platform digital terintegrasi untuk stasiun televisi Islami TV9 Nusantara. Aplikasi ini dirancang sebagai "Digital Minaret" (Menara Digital) yang menyebarkan konten religi yang santun dan menyejukkan, menggabungkan siaran langsung 24 jam, berita terkini, fitur ibadah, dan interaksi komunitas dalam satu ekosistem modern berbasis warisan budaya Nusantara.

## 2. Visi dan Tujuan (Vision and Goals)
- **Visi:** Menjadi platform media digital Islami terdepan di Indonesia yang menjembatani tradisi pesantren dengan kemajuan teknologi digital.
- **Tujuan:**
  - Menyediakan akses mudah ke siaran langsung TV9 Nusantara kapan saja dan di mana saja.
  - Memberikan informasi berita terkini dengan sudut pandang Islami Nusantara.
  - Memfasilitasi interaksi antara pemirsa dan narasumber melalui fitur forum talkshow.
  - Menyediakan alat bantu ibadah harian (Al-Qur'an, Jadwal Shalat, dan lain-lain) dalam satu aplikasi.

## 3. Target Pengguna (Target Audience)
1. **Masyarakat Muslim Umum:** Pengguna yang membutuhkan konten religi yang menyejukkan.
2. **Komunitas Santri dan Alumni Pesantren:** Pengguna utama konten dakwah TV9.
3. **Masyarakat Modern dan Digital Native:** Pengguna yang mencari platform berita dan religi dengan estetika visual tinggi.

## 4. Fitur Utama (Core Features)

### 4.1 Live Streaming 24 Jam
- Pemutar video siaran langsung yang stabil menggunakan link:
  - `https://5bf7b725107e5.streamlock.net:443/tv9/tv9/playlist.m3u8`
- Dukungan format HLS (`.m3u8`) untuk kualitas streaming adaptif.
- Informasi acara yang sedang tayang (**Now Playing**) dan acara selanjutnya.
- Indikator waktu shalat lokal yang terintegrasi di atas pemutar video.

### 4.2 Portal Berita Terkini
- Daftar artikel berita dengan kategori (Nusantara, Khazanah, Pendidikan, dan lainnya).
- Antarmuka baca berita yang bersih dan fokus pada kenyamanan tipografi.
- Fitur bagikan berita ke media sosial.

### 4.3 Fitur Religi dan Ibadah (Jelajahi TV9)
- **Al-Qur'an Digital:** Akses baca ayat suci.
- **Jadwal Shalat:** Berdasarkan lokasi pengguna saat ini.
- **Kiblat dan Doa:** Alat bantu navigasi ibadah dan kumpulan doa harian.
- **Zakat dan Donasi:** Integrasi pembayaran zakat, infaq, dan sedekah online.

### 4.5 Jadwal Acara (Program Guide)
- Tampilan jadwal harian yang compact dan mudah dipahami.
- Fitur pengingat (reminder) untuk acara yang akan datang.

## 5. Panduan Desain (Design Language)
- **Sistem Desain:** Nusantara Heritage.
- **Estetika:** Modern, imersif, dan bersih tanpa title bar/header konvensional.
- **Palet Warna:**
  - Hijau Nusantara: `#004B23`
  - Emas Aksen: `#735C00`
  - Surface Light: `#F7FAF8`
- **Tipografi:**
  - Header: **Noto Serif** (berwibawa dan intelektual).
  - Body: **Manrope** (modern dan mudah dibaca).

## 6. Struktur Navigasi (Information Architecture)
1. **Beranda:** Live TV, highlight berita, dan menu jelajahi fitur religi.
2. **Berita:** Hub utama untuk semua kategori artikel.
3. **Forum:** Pusat diskusi interaktif talkshow.
4. **Jadwal:** Daftar program TV9 harian.
