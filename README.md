# Exam SMKN 1 Sragi

Proyek Android sederhana untuk latihan ujian sekolah.

## Akun demo
- Admin: `admin` / `admin123`
- Siswa: username bebas / `siswa123`

## Fitur
- Login demo admin dan siswa
- Soal pilihan ganda
- Perhitungan nilai otomatis
- Admin dapat menambah dan menghapus soal
- Soal tersimpan lokal di perangkat

## Catatan penting
Ini adalah prototipe/demo belajar. Login dan data soal belum menggunakan server; akun siswa menerima username apa pun dengan kata sandi demo. Jangan gunakan untuk ujian resmi atau menyimpan data pribadi tanpa backend dan keamanan yang benar.

## Build APK
Workflow GitHub Actions ada di `.github/workflows/build.yml`. Setelah seluruh file diunggah ke repositori pada branch `main`, buka tab **Actions**, pilih workflow **Build Exam SMKN 1 Sragi APK**, lalu unduh artifact `Exam-SMKN1-SRAGI-debug-apk` ketika proses berhasil.
