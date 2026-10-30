# Website Profil SMK Alexandria Islamic School

Website profil sekolah berbasis **HTML, CSS, dan JavaScript** (website statis). Website menampilkan profil sekolah, jurusan, prestasi, ekstrakurikuler, galeri kegiatan, dan artikel.

Project ini dibuat sebagai tugas akhir perkuliahan Program Studi Teknologi Informasi, Universitas Bina Sarana Informatika (Depok).


## Demo

Buka langsung di browser, tanpa download:

**https://github.com/evnydprtma12/website-sekolah**


## Halaman

| Halaman | File | Keterangan |
| --- | --- | --- |
| Beranda | `index.html` | Slider banner, nilai-nilai sekolah (*Our Values*), sambutan, daftar jurusan, prestasi, ekstrakurikuler, dan artikel terbaru |
| Galeri | `galeri.html` | Daftar album kegiatan sekolah |
| Galeri Pramuka | `perGaleri.html` | Detail album kegiatan Pramuka |
| Galeri Paskibra | `paskibra.html` | Detail album kegiatan Paskibra |
| Artikel | `artikel.html` | Daftar artikel dan postingan terbaru |
| Detail Artikel | `perArtikel.html`, `perArtikel2.html`, `perArtikel3.html` | Isi lengkap masing-masing artikel |
| Ekstrakurikuler | `ekstrakulikuler.html` | Daftar kegiatan ekstrakurikuler |
| Detail Ekstrakurikuler | `perEkstrakulikuler.html` | Detail ekstrakurikuler Basket |
| Kontak | `kontak.html` | Formulir "Hubungi Kami" dan peta lokasi |
| Pendaftaran | `pendaftaran.html` | Formulir pendaftaran siswa |
| Login | `login.html` | Tampilan form login dan daftar akun |

**Jurusan yang ditampilkan:** Rekayasa Perangkat Lunak, Agribisnis Ternak Unggas, Agribisnis Pengolahan Hasil Pangan, Agribisnis Perikanan, Akuntansi Keuangan dan Lembaga, serta Teknik Kendaraan Ringan.

## Teknologi

| Komponen | Keterangan |
| --- | --- |
| Markup | HTML5 |
| Styling | CSS3 / SCSS, [Bootstrap 4.6](https://getbootstrap.com/docs/4.6/) |
| Skrip | JavaScript, jQuery 3.5 |
| Slider | [LightSlider](https://sachinchoolur.github.io/lightslider/) |
| Ikon | Font Awesome 5.15 |
| Font | Google Fonts (Poppins, Viga, PT Serif) |
| Peta | Google Maps Embed |

Seluruh library dimuat lewat **CDN**, sehingga halaman perlu koneksi internet agar tampil sempurna.

## Cara Menjalankan

### Tanpa instalasi

1. Unduh atau clone repository ini.
2. Buka file `index.html` dengan browser (klik dua kali).

```bash
git clone https://github.com/evnydprtma12/website-sekolah.git
cd website-sekolah
```

### Lewat server lokal (opsional)

Jika menggunakan VS Code, pasang ekstensi **Live Server**, klik kanan `index.html`, lalu pilih **Open with Live Server**. Alternatif lain, dengan Python:

```bash
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Struktur Folder

```
├── index.html            # Halaman utama
├── galeri.html, perGaleri.html, paskibra.html
├── artikel.html, perArtikel.html, perArtikel2.html, perArtikel3.html
├── ekstrakulikuler.html, perEkstrakulikuler.html
├── kontak.html, pendaftaran.html, login.html
├── css/
│   ├── style.scss        # Sumber styling (SCSS)
│   ├── style.css         # Hasil kompilasi
│   ├── style.css.map
│   └── login.css         # Styling halaman login
├── js/
│   ├── script.js         # Slider, navbar, dan tab login/daftar
│   └── login.js          # Animasi form login
├── images/               # Foto dan gambar website
└── img/
```

## Publikasi dengan GitHub Pages

1. Buka **Settings → Pages** pada repository.
2. Pada **Source**, pilih **Deploy from a branch**.
3. Pilih **Branch: `main`** dan folder **`/ (root)`**, lalu klik **Save**.
4. Tunggu beberapa menit, website tersedia di alamat yang tertera pada halaman Pages.

## Catatan

- Formulir **Login**, **Daftar**, **Hubungi Kami**, dan **Pendaftaran** hanya berupa tampilan (front-end) dan **belum mengirim atau menyimpan data**, karena tidak ada backend.
- Beberapa bagian artikel di beranda masih berisi teks sementara.
- Konten dan foto pada website ini digunakan untuk keperluan pembelajaran.

## Kontak

- **Nama:** [Evan Yudi Pratama]
- **Email:** [evanyudipratama12@gmail.com]