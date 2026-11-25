# progres-harian

## Pengingat paket mini game mingguan
Halaman Hari ini menampilkan kartu "Paket mini game mingguan" bila ada app yang paketnya terlambat (minggu ini belum ada) atau perlu disiapkan (Jumat–Minggu, minggu depan belum ada). Data dibaca dari kunci `paketMingguan:nalar-harian`, `paketMingguan:latihan-kuantitatif`, `paketMingguan:latihan-ppu-pbm`, dan `paketMingguan:fundamental-math` yang ditulis tiap app (`{"app","nama","minggu":["YYYY-MM-DD" hari Senin, ...],"diperbarui"}`). App yang belum pernah dibuka setelah pembaruan belum punya data, jadi belum ikut tampil.
