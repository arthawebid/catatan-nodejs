# Instalasi NodeJS pada AlmaLinux
Untuk menginstal Node.js di AlmaLinux, dapat menggunakan manajer paket DNF. Berikut adalah langkah-langkah umum: 
## Instalasi Instruksi
1. Perbarui sistem:
```bash
sudo dnf update -y
```
```bash
dnf install epel-release
```
2. Modul Nodejs
```bash
dnf module list nodejs
```
3. Aktifkan modul Node.js:
dengan versi tertentu
```bash
sudo dnf module enable nodejs:<versi_node> -y
```
dengan versi terbaru
```bash
sudo dnf install nodejs -y
```
## Memeriksa Versi node dan npm     
```bash
node -v
```

```bash
npm -v
```