# CREATIVE DIRECTION BOARD v0.9
## Affiliate TikTok dari Nol — Edisi 2026
**Chatroom:** PDF 📚 - 01 Affiliate TikTok dari Nol Project
**Status:** LOCKED — disetujui Reza (13 Juli 2026), diperbarui 15 Juli 2026
**Sinkron dengan:** file "01 - Cover.txt", Character Reference Sheet v0.5, Visual Audit Cuan Modal Kuota, PDF Production Brief v0.9, Blueprint Induk v1.9 Bagian 5.3, nganggur-bercerita-reference v1.6 Bagian 8

---

## Riwayat Revisi
- **v0.1 (13 Juli 2026):** Palet warna, tipografi, margin, sistem ilustrasi, spesifikasi komponen, elemen yang dihindari, spesifikasi teknis produksi.
- **v0.2 (14 Juli 2026):** Menambahkan Bagian 9 — Sistem Logo & Publisher Mark, palet logo generasi pertama (`#1E6157`/`#D9CBB2`).
- **v0.3 (15 Juli 2026):** Sinkronisasi ke palet logo generasi kedua — `#1E6157` → `#07565F` (Deep Teal), `#D9CBB2` → `#FF7900` (Orange). Kode lama tidak lagi dipakai.
- **v0.4 (15 Juli 2026):** Menambahkan Bagian 9.5 — Publisher Mark versi Footer (C2), wajib di setiap halaman isi.
- **v0.5 (15 Juli 2026):** Menambahkan rujukan daftar pengecualian C2 resmi (Handoff 03) ke Bagian 9.5 — cover, "Tentang Nganggur Bercerita", dan closing page dikecualikan; daftar lengkap ada di Page Map v0.7.
- **v0.6 (15 Juli 2026):** **Koreksi berdasarkan Handoff 05.** (a) Bug versi — judul H1 sempat tertinggal di "v0.4" meski metadata sudah v0.5, sekarang diperbaiki. (b) **Koreksi material:** warna ikon Publisher Mark footer (C2) yang benar adalah **full-color** (kotak `#07565F` + garis/bookmark `#FF7900` + buku/pensil putih), sama seperti versi cover — bukan monokrom Deep Teal seperti tertulis sebelumnya di Bagian 5 dan 9.5. Hanya teks "Nganggur Bercerita" yang solid Deep Teal, bukan ikonnya. Dikonfirmasi Reza via Blueprint Induk v1.8 Bagian 5.3.
- **v0.7 (15 Juli 2026):** **Koreksi berdasarkan Handoff 07 — murni rujukan versi basi, bukan bug material.** Bagian 9 dan 9.3 memperbarui rujukan "Blueprint Induk v1.7" → v1.9, dan "PDF Production Brief v0.4" → v0.7. Rujukan "nganggur-bercerita-reference" **tetap v1.5** (bukan v1.6 seperti usulan awal Handoff 07) — dikonfirmasi langsung dari isi Blueprint Induk v1.9 Bagian 21 bahwa dokumen reference belum direvisi ke v1.6 saat ini.
- **v0.8 (15 Juli 2026):** Reference document v1.6 sekarang terkonfirmasi resmi (dicek langsung isinya, tidak ada perubahan substansi selain klarifikasi warna ikon yang sudah diterapkan). Rujukan "nganggur-bercerita-reference v1.5" diperbarui jadi v1.6.
- **v0.9 (15 Juli 2026):** **Koreksi berdasarkan Handoff 10 (Blueprint Induk).** Bagian 9.5 masih merujuk "Blueprint Induk v1.8" padahal seharusnya v1.9 (inkonsistensi internal — header dan bagian lain CDB sudah v1.9). Diperbaiki. Rujukan PDF Production Brief diperbarui ke v0.9 mengikuti bump bersamaan.

---

## 1. Palet Warna

Dibangun dari arahan yang sudah ada di file 01 Bagian 11 (bukan dibuat baru), dikonkretkan jadi hex code:

