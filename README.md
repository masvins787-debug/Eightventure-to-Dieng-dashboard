# Dashboard Simulasi Anggaran Liburan ke Dieng

Dashboard satu halaman untuk menghitung dan memantau patungan liburan ke Dieng.
Dibuat dengan Tailwind CSS, Alpine.js, Chart.js, dan Lucide Icons (semua lewat CDN, tanpa proses build).

## Fitur
- Rincian biaya per kategori (tambah, edit, hapus, ganti nama kategori)
- Total anggaran, biaya per orang, dan dana terkumpul (bisa diatur manual)
- Pembayaran peserta: DP/cicilan, status Lunas/Sebagian/Belum, pengingat WhatsApp
- Destinasi wisata dengan foto dan harga tiket
- Rencana perjalanan per hari
- Grafik donat proporsi pengeluaran (warna bisa diganti)
- Hitung mundur keberangkatan (tanggal diketik manual)
- Foto latar dan deskripsi hero bisa diubah
- Cetak PDF dan bagikan ke WhatsApp
- Data tersimpan otomatis di browser (localStorage)

## Menjalankan
Buka `index.html` di browser (butuh koneksi internet untuk memuat library).

## Publikasi dengan GitHub Pages
1. Upload `index.html` dan `README.md` ke repository GitHub.
2. Buka **Settings > Pages**.
3. Pada **Source** pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1-2 menit. Situs tersedia di `https://USERNAME.github.io/NAMA-REPO/`.

## Catatan
Data tersimpan di browser masing-masing pengunjung, jadi tidak dibagikan antar perangkat.
