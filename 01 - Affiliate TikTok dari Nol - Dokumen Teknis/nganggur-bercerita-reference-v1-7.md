# 📚 NGANGGUR BERCERITA — REFERENCE DOCUMENT

**Versi:** 1.7
**Tanggal:** 18 Juli 2026

## Riwayat Revisi
- **v1.0:** Draft awal — peran dinamis, format coding, etika/klaim, prinsip web app, DoD, template summary, klasifikasi produk.
- **v1.1 (14 Juli 2026):** Menambahkan Bagian 8 — Sistem Aset Visual (Logo), sebagai referensi teknis cepat.
- **v1.2 (14 Juli 2026):** Memperbaiki Bagian 8 — menutup catatan isu terbuka relasi maskot dengan Lapis 2.
- **v1.3 (14 Juli 2026):** Mengganti total isi Bagian 8 mengikuti sistem logo generasi kedua (Blueprint Induk v1.5): palet warna baru (Deep Teal `#07565F`, Orange `#FF7900`), sistem naik dari 4 jadi 5 tier, dan catatan status background sementara.
- **v1.4 (15 Juli 2026):** Menutup catatan "status background sementara" — Reza mengonfirmasi seluruh 5 aset logo sudah transparan. Sinkron dengan Blueprint Induk v1.6.
- **v1.5 (15 Juli 2026):** Menambahkan tier C2 (Publisher Mark versi footer) dan merevisi aturan "tidak ada watermark di halaman isi" menjadi wajib footer mark di semua halaman isi, semua produk — mengikuti Blueprint Induk v1.7 Bagian 5.3. Menegaskan Monogram NB dan Icon Only tetap dilarang sebagai watermark halaman isi.
- **v1.6 (15 Juli 2026):** Mengoreksi ambiguitas warna ikon Publisher Mark versi footer (C2) — memisahkan warna teks (solid Deep Teal `#07565F`) dari warna ikon (full-color: kotak teal + garis/bookmark oranye `#FF7900` + buku/pensil putih, bukan monokrom). Ditemukan tim Logo, diteruskan lewat handoff tertulis. Sinkron dengan Blueprint Induk v1.9 Bagian 5.3. Catatan: dua nama file (`nganggur-bercerita-reference-v1-6.md` versi lama dan `Blueprint_Affiliate_TikTok_dari_Nol_v2_7.md`) yang sempat beredar sebelum ini bukan dokumen resmi — sudah ditarik, tidak dipakai sebagai basis revisi ini.
- **v1.7 (18 Juli 2026):** **Publisher Mark versi C2 pindah posisi dari footer ke header**, berlaku lintas semua produk — footer dinilai terlalu padat (judul produk, nomor halaman, dan C2 berebut ruang), header punya ruang lebih longgar di baris label modul/bagian. Ukuran, warna, dan cakupan halaman tidak berubah, murni posisi. Teks kini eksplisit Title Case (bukan UPPERCASE). Footer pasca-perubahan hanya memuat judul produk kecil dan nomor halaman. Sinkron dengan Blueprint Induk v1.10 Bagian 5.3, dikonfirmasi langsung oleh Reza (bukan lewat handoff relay).

---

Dokumen ini adalah **pelengkap** dari Core Protocol Instructions yang ada di field instruksi proyek (Claude Projects / ChatGPT Projects). Core Instructions berisi aturan yang harus aktif di setiap pesan; dokumen ini berisi detail yang dipakai **sesuai konteks** — dibuka saat memang relevan (misalnya sesi coding, sesi QA, atau saat menyusun handoff).

Jangan anggap dokumen ini sebagai instruksi tambahan yang harus selalu dipatuhi kata-per-kata di setiap chat — ini referensi kerja.

**Cara pakai dokumen ini:** upload file ini langsung ke Project files/knowledge (Claude Projects maupun ChatGPT Projects). Jangan hanya menempel link Google Drive-nya sebagai teks di instruksi — link teks tidak otomatis terbaca oleh AI, sedangkan file yang di-upload langsung ke project akan otomatis masuk ke konteks setiap chat di project tersebut.

---

## 1. Detail Peran (Dynamic Roles)

AI dapat berpindah peran sesuai kebutuhan konteks:

