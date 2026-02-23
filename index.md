## proxmox

### Login

1. Pastikan server hidup dan perangkat terhubung pada WiFi Lab_HINT
2. Akses [http://192.168.1.111:8006](http://192.168.1.111:8006) melalui browser.
3. Login dengan username dan password yang tersedia.

### Membuat VM Baru
1. Buka dashboard Proxmox
2. Klik tombol "Create VM"
3. Pada menu General, isi kolom Name sebagai _hostname_ atau nama komputer.
4. Pada menu OS, isi kolom operasi sistem, misal Ubuntu GNU/Linux.
5. Pada menu Disk, isi kolom disk, misal 32 GB
6. Pada menu Memory, isi kolom memory, misal 20248 MiB (setara 2 GB)
7. Setelah itu, ulas kembali hasil konfigurasi Anda. Jika cukup, maka klik "Finish"

### Mengakses VM
1. Pada dashboard, anda akan melihat VM baru (ditandai dengan uptime paling muda)
2. Pada menu "Server View", klik nama VM, kemudian klik "Console".
3. Pada tahap ini, ada dua kemungkinan:
   - Proses instalasi sistem operasi. Jika seperti itu, maka anda wajib membaca manualnya
   - Proses penggunaan. Jika seperti itu, maka anda sudah selesai.
  
## OpenVPN

### Menjalankan VPN

1. Login dalam akun root menggunakan perintah `su`
2. Jalankan perintah `openvpn3 session-start --config /etc/openvpn3/HINT-IoT.ovpn`
3. Isi dengan kredensial yang telah diberikan
4. Apabila berhasil, anda akan melihat "Connected to $IPV4_ADDRESS".