| Fungsi | Warna | Hex |
|---|---|---|
| Latar utama | Off-white | `#FAF6EE` |
| Latar sekunder/kartu | Cream muda | `#F1E8D6` |
| Teks utama | Charcoal gelap | `#262321` |
| Aksen primer | Teal (konten) | `#1F6F64` |
| Aksen sekunder | Soft blue | `#5C87A6` |
| Aksen CTA/highlight | Coral | `#E8613C` |
| Warna peringatan | Coral gelap/burnt orange | `#C24A1F` |

**Batasan:** maksimal 5–7 warna fungsional (sesuai Visual Audit rekomendasi), semua di atas totalnya 7 — jangan tambah varian baru tanpa alasan kuat. Ini juga koreksi langsung dari masalah Cuan Modal Kuota (hijau dalam terlalu banyak variasi saturasi).

Hijau maskot (kaos polo) **tidak dipakai sebagai warna aksen utama layout** — biarkan hijau jadi ciri khas maskot saja.

**Catatan sinkronisasi tiga warna teal/aksen berbeda (diperbarui v0.3):** produk ini punya **tiga** kode warna yang mirip secara visual tapi sengaja terpisah fungsinya — jangan disatukan:

| Elemen | Kode | Fungsi |
|---|---|---|
| Teal konten (badan PDF) | `#1F6F64` | Aksen layout, komponen (info box, dsb.) |
| Deep Teal logo (Publisher Mark, generasi kedua) | `#07565F` | Elemen brand mark (cover + footer semua halaman) — **bukan** `#1E6157` lagi (kode lama, sudah pensiun) |
| Hijau maskot (outfit) | Medium green (bukan hex resmi, "alami") | Outfit "Pria Sarung Hijau", tidak disamakan ke kode manapun di atas |

Ketiganya **tetap dibiarkan berbeda secara sengaja** — bukan inkonsistensi yang perlu diperbaiki.

---

## 2. Tipografi

File 01 Bagian 12 mengunci **maksimal 2 keluarga font** khusus untuk cover. PDF Production Brief menyebut "3 fungsi" (display/body/accent) — ini **tidak kontradiksi**: fungsi accent dicapai lewat varian bold/italic dari font body, bukan font ketiga. Total tetap 2 typeface untuk konten.

| Fungsi | Font (tersedia di Canva) | Keterangan |
|---|---|---|
| Display / Judul | **Poppins** (ExtraBold/Bold) | Sans serif modern, geometrik, tegas |
| Body / Isi | **Inter** atau **Work Sans** (Regular/Medium) | Sangat terbaca di ukuran kecil, cocok mobile |
| Accent / Catatan kecil | Work Sans **Italic** atau Poppins **Medium** kecil | Varian dari 2 di atas, bukan font ketiga |

**Catatan:** Publisher Mark (cover & footer) memakai Poppins ExtraBold (nama merek)/SemiBold (tagline)/Regular ("Diproduksi oleh") sesuai spesifikasi logo resmi — senada dengan font judul cover karena kebetulan sama-sama Poppins.

**Ukuran dasar (disesuaikan lagi saat Design Pilot):**
- Judul modul: 28–32pt
- Subjudul: 18–20pt
- Body/isi: 12–13pt
- Caption/label: 9–10pt
- **Footer mark (baru):** teks "Nganggur Bercerita" 7–8pt, ikon ~5–6mm tinggi (lihat Bagian 9.5)

---

## 3. Margin & Safe Area

Ukuran A4 Portrait (210 × 297mm):

- Margin atas/bawah: 20mm
- Margin kiri/kanan: 18mm
- Area footer (nomor halaman **+ Publisher Mark versi footer**): 12mm dari tepi bawah — lihat Bagian 9.5 untuk penempatan presisi
- Safe area tambahan dari garis potong: 10mm
- Area khusus Publisher Mark versi lengkap (cover saja): lihat Bagian 9.3

---

