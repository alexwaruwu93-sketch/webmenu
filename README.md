# De Boer Restaurant — Digital Menu

Website digital menu untuk De Boer Restaurant, Hotel Grand Inna Medan. Proyek tugas kuliah.

## Struktur Proyek

```
.
├── index.html          # Markup utama halaman
├── style.css           # Seluruh styling (desain, layout, responsive, animasi)
├── script.js           # Data menu (99 item) + logic search, filter, popup
├── images/
│   └── menu/            # Foto asli menu (50 file .jpg)
└── README.md
```

## Cara Menjalankan

Tidak perlu instalasi apa pun. Cukup:

1. Clone atau download repo ini.
2. Buka file `index.html` langsung di browser.

Atau jalankan lokal dengan live server (opsional, untuk auto-reload saat development):

```bash
# Python
python3 -m http.server 8000

# atau Node (jika punya http-server terpasang)
npx http-server
```

Lalu buka `http://localhost:8000`.

## Deploy ke GitHub Pages

1. Push seluruh isi folder ini ke repository GitHub.
2. Masuk ke **Settings → Pages**.
3. Pilih branch `main` dan folder `/ (root)`.
4. Simpan — situs akan tersedia di `https://<username>.github.io/<nama-repo>/`.

## Fitur

- Pencarian menu berdasarkan nama, kategori, atau deskripsi
- Filter berdasarkan kategori (Signature, Main Course, Coffee, dll.)
- Popup detail menu saat kartu diklik
- Badge (Best Seller, Chef Recommendation, New, Spicy, Vegetarian)
- Responsive untuk desktop, tablet, dan mobile
- Tombol kontak WhatsApp mengambang

## Catatan

- 50 dari 99 menu menggunakan foto asli restoran (folder `images/menu/`); sisanya masih menggunakan foto stok sementara karena belum tersedia foto asli untuk item tersebut.
- Data menu (nama, harga, deskripsi, kategori) berada di `script.js` pada variabel `menuData` — mudah ditambah/diedit di satu tempat.
