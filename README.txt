FIXED HAPPY CRUSH DAY

Penyebab error pada file sebelumnya:
index.html memiliki href="Utama.html", tetapi Utama.html belum ikut dibuat.

Struktur yang benar:
HAPPY_CRUSH_DAY/
├── index.html
├── Utama.html
├── ending.html
├── style.css
└── images/
    ├── confession.jpg
    └── ending.jpg

Cara menjalankan:
1. Extract ZIP.
2. Buka folder di VS Code.
3. Buka index.html.
4. Klik tombol panah -> Utama.html akan terbuka.
5. Klik Mau -> ending.html.

CSS berada di file style.css dan dipanggil dari setiap HTML dengan:
<link rel="stylesheet" href="style.css">
