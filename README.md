# INFO Changelog - CBT-3GU-BAJAKAN🛑

![logoapkutama](https://github.com/user-attachments/assets/2249fa6f-0242-4aca-b56b-09881f370e4f)
## v1.0.0 - [Initial Release]
- Membuat aplikasi **CBT Bajakan** dengan fitur utama:
  - Login ke sistem CBT tanpa batasan sekolah.
  - Dukungan berbagai metode akses soal ujian.
  - Tampilan sederhana dan ringan.

## v1.1.0 - [Fitur Scan QR Code]
- Menambahkan fitur **Scan QR Code** dengan dua opsi:
  1. **Scan langsung** menggunakan kamera.
  2. **Input manual** dengan teks enkripsi.
- Menampilkan hasil decode dalam **WebView khusus**.

## v1.1.1 - [Bug Fix: WebView Crash]
- Memperbaiki **crash pada WebViewScanQRActivity** karena aktivitas tidak terdaftar di **AndroidManifest.xml**.
- Menambahkan pengecekan validitas URL sebelum ditampilkan di WebView.

## v1.2.0 - [UI & Navigasi WebView]
- Menambahkan tombol navigasi **(Undo, Forward, Refresh, Resize, Exit)** dalam WebView.
- Menambahkan indikator **baterai dan jam** dalam WebView.

## v1.2.1 - [Bug Fix: Force Close saat Scan QR]
- Memperbaiki **force close** saat hasil scan QR lebih dari satu kali.
- Memastikan URL yang di-decode dapat langsung dibuka di WebView **tanpa crash**.

## v1.3.0 - [COOMING SOON!]
- Optimasi performa aplikasi agar lebih ringan.
- Penyempurnaan UI dan UX untuk pengalaman pengguna yang lebih baik.
- Perbaikan minor lainnya sebelum rilis di GitHub.
