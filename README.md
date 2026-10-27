# CV Bima Putra - Demo v2 untuk GitHub Pages

Salinan demo yang sama dengan https://cv-bima-putra.abaodesu.chatgpt.site, termasuk semua halaman publik, preview mobile, CMS demo, filter proyek, galeri, formulir simulasi, dan Floating WhatsApp.

Tidak memerlukan npm, build, database, atau backend. Seluruh HTML/CSS/JS dan aset menggunakan path relatif, sehingga bisa dipublikasikan dalam subfolder repository GitHub Pages.

## Deploy

1. Ekstrak ZIP.
2. Buat repository GitHub baru (Public jika menggunakan GitHub Free).
3. Upload seluruh ISI hasil ekstrak ke root repository, termasuk folder `assets`. Pastikan `index.html` langsung berada di root. Jangan upload ZIP-nya.
4. Commit ke branch `main`.
5. Buka **Settings > Pages**.
6. Source: **Deploy from a branch**.
7. Branch: **main**, folder: **/(root)**, lalu **Save**.
8. Setelah deployment selesai, buka URL yang ditampilkan GitHub.

Panduan resmi: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Alur demo

- Navigasi publik menggunakan hash, misalnya `#/proyek`, sehingga refresh halaman detail tidak memerlukan server routing.
- Tombol Mobile membuka `mobile.html`.
- CMS demo tersedia melalui pemilih halaman di bawah. Login dapat memakai email berformat valid dan password sembarang.
- Edit proyek tersimpan hanya pada browser/origin tempat demo dibuka. Data edit lokal dari alamat demo sebelumnya tidak ikut berpindah ke GitHub Pages.
- Formulir dan WhatsApp tetap simulasi. Semua nama proyek, klien, legalitas, dan kontak adalah dummy.
- Logo dan foto sudah disertakan. Outfit dan Inter dimuat dari Google Fonts.

## Sumber foto ilustrasi

- https://images.unsplash.com/photo-1541888946425-d81bb19240f5
- https://images.unsplash.com/photo-1486406146926-c627a92ad1ab
- https://images.unsplash.com/photo-1504307651254-35680f356dfd
- https://images.unsplash.com/photo-1503387762-592deb58ef4e

Foto merupakan ilustrasi, bukan dokumentasi pekerjaan perusahaan.
