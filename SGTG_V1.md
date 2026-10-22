# SGTG V.1 — Standar Game Toto Gutomo

**Status:** Resmi
**Versi:** 1.0
**Tanggal berlaku:** 22 Oktober 2026
**Disusun:** Toto Gutomo (Guru SMA Negeri 3 Maliku) bersama Claude
**Acuan tampilan:** game HaHe (hahe.totogutomo.com)

Dokumen ini hanya mengatur **rasa dan kelengkapan game**. Jenis game **tidak ditetapkan di sini**; dibahas per game sesuai materi dan/atau TP. SGTG berdiri sendiri dan tidak bergantung pada SCTG.

---

## Prinsip Inti

> Murid belajar **lewat aksi di dalam game**, bukan lewat soal yang diberi kulit game, dan bukan course yang ditempeli game.

Ciri game yang benar: murid melakukan sesuatu (memilih jalan, menangkap, membangun, melayani, dan sejenisnya); materi hadir sebagai isi dunia game; tidak ada bahasa course ("Langkah 3/10", centang "saya sudah membaca", teks panjang).

---

## Aturan

### 1. Tampilan: 2D dengan efek pseudo-3D
- Game 2D, berwarna penuh, latar penuh, gaya kartun tebal dan cerah ala HaHe.
- Kesan 3D dibuat tanpa render 3D: **gradasi** (sisi terang dan gelap), **kilap** (kilau lengkung pada objek), **bayangan** (bayangan dasar dan bayangan lembut).
- Efek dibuat sebagai "resep" yang dipakai ulang di seluruh game, bukan dibuat ulang tiap objek.
- Satu dunia, satu tema, satu gaya dari layar awal sampai akhir.

### 2. Perangkat: mobile, desktop, dan IFP
- Satu berkas dimainkan di HP (tegak dan mendatar), laptop/desktop, dan IFP.
- Di IFP tampilan dan tombol diperbesar agar terbaca dan tersentuh dari jauh.
- **Saat bermain, layar tidak menggulir:** semua yang perlu dilihat dan disentuh muat dalam satu layar.

### 3. Tombol game
- Bulat, besar, jelas, dan responsif terhadap sentuhan langsung (di desktop juga bisa diklik).
- Tidak memakai tombol bergaya formulir.
- Ukuran minimum ditetapkan sekali di mesin game: nyaman disentuh di HP, lebih besar di IFP.

### 4. SFX (efek suara)
- Dibuat dari kode, tanpa berkas luar.
- Tersedia tombol hidup/mati dan pengatur volume.
- Tetap terdengar jelas di atas SBG.

### 5. SBG (backsound)
- Tempat disediakan di folder game; **berkas diisi oleh Toto Gutomo**.
- Tersedia tombol hidup/mati dan pengatur volume.
- SBG mulai setelah sentuhan pertama murid (peramban umumnya menahan bunyi sebelum itu).
- **Sebelum build,** Claude mengingatkan Toto Gutomo untuk mengirim tangkapan layar **lisensi dan sumber** SBG. Jika tidak dikirim, game dianggap **tanpa SBG** (tombol dan volume SBG tidak ditampilkan).
- Lisensi dan sumber SBG dicantumkan di Tentang.

### 6. Jenis game: dibahas dulu, sesuai materi dan/atau TP
- Alur diskusi: **materi/TP → aksi belajar apa yang terjadi → baru jenis game**.
- Tidak ada kode sebelum perintah eksplisit Toto Gutomo ("Gas kode", "Bangun Kode", "Update Kode", atau sejenisnya).
- Mockup (bila perlu) baru dibahas setelah konsep matang, dan dibuat hanya atas perintah eksplisit.
- Isi akademik (fakta, angka, istilah) diperiksa sebelum penyerahan.

### 7. Footer dan Tentang
- Footer permanen: `[nama game] ©[tahun pembuatan] | totogutomo.com` (contoh bentuk: `Nama Game ©2026 | totogutomo.com`). Tahun = tahun game pertama dibuat, tidak berubah saat update.
- Tentang memuat: nama game, deskripsi singkat, **Toto Gutomo, S.Pd., Gr., M.Pd.** lalu di bawahnya **"Guru SMA Negeri 3 Maliku"**, teknologi yang benar-benar dipakai, lisensi dan kredit aset (termasuk SBG), serta tautan totogutomo.com.

---

## Kenyamanan Dasar (ala HaHe)
- Tombol **Jeda** selama bermain.
- Tombol **Back Android** bekerja masuk akal (kembali ke layar sebelumnya; saat bermain membuka Jeda).
- Permainan **tersimpan otomatis** dan dapat dilanjutkan (opsional, diputuskan per game).

## Pengujian Ringkas
- **Dikerjakan Claude (hemat):** game dimainkan sampai selesai sekali lewat skrip; cek tidak ada kesalahan, tidak ada gulir, dan tombol bisa diketuk di tiga ukuran (HP tegak, HP mendatar, IFP); tinjau 3 gambar saja (satu per ukuran).
- **Dinilai Toto Gutomo di perangkat asli:** rasa "game banget", mutu efek 3D, keseruan.
- Bila satu game rumit sekali diuji lewat skrip, Claude melapor dulu sebelum menghabiskan banyak token.

## Penyerahan
- Satu berkas siap unggah (atau paket sesuai kebutuhan game), kode uji/debug sudah dibersihkan.
- Daftar game diperbarui di `DAFTAR_GAME.md`.
