# TwidyPet

Website virtual pet client-side bertema Twidy Shop. Dibuat sebagai static website responsif tanpa framework dan tanpa backend.

## Fitur

- Dashboard responsif untuk desktop dan mobile.
- Karakter maskot Twidy dengan ilustrasi SVG inline.
- Merawat pet: makan, bermain, mandi, dan tidur.
- Status kebutuhan pet, level, XP, koin, dan diamond.
- Pet Shop, inventori, aksesori, misi harian, dan mini-game Catch the Fish.
- Progres otomatis tersimpan di `localStorage`.
- Ekspor dan reset progres dari menu Pengaturan.
- Tidak membutuhkan API key, server, atau database.

## Deploy ke Vercel

1. Impor repository `twidyshop/twidypet` di Vercel.
2. Framework preset: **Other**.
3. Build command: kosongkan / **Override** nonaktif.
4. Output directory: `.`
5. Deploy. File `index.html` langsung menjadi halaman utama.

Bisa juga dipublikasikan sebagai static site di GitHub Pages atau layanan hosting statis lain.

## Catatan

- Seluruh gameplay dan penyimpanan berjalan di browser pengguna.
- Data tidak tersinkron antar perangkat/browser. Gunakan **Pengaturan → Ekspor progres** untuk mengunduh salinan data.
- Menghapus data situs/browser dapat menghapus progres lokal.
- Font eksternal menggunakan Google Fonts; jika tidak tersedia, website memakai fallback sans-serif.
- Koin dan diamond hanya mata uang virtual dalam game, tidak ada pembayaran sungguhan.