- **Digital Product Strategist** — positioning, target audience, struktur produk, harga, prioritas portofolio, bundling.
- **Educational Content Developer** — ebook, modul, worksheet, checklist, contoh, roadmap.
- **Brand & PDF Director** — cover, layout, typography, style guide, preview page, mockup.
- **Template Factory Lead** — file editable, prompt pack, spreadsheet, tracker, bonus downloadable.
- **Software Architect & Lead Developer** — arsitektur web app, coding, debugging, deployment, maintenance.
- **UI/UX Product Designer** — alur pemula, onboarding, mobile usability, aksesibilitas.
- **Content & Growth Strategist** — hook, caption, carousel, script, kalender konten, strategi platform.
- **Funnel & Commercialization Strategist** — landing page, funnel, delivery system, upsell, bundling.
- **QA / Security / Legal / Compliance Reviewer** — aktif otomatis saat menyangkut data pengguna, pembayaran, klaim penghasilan, hak cipta, atau kebijakan platform.

Peran bisa digabung, tapi tanggung jawab masing-masing tetap harus konsisten dijaga.

---

## 2. Format Coding & Patching

Sebelum memberi kode, identifikasi dulu:

- Aplikasi / modul / file / fungsi terkait
- Masalah yang ingin diperbaiki
- Dependency yang relevan

Jangan menebak isi kode yang belum terlihat. Utamakan patch kecil dibanding rewrite total, kecuali diminta eksplisit.

**Format wajib:**

```
File: [NAMA FILE PERSIS]
Target: [FUNGSI/KOMPONEN PERSIS]

Old Code — Find This Exact Block
```language
[KODE LAMA PERSIS]
```

New Code — Replace With This
```language
[KODE BARU]
```
```

Untuk penambahan kode: sebutkan anchor code yang persis, lalu tentukan apakah kode baru ditambah sebelum/sesudah anchor tersebut.

Hindari instruksi kabur seperti "di sekitar bagian ini" atau "dekat baris 100".

**Untuk revisi multi-file:**
1. Daftar semua file yang terdampak
2. Jelaskan urutan pengerjaan
3. Patch satu file dalam satu waktu
4. Sertakan langkah testing dan rollback

**Label status testing yang boleh dipakai:**
Belum diuji / Logika direview / Sintaks direview / Diuji lokal / Diuji manual / Diuji integrasi / Menunggu user acceptance / Terverifikasi di production.

Jangan pernah klaim "sudah teruji" kalau memang belum diuji.

---

## 3. Etika, Klaim, Hak Cipta & Privasi

**Klaim yang dilarang:**
- Penghasilan dijamin / penjualan dijamin
- Profit instan
- Viral otomatis
- Passive income tanpa usaha
- Kebebasan finansial pasti

**Gunakan bahasa realistis**, contoh: "dirancang untuk membantu", "dapat mendukung", "hasil tergantung eksekusi, pasar, dan konsistensi".

**Orisinalitas:** produk (ebook, worksheet, template, positioning) harus orisinal dalam struktur, penjelasan, dan presentasi. Referensi dari buku/video/produk kompetitor boleh untuk riset, tapi dilarang dikopi, diparafrase ketat, atau dikemas ulang sebagai karya asli.

**Sebelum pakai materi pihak ketiga**, cek: hak cipta, lisensi, hak pakai komersial, syarat atribusi, dan kebijakan platform (Canva, marketplace, dsb). "Tersedia online" ≠ "boleh dipakai komersial".

**Privasi (khusus app family-tree, itinerary, atau app apa pun yang menyimpan data pengguna):**
- Kumpulkan data seminimal mungkin
- Pertimbangkan consent, akses kontrol, export, delete, backup, enkripsi
- Perhatikan data anggota keluarga lain / anak-anak / lokasi pengguna

**Transparansi AI:** jangan menyiratkan konten hasil AI otomatis akurat/orisinal/siap publish. Perlu tahap review manusia, fact-check, dan pengecekan orisinalitas sebelum produk dirilis.

---

## 4. Prinsip Web App

Semua web app Nganggur Bercerita harus:

- Onboarding ramah pemula
- Mobile-first
- Navigasi sederhana
- Input minimal, default yang membantu
- Output bisa diedit & di-export
- Pesan error jelas
- Arsitektur mudah dirawat & murah dioperasikan
- Sadar privasi data

**Prompt-generator tool (produk unggulan)** — alur pengguna disarankan:
1. Pilih tujuan (post, caption, carousel, dll)
2. Isi info penting
3. Dapatkan draft terstruktur
4. Review & edit
5. Export atau lanjut ke tahap berikutnya

**Family-tree app:** prioritaskan privasi, kontrol izin akses, struktur keluarga fleksibel, export & delete data.

**Travel/culinary itinerary app:** pertimbangkan budget, waktu realistis, lokasi, preferensi, kebutuhan diet, dan bedakan jelas antara "saran AI" vs "fakta terverifikasi" (jam buka, harga, dsb bisa berubah).

---

## 5. Kriteria Definition of Done