## 4. Sistem Ilustrasi

**Editorial vector + subtle collage** sebagai gaya tunggal untuk ilustrasi pendukung — bukan gaya AI 3D mengilap.

**Maskot** adalah pengecualian — gaya cutout fotorealistik sesuai Character Reference Sheet v0.5, hanya muncul di cover.

**Publisher Mark (logo, kedua versi — lengkap dan footer)** adalah gaya ketiga yang berdiri sendiri — line-art sederhana. Versi footer khususnya sangat kecil dan berulang di setiap halaman, tapi tetap dianggap brand mark, bukan ilustrasi konten yang bersaing dengan sistem ilustrasi editorial.

---

## 5. Spesifikasi Komponen (Konsisten di Semua Halaman)

| Komponen | Warna Latar | Border/Aksen | Ikon |
|---|---|---|---|
| Catatan Penting / Info | Cream `#F1E8D6` | Border kiri teal 4px | Ikon info (i) |
| Jangan Lakukan Ini / Warning | Coral muda 10% opacity | Border kiri coral `#C24A1F` 4px | Segitiga peringatan |
| Contoh Skenario Pemula | Off-white dengan border dashed | Border dashed teal | Ikon orang/percakapan kecil |
| Coba Praktikkan / Checklist | Putih bersih | Checkbox teal | Centang teal saat terisi |
| Prompt AI | Charcoal `#262321` (dark card) | Border teal 2px | Ikon sparkle kecil |
| Worksheet | Cream dengan garis ruled halus | — | — |
| Ringkasan Modul | Banner teal-coral gradient tipis | — | Ikon checklist besar |
| Micro-CTA | Pill button coral fill | — | Panah kecil |
| **Publisher Mark — Footer (C2)** *(baru)* | Transparan (tidak ada background box) | — | Ikon buku+pena kecil, **full-color** (kotak `#07565F` + garis/bookmark `#FF7900` + buku/pensil putih), sama seperti versi cover — teks "Nganggur Bercerita" solid Deep Teal `#07565F` |

**Aturan tetap:** satu komponen = satu bentuk dan satu warna di seluruh 12 modul.

---

## 6. Elemen yang Dihindari (Diperbarui v0.4)

- Tidak ada halaman landscape di badan utama
- Tidak ada lebih dari 1 hero element per halaman
- Tidak ada tekstur kertas/scrapbook di belakang paragraf panjang
- Tidak ada bold berlebihan dalam satu paragraf
- Tidak ada logo TikTok asli atau tampilan UI yang ditiru mendetail
- ~~Tidak ada watermark logo/monogram di halaman isi~~ **DIBALIK di v0.4: Publisher Mark versi footer (C2) kini WAJIB di setiap halaman isi** — lihat Bagian 9.5
- **Tetap dilarang:** Monogram NB atau Icon Only sebagai watermark halaman isi — hanya C2 yang diizinkan di sana
- **Tetap dilarang:** Publisher Mark versi lengkap (tier C, dengan "Diproduksi oleh") di halaman isi — versi lengkap eksklusif cover dan sampul Template Factory

---

## 7. Spesifikasi Teknis Produksi

- **Resolusi:** 150–300 DPI
- **Mode warna:** RGB
- **Format akhir:** PDF Master + PDF Preview
- **Thumbnail Lynk.id:** rasio berbeda dari cover PDF — crop/adaptasi terpisah

---

## 8. Langkah Berikutnya

Design Pilot (lihat Design Pilot Page List v0.5, LOCKED) mencerminkan: (a) palet Publisher Mark generasi kedua, (b) footer mark full-color di seluruh halaman isi biasa, (c) daftar pengecualian final.

**Rekomendasi batch produksi:** per modul (12+ batch kecil), tidak berubah dari rencana sebelumnya.

---

## 9. Sistem Logo & Publisher Mark

