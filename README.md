# 🏥 Sistem Informasi Data Pasien - RS Cahaya Ilahi

Program ini adalah aplikasi manajemen data pasien berbasis Python yang memungkinkan Anda untuk mencatat, mengelola, dan mencari informasi pasien, termasuk prediksi kunjungan berikutnya secara otomatis.

## ✨ Fitur Utama

- ✅ Menambahkan data pasien
- 🔍 Mencari pasien berdasarkan **ID** atau **nama**
- 📋 Menampilkan seluruh data pasien
- 📝 Mengedit data pasien
- ❌ Menghapus data pasien
- 🧠 Prediksi kunjungan pasien berikutnya secara otomatis (+14 hari dari kunjungan terakhir)
- 💊 Menyimpan riwayat penyakit dan nama dokter
- 📁 Penyimpanan data otomatis ke file JSON (`data_pasien1.json`)

## 🧱 Struktur Data Pasien

Setiap pasien memiliki informasi sebagai berikut:

- `id_pasien` (string)
- `nama` (string)
- `nomer_HP` (string)
- `tempat_lahir` (string)
- `tanggal_lahir` (format: dd-mm-yyyy)
- `jadwal_kunjungan_terakhir` (format: dd-mm-yyyy)
- `riwayat_penyakit` (list)
- `dokter` (string)
- `prediksi_kunjungan_berikutnya` (otomatis dihitung 14 hari setelah kunjungan terakhir)
