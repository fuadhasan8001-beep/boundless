# Portofolio Kolektif Siswa

Situs portofolio statis dengan arsip berisi konsep halaman alternatif.

## Menjalankan secara lokal

Buka `index.html` di peramban, atau sajikan folder ini dengan server web statis. Contoh jika Python tersedia:

```sh
python3 -m http.server 8000
```

Lalu buka <http://localhost:8000>. Tata letak dan fon menggunakan CDN Tailwind CSS dan Google Fonts, sehingga penyempurnaan visual tersebut memerlukan koneksi internet. HTML tetap dapat dibuka tanpa koneksi, dengan gaya yang lebih sederhana jika CDN tidak tersedia.

## Struktur

- `index.html` — portofolio utama yang responsif.
- `prototypes/index.html` — arsip dan pintu masuk konsep desain alternatif.
- `prototypes/` — konsep halaman mandiri.
- `assets/previews/` — gambar pratinjau arsip.
- `docs/design-system.md` — catatan sistem desain yang digunakan konsep.
# boundless
