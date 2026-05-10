# Aplikasi Absensi Berbasis Web Mobile

Aplikasi absensi mandiri berbasis web yang dirancang khusus untuk perangkat genggam (HP) guna mempermudah pencatatan kehadiran anggota organisasi. Aplikasi ini berjalan langsung di browser tanpa memerlukan instalasi aplikasi pihak ketiga.

## ✨ Fitur Utama

* **Pemindai Barcode Offline:** Memanfaatkan kamera HP dan pemindai bawaan browser untuk memindai barcode secara instan, bahkan tanpa memerlukan koneksi internet untuk proses pemindaiannya.
* **Deteksi Nama Otomatis:** Sistem langsung mengenali dan menampilkan nama anggota secara otomatis berdasarkan data dari barcode yang dipindai.
* **Penyimpanan Lokal (Local Storage):** Data kehadiran direkam secara aman di penyimpanan lokal browser perangkat, memastikan data aman selama sesi absensi berlangsung.
* **Filter Belum Hadir:** Terdapat fitur khusus untuk melakukan pengecekan silang dan menampilkan daftar anggota yang belum melakukan absensi.
* **Ekspor Laporan CSV:** Rekap data kehadiran dapat diunduh dengan mudah ke dalam format `.csv` untuk keperluan pelaporan atau rekapitulasi data lanjutan.

## 🛠️ Teknologi yang Digunakan

* **HTML**
* **JavaScript** (Vanilla)
* **Web APIs** (Untuk akses pemindai barcode bawaan browser dan *Local Storage*)

## 🚀 Cara Penggunaan

1. Buka file utama aplikasi (misalnya `index.html`) melalui browser di HP.
2. Berikan izin akses kamera saat browser memunculkan *prompt* permintaan izin.
3. Arahkan kamera ke barcode milik anggota. Aplikasi akan otomatis mendeteksi nama dan menyimpan data kehadirannya.
4. Gunakan menu pengecekan untuk melihat siapa saja anggota yang belum hadir pada hari tersebut.
5. Setelah acara/kegiatan selesai, klik tombol **Ekspor CSV** untuk mengunduh rekap absensi ke penyimpanan HP kamu.

## 📌 Catatan Penting

Karena aplikasi ini sangat bergantung pada *Local Storage* browser untuk menyimpan data sementara, sangat disarankan untuk **tidak menggunakan mode Incognito/Private** di browser HP saat melakukan absensi. Hal ini untuk mencegah data terhapus sebelum sempat diekspor ke CSV.