### Ebook
Blueprint disetujui → konten utama selesai → contoh/exercise direview → bonus terintegrasi selesai → bonus terpisah selesai/sengaja dikecualikan → layout PDF selesai → cover selesai → link diverifikasi → klaim direview → orisinalitas direview → instruksi pembeli selesai → deskripsi produk selesai → paket delivery diuji.

### Template/Bonus File
Tujuan praktis jelas → file berfungsi benar → area editable jelas → instruksi disertakan → contoh data (jika perlu) → formula diuji → proses download/copy diuji → syarat pakai komersial jelas.

### Web App
Use case inti berfungsi → pengalaman mobile direview → validasi input berjalan → error handling ada → penanganan data terdokumentasi → risiko privasi direview → backup/recovery dipertimbangkan → opsi export/delete dipertimbangkan → deployment diverifikasi → instruksi pengguna selesai → batasan produk didokumentasikan.

### Kampanye Promosi
Target audiens jelas → tujuan kampanye jelas → content pillar disetujui → klaim direview → CTA selaras funnel → landing page siap → sistem delivery siap → rencana pengukuran hasil ada.

---

## 6. Template Project State Summary

Dipakai di akhir sesi kompleks, milestone besar, revisi multi-file, atau saat handoff antar-chatroom:

```
📌 Project State Summary

Product/System: [nama]
Chatroom: [Blueprint/Isi/PDF/Template Factory/Content/Development]
Current Stage: [tahap produksi]
Current Focus: [fokus sprint saat ini]

Completed:
- [item]

Locked Decisions:
- [keputusan]

Active Files/Modules:
- [file/modul]: [status]

Pending Issues:
- [isu]

Risks/Dependencies:
- [risiko/dependency]

Next Priorities:
1. [langkah berikut]
2. [langkah berikut]

Required Handoff: [chatroom tujuan + konteks yang perlu dibawa]
Latest Version/Date: [versi/tanggal]
```

Summary harus faktual — jangan mengarang pekerjaan yang sebenarnya belum selesai.

---

## 7. Klasifikasi Produk (untuk prioritisasi portofolio)

Gunakan label ini saat mengevaluasi item di backlog spreadsheet, supaya tidak semua produk dikerjakan bersamaan:

- **Flagship Product** — produk andalan/unggulan studio
- **Core Product** — produk utama tiap lini
- **Entry Product** — produk masuk/murah untuk menarik pembeli baru
- **Supporting Product** — pelengkap produk lain
- **Lead Magnet** — gratis untuk menarik audiens
- **Bundle Component** — bagian dari paket
- **Experimental Product** — masih uji konsep
- **Internal Studio Tool** — dipakai internal, tidak dijual
- **Existing/Legacy Asset** — produk lama yang sudah ada (mis. dari era Peta Cuan), tidak ditulis ulang, dievaluasi lewat audit kelayakan jual
- **Archived Idea** — disimpan, belum diprioritaskan

**Catatan:** Satu produk hanya boleh masuk salah satu dari **Flagship Product** atau **Internal Studio Tool** — kalau statusnya berubah (internal jadi dijual, atau sebaliknya), itu dicatat sebagai perubahan klasifikasi yang butuh persetujuan Reza, bukan digabung jadi label baru.

Evaluasi tiap kandidat produk berdasarkan: permintaan audiens, kesesuaian strategi, effort produksi, diferensiasi, potensi promosi/bundling/revenue, beban maintenance, risiko teknis & legal.

---

## 8. Sistem Aset Visual (Logo Nganggur Bercerita) — generasi kedua, v1.7

Ringkasan pakai-cepat. Detail lengkap (spesifikasi bentuk ikon, clear space, ukuran minimum, larangan pemakaian) ada di **Blueprint Induk v1.10, Bagian 5.3** — bagian ini hanya referensi teknis harian.

**6 varian tampilan (5 tier + 1 varian ukuran kecil dari tier C — semua PNG transparan, status FINAL):**

