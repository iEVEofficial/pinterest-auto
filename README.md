# pinterest-auto

## Anda memerlukan Access Token dan Board ID dari Pinterest.
1. Buat Aplikasi Pinterest: Kunjungi Pinterest for Developers dan buat aplikasi baru.
2. Hasilkan Access Token: Di dalam pengaturan aplikasi Anda, pergi ke bagian otentikasi dan hasilkan Access Token (OAuth 2.0). Pastikan Anda memberikan izin (scope) pins:read dan pins:write.
3. Dapatkan Board ID: Buka board Pinterest yang ingin Anda gunakan untuk auto-post. URL-nya akan terlihat seperti https://www.pinterest.com/username/board-name/. Bagian terakhir (board-name) biasanya adalah ID Anda. Jika tidak berhasil, Anda bisa menggunakan API untuk mendapatkan daftar board dan ID-nya.

## Tambahkan Kredensial ke GitHub Secrets
1. Simpan kredensial Anda dengan aman menggunakan GitHub Secrets.
2. Buka repositori Anda di GitHub, lalu pergi ke Settings > Secrets and variables > Actions.
3. Klik New repository secret.

Buat dua secret baru:
  PINTEREST_ACCESS_TOKEN: Masukkan Access Token yang Anda dapatkan dari Pinterest.
  PINTEREST_BOARD_ID: Masukkan ID board Pinterest Anda.