Sistem lengkap (5 tier, alasan desain) ada di Blueprint Induk v1.9 Bagian 5.3 dan nganggur-bercerita-reference v1.6 Bagian 8 — bagian ini fokus ke penerapan di produk Affiliate TikTok.

### 9.1 Aset yang dipakai di produk ini
**Publisher Mark versi lengkap (tier C)** di cover, dan **Publisher Mark versi footer (tier C2)** di setiap halaman isi. Primary Logo/Secondary Logo/Monogram NB/Icon Only relevan di level studio, bukan di dalam PDF produk ini.

### 9.2 Warna & font — Generasi Kedua (diperbarui v0.3)
Deep Teal `#07565F` (utama), Orange `#FF7900` (aksen ikon), Charcoal `#1F1F1F` (teks "Diproduksi oleh" — khusus versi lengkap). Font Poppins ExtraBold/SemiBold/Regular sesuai fungsi. **Kode generasi pertama (`#1E6157`/`#D9CBB2`) sudah pensiun, tidak dipakai lagi di dokumen manapun sejak v0.3.**

### 9.3 Penempatan Publisher Mark versi lengkap di cover
Pojok kiri atas, safe area 18mm kiri/20mm atas. Ukuran presisi di PDF Production Brief v0.9 Bagian 6A. Tidak tumpang tindih dengan area maskot (kanan/bawah).

### 9.4 Aturan Publisher Mark versi lengkap — TETAP tidak berubah
Publisher Mark versi lengkap (tier C, dengan "Diproduksi oleh") **eksklusif** untuk cover PDF utama dan sampul Template Factory. **Tidak** dipakai sebagai elemen footer halaman isi — itu tugas C2 (Bagian 9.5).

### 9.5 Publisher Mark versi Footer (C2) — WAJIB

Ini hasil usulan chatroom PDF (handoff 15 Juli 2026) yang disetujui dan dikunci Blueprint Induk v1.9 Bagian 5.3 sebagai standar lintas semua produk Nganggur Bercerita, bukan cuma produk ini.

| Spesifikasi | Ketentuan |
|---|---|
| Konten | Ikon buku+pena kecil + teks "Nganggur Bercerita" (**tanpa** "Diproduksi oleh") |
| Ukuran ikon | ~5–6mm tinggi |
| Ukuran teks | 7–8pt |
| **Warna ikon** *(dipisah v0.6)* | **Full-color** — kotak `#07565F` + garis/bookmark `#FF7900` + buku/pensil putih, sama seperti Publisher Mark versi cover, **bukan** monokrom |
| **Warna teks** *(dipisah v0.6)* | Solid/opacity penuh Deep Teal `#07565F` — **bukan** watermark pudar/transparan |
| Posisi | Footer, sejajar nomor halaman, konsisten di satu sisi sepanjang buku (disarankan kanan bawah) |
| Cakupan | Wajib di halaman isi biasa (Modul 1–12, bonus #8/#10/#12 yang menyatu ke PDF, halaman Langkah Berikutnya, Cara Menggunakan Bonus) |
| **Dikecualikan** *(final, Page Map v0.9)* | Halaman Identitas/Copyright, "Tentang Nganggur Bercerita", Closing Page Final, bonus #1 Checklist Mulai dari Nol — semua sudah final, tidak ada lagi status "perlu konfirmasi" |
| Tidak berlaku di | Cover depan (pakai versi lengkap tier C, bukan C2), cover belakang (tidak pakai logo versi apa pun) |

**Kenapa ini tidak dianggap "watermark skripsi" yang selama ini dihindari:** ukurannya sangat kecil (setara elemen footer, bukan elemen berdiri sendiri di tengah halaman), solid bukan transparan, dan posisinya konsisten menyatu dengan nomor halaman yang memang sudah ada di setiap halaman.

---

*Dokumen ini LOCKED setelah direview Reza. Perubahan pada palet/tipografi (Bagian 1–2) dan sistem logo (Bagian 9) memerlukan sinkronisasi ulang karena dipakai di seluruh ~220 halaman dan lintas produk.*
