# Universal Web App Launcher

Launcher universal untuk Windows yang menjalankan proyek web (`HTML`/`CSS`/`JS`) sebagai **Aplikasi Desktop**, **Preview HP (Mobile)**, atau melalui browser biasa menggunakan server HTTP lokal bawaan.

## Fitur Utama

- **Pilih atau Drag & Drop Folder Proyek**: Deteksi otomatis `index.html` maupun file `.html` lain di dalam proyek web Anda.
- **Server HTTP Lokal Bawaan**: Melayani file statis (`HTML`, `CSS`, `JS`, `JSON`, gambar, font, audio, video, dan `PDF`) tanpa perlu konfigurasi server manual.
- **Multi-Mode Tampilan**:
  - **Desktop App** (`1280x820`)
  - **Preview Mobile / HP** (`406x860`)
  - **Browser Default**
- **Akses Wi-Fi / LAN**: Tampilkan alamat IP lokal agar proyek web bisa langsung dibuka dan diuji lewat HP di jaringan Wi-Fi yang sama.
- **Riwayat Proyek**: Menyimpan daftar folder proyek terakhir agar cepat dibuka kembali.

## Persyaratan Sistem

- Windows 10 / 11
- .NET Framework (sudah tersedia bawaan di Windows)
- Browser berbasis Chromium (Google Chrome, Microsoft Edge, Brave, dll.) untuk mode aplikasi desktop & mobile preview

## Cara Menggunakan

1. Unduh file `UniversalWebAppLauncher.exe` dari repositori ini.
2. Jalankan `UniversalWebAppLauncher.exe`.
3. Pilih atau seret (*drag & drop*) folder proyek web Anda yang berisi file `index.html`.
4. Klik mode tampilan yang diinginkan (**Desktop**, **Mobile**, atau **Browser**), atau aktifkan opsi **Wi-Fi / LAN** untuk membuka preview dari HP.

## Catatan

- Jika Windows SmartScreen menampilkan peringatan saat pertama kali dijalankan (karena file belum ditandatangani digital), klik **More info** -> **Run anyway**.