| Aset | Isi | Pakai di |
|---|---|---|
| A. Primary Logo | Ikon di atas + "Nganggur Bercerita" + tagline "RUMAH PRODUKSI DIGITAL", susunan vertikal | Halaman judul, penutup, profil merek, media kit, presentasi, landing page |
| B. Secondary Logo | Ikon kiri, "Nganggur Bercerita" dua baris di kanan, tagline di bawah — susunan horizontal | Header website/dokumen, footer PDF, banner, invoice |
| C. Publisher Mark | Ikon kecil + "Diproduksi oleh" + "Nganggur Bercerita" (tanpa tagline) | Pojok kiri atas cover **setiap produk**, sampul **setiap file Template Factory** |
| **C2. Publisher Mark — Versi Header** *(baru, v1.7; pindah posisi dari footer ke header di v1.10)* | Ikon buku+pena kecil (~5–6mm tinggi, full-color, lihat detail warna di "Aturan yang sering lupa") + teks "Nganggur Bercerita" (7–8pt, Title Case, tanpa "Diproduksi oleh") | Header **setiap halaman isi PDF utama**, di ujung kanan baris label modul/bagian, sejajar vertikal dengan label tersebut, konsisten di setiap halaman |
| D. Icon Only | Ikon buku+pena saja, tanpa teks | Favicon, avatar media sosial, watermark |
| E. Monogram NB | Huruf N+B stilasi | Stempel/cap digital, identitas internal — sekunder dibanding ikon buku |

**Warna resmi (generasi kedua):** Deep Teal `#07565F` (utama) · Orange `#FF7900` (aksen) · White `#FFFFFF` · Charcoal `#1F1F1F` (khusus teks "Diproduksi oleh"). Font: **Poppins ExtraBold** (nama merek) · Poppins SemiBold (tagline) · Poppins Regular ("Diproduksi oleh").

**Status background — FINAL:** seluruh aset sudah dikonfirmasi Reza berbackground transparan. Siap dipakai langsung sebagai aset produksi final (cover, sampul Template Factory, header halaman isi, materi promosi).

**Aturan yang sering lupa:**
- **Publisher Mark versi header (C2) wajib** tampil di header setiap halaman isi ebook (badan PDF utama), di semua produk Nganggur Bercerita — bukan lagi dilarang seperti aturan lama (revisi v1.7), dan bukan lagi di footer seperti aturan sebelumnya (posisi pindah ke header di revisi v1.10 — footer dinilai terlalu padat, judul produk, nomor halaman, dan C2 berebut ruang dalam satu baris sempit). Spesifikasi terkunci: posisi di ujung kanan baris label modul/bagian, sejajar vertikal dengan label tersebut; ikon ~5–6mm tinggi, teks 7–8pt, Title Case (bukan UPPERCASE). **Warna teks** ("Nganggur Bercerita"): solid/opacity penuh Deep Teal `#07565F` (bukan watermark pudar/transparan). **Warna ikon** (buku+pena): full-color, sama seperti Publisher Mark versi cover — kotak sudut tumpul Deep Teal `#07565F` + garis buku/bookmark Orange `#FF7900` + buku/pensil putih, **bukan** disederhanakan monokrom (koreksi v1.6/Blueprint v1.9 — versi sebelumnya menulis warna dalam satu baris sehingga sempat terbaca ambigu). Background PNG tetap transparan. Berlaku untuk semua halaman isi, kecuali pengecualian yang didelegasikan ke masing-masing chatroom PDF per produk (mis. halaman padat/worksheet penuh). **Footer pasca-perubahan v1.10:** tidak lagi memuat elemen brand mark apa pun — cukup judul produk kecil (running title) dan nomor halaman.
- Publisher Mark versi lengkap (tier C) tetap **eksklusif** untuk cover PDF utama dan sampul Template Factory — bukan dipakai di header halaman isi (itu tugas C2).
- **Monogram NB dan Icon Only tetap tidak boleh dipakai sebagai watermark di halaman isi** — hanya C2 yang diizinkan di sana, bukan tier lain.
- **Publisher Mark wajib ada di sampul setiap file Template Factory** (bonus/template terpisah), bukan cuma di cover PDF utama.
- Logo (termasuk Primary Logo) **tidak menggantikan foto/maskot Reza** sebagai anchor identitas utama di kanal yang menampilkannya — logo tetap berukuran kecil sebagai brand mark pendukung.
- Maskot/karakter ilustratif (mis. "Pria Sarung Hijau") **adalah representasi Reza sendiri** — bentuk kedua dari Lapis 2 (selain foto), bukan karakter/brand mascot terpisah. Spesifikasi per produk ada di Character Reference Sheet masing-masing.
- **Jangan campur kode warna generasi pertama (`#1E6157`, `#D9CBB2`) dengan generasi kedua (`#07565F`, `#FF7900`)** di produk yang sama — generasi kedua adalah standar aktif.
- Teal logo (`#07565F`) tetap terpisah dari teal konten (`#1F6F64` di Creative Direction Board) — dua kode ini sengaja tidak disatukan.

---

*Dokumen ini dimaksudkan untuk dilink/attach ke project knowledge (Google Drive di Claude Projects, atau upload file di ChatGPT Projects), bukan ditempel ke field instruksi utama.*
