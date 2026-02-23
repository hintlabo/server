# Frequently Asked Questions

## Kenapa $aplikasi tidak bisa diakses?

Kita wajib tahu akar masalahnya:
- Apakah VPN-nya mati? Jika iya, maka jalankan VPN-nya.
- Apakah proses $aplikasinya mati? Jika iya, jalankan aplikasinya.
- Apakah Nginx-nya mati? Jika iya, maka jalankan Nginxnya.

## Tidak bisa membuka $domain

Pertama, kita wajib ping alamat IP, misal `ping 8.8.8.8`. Kalau bisa,
maka kemungkinan masalah ada di DNS yang berada di `/etc/resolv.conf`.

Kalau tidak bisa ping, maka ada masalah di jaringan internetnya.
