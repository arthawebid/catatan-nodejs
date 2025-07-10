# Instalasi NodeJS pada AlmaLinux
Untuk menginstal Node.js di AlmaLinux, dapat menggunakan manajer paket DNF atau NVM (Node Version Manager). Berikut adalah langkah-langkah umum: 
## Instalasi Instruksi
1. Perbarui sistem:
``bash
sudo dnf update -y
``bash
2. Aktifkan modul Node.js:
dengan versi tertentu
``bash
sudo dnf module enable nodejs:<versi_node> -y
``bash
