---
layout: default
title: Dasbor Admin (Backend)
---

# ⚙️ Dasbor Admin: Buku Manual Kendali Operasional

Sistem _Backend_ (Admin Panel) CMS Sekolah Pro merupakan ruang mesin utama. Dibangun untuk memberikan kekuatan mutlak bagi sekolah mengelola segala jenis data tanpa perlu mengerti bahasa pemrograman sama sekali. Berikut bedah modul Dasbor Admin:

---

## 1. Dasbor Utama (Ringkasan Statistik)
Halaman pertama setelah *login* yang menyajikan kondisi kesehatan informasi sekolah sekilas mata.
- Menyajikan angka *counter* untuk total Berita, jumlah Ekstrakurikuler, jumlah Guru, dsb.
- **Pintasan Aksi**: Tombol cepat untuk "Tulis Berita Baru" tanpa harus mencari menunya.

![Dasbor Admin](assets/img/admin-dashboard.png)

---

## 2. Modul Identitas & Pengaturan Web (Settings)
Alih-alih merubah konfigurasi di kode program, Anda dapat melakukan kustomisasi wajah (*branding*) sekolah langsung dari layar ini.
- Ubah Logo Sekolah, Teks Moto (*Tagline*), dan Teks Sambutan Beranda.
- Konfigurasi Alamat, Email, Nomor Telepon, dan titik kordinat Google Maps.
- Pengaturan Media Sosial (Instagram, YouTube) dan *Meta Tag SEO* otomatis.

![Pengaturan Web](assets/img/admin-settings.png)

---

## 3. Modul Manajemen Publikasi (Posts)
Pusat kontrol jurnalistik internal sekolah.
- Antarmuka *Editor Artikel* modern yang mirip dengan mengetik di Microsoft Word.
- Mendukung "Draft" (simpan sementara) dan "Published" (terbitkan).
- Modul sub-menu untuk mengelola **Kategori Tulisan** dan **Tags**.

![Manajemen Publikasi](assets/img/admin-post.png)

---

## 4. Modul Pembuat Halaman Statis (Pages)
Jika sekolah butuh satu halaman informasi baru yang sifatnya permanen (misal: "Sejarah Komite Sekolah" atau "SOP Pengaduan Kekerasan"), Admin bisa membuat halaman baru di sini tanpa bergantung pada *developer*.
- Format *slug URL* (contoh: `/halaman/sop-pengaduan`) terbuat otomatis.

![Manajemen Halaman](assets/img/admin-pages.png)

---

## 5. Modul Akademik & Dokumen
Mengatur lalu lintas arus informasi harian kepada siswa/wali murid.
- **Pengumuman**: Peringatan sekilas (seperti libur darurat cuaca).
- **Agenda**: Input tanggal mulai dan selesai kegiatan ujian/porseni yang otomatis muncul di kalender publik.
- **Manajer Unduhan**: Tempat meng-*upload* file PDF (*Formulir, Tata Tertib*) dan memberi label kategori unduhan tersebut.

![Modul Akademik](assets/img/admin-akademik.png)

---

## 6. Modul Manajemen SDM & Fasilitas
Database master pendidik dan sarana.
- **Staf & Guru**: Form input foto profil, jabatan struktural (Kepala, Wakil, Wali Kelas), pangkat kependidikan, dan biodata panjang.
- **Fasilitas**: Registrasi sarana fisik.
- **Ekstrakurikuler**: Input nama ekskul, pelatih penanggung jawab, jadwal kumpul rutin, serta penambahan catatan Medali Prestasi.

![Manajemen SDM](assets/img/admin-sdm.png)

---

## 7. Media Center Terpadu (File Manager)
Penyimpanan sentral (Awan Lokal) untuk semua artefak digital (foto, file, pdf).
- Layaknya *Google Drive* internal, Anda dapat melihat seluruh gambar yang pernah di-*upload*.
- Jika ingin memasang satu foto guru di tiga halaman berbeda, tidak perlu unggah tiga kali, cukup klik dari direktori Media Center ini.

![Media Center](assets/img/admin-media.png)

---

## 8. Navigasi Dinamis (Menu Builder)
Apakah Anda ingin mengubah posisi menu "Fasilitas" agar berada di bawah menu "Profil" pada tampilan depan web? Lakukan di sini!
- Sistem perakitan menu (*Menu Builder*) memungkinkan admin menambah, menghapus, atau membuat tautan eksternal (misal mengarah ke *Google Form*) pada navigasi publik web.

![Menu Builder](assets/img/admin-menu.png)

---

## 9. 🌟 Fitur Revolusioner: Custom Pods
Fitur paling *powerful* dari CMS ini! Fitur pembuat Database Mandiri tanpa *Coding*.
- Contoh Kasus: Sekolah butuh mendata "Siswa Berprestasi Nasional".
- Admin masuk ke Pods -> Buat entitas "Siswa Berprestasi".
- Tambah *Field*: "Nama Siswa" (Text), "Tanggal Juara" (Date), "Foto Trofi" (Image).
- **Boom!** CMS otomatis merakit form pendaftaran baru dan tabel data untuk entitas tersebut di panel admin Anda!

![Custom Pods](assets/img/admin-pods.png)

---

## 10. Modul Security & Audit
Kunci pengaman sistem bagi Super Administrator.
- **RBAC (Pengguna)**: Buat akun *login* baru untuk staf Anda dan tentukan batasannya (Admin penuh atau hanya Editor artikel).
- **Log Aktivitas (Audit Trail)**: CCTV aktivitas digital. Mencatat 100% pergerakan data. *“Siapa yang menghapus pengumuman libur jam 7 malam tadi?”* — Semuanya tercatat permanen di halaman ini beserta IP dan identitas peretas internal/eksternal.

![Audit Log](assets/img/admin-audit.png)

---

[➡️ Lanjut: Skema Penawaran Harga (Pricing)](pricing.md) | [⬅️ Kembali ke Portal Publik](frontend.md)
