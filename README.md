# Relasi dan Fungsi — Website Interaktif Bab 4

Website interaktif satu file untuk **Bab 4 Relasi dan Fungsi, Matematika SMP/MTs Kelas VIII**.

## Sumber materi

Matematika untuk SMP/MTs Kelas VIII, Kemendikbudristek RI, 2022, Mohammad Tohir dkk.,
ISBN 978-602-427-919-6, Bab 4 (hal. 138–206). Semua definisi, contoh, dan soal Uji
Kompetensi mengikuti buku tersebut. Soal berlabel "latihan tambahan" dibuat mengikuti
pola soal buku.

## Isi

- **A. Himpunan** — definisi, kardinalitas, himpunan semesta, 3 cara penyajian, berhingga/tak berhingga
- **B. Relasi** — domain/kodomain/range, 3 cara penyajian, Contoh 4.4 ("kurang dari")
- **C. Fungsi** — definisi, 5 cara penyajian f(x) = 2x, nilai fungsi, Contoh 4.8–4.11, tarif taksi B(x) = 3000x + 7500
- **D. Korespondensi Satu-satu (pengayaan)** — syarat n(A) = n(B), banyaknya n!

## Fitur interaktif (JavaScript murni, tanpa library)

1. Header sticky, peta konsep, progress bar baca, mode gelap/terang, responsif
2. Lab Diagram Panah (data Tabel 4.1) — klik siswa, toggle panah / pasangan berurutan / diagram Cartesius
3. Lab "Fungsi atau Bukan?" — 6 kartu + generator pasangan acak dengan pemeriksaan otomatis
4. Kalkulator f(x) = ax + b dengan langkah substitusi + preset; kalkulator taksi dua arah (km → tarif, tarif → km)
5. Grafik interaktif f(x) = ax + b (canvas, slider a dan b, titik potong sumbu)
6. Kalkulator n! untuk korespondensi satu-satu (preset 5! = 120, 6! = 720)
7. Kuis 10 soal (Uji Kompetensi + latihan bab) dengan pembahasan dan skor terbaik di localStorage
8. Contoh soal langkah-demi-langkah (4.4, 4.8, 4.10)

## Menjalankan

Buka `index.html` langsung di peramban, atau jalankan server lokal:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000/index.html
```

## GitHub Pages

Repo target (baru): **`relasi-dan-fungsi`** — https://hardiansyah-math.github.io/relasi-dan-fungsi/

```bash
# dari folder ini, unggah index.html ke repo relasi-dan-fungsi (branch main),
# lalu aktifkan GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
```

Satu-satunya file yang dibutuhkan adalah `index.html` (CSS + JS inline, tanpa dependensi
eksternal), sehingga situs langsung jalan di GitHub Pages dan offline.
