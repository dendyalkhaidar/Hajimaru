# はじめる – Belajar Jepang N5–N3

Aplikasi belajar bahasa Jepang (PWA). Semua data sudah ada di dalam `index.html`, jadi tidak perlu server.

## Cara pasang di GitHub Pages
1. Buka github.com, buat repositori baru (misalnya `hajimeru`), pilih Public.
2. Klik **Add file → Upload files**, lalu unggah SEMUA isi folder ini (termasuk `.nojekyll` jika tampil) dan commit.
3. Buka **Settings → Pages**. Pada *Build and deployment*, pilih **Deploy from a branch**, branch **main**, folder **/ (root)**, lalu Save.
4. Tunggu 1–2 menit. Alamatnya: `https://USERNAME.github.io/hajimeru/`.
5. Buka alamat itu di Chrome Android, ketuk menu ⋮ → **Tambahkan ke layar utama** / **Instal aplikasi**.

## Memperbarui
Unggah ulang `index.html` (dan `sw.js` jika ada versi baru) ke repositori yang sama. Ubah nama cache di `sw.js` (`hajimeru-v3`) supaya HP memuat versi terbaru.

## Catatan
- Progres belajar tersimpan di browser tiap perangkat. Gunakan Progres → Salin backup untuk memindahkan data.
- Data kosakata: open-anki-jlpt-decks (MIT) dicocokkan dengan JMdict dan KANJIDIC2 © EDRDG (https://www.edrdg.org/edrdg/license.html). Arti Indonesia otomatis berasal dari WordNet Bahasa dan bisa keliru.
- Daftar JLPT tidak resmi.
