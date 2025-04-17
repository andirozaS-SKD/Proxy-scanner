# PROXY-s - Proxy Network Scanner

![Banner](https://img.shields.io/badge/version-1.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

**PROXY-s** adalah tool sederhana berbasis Python untuk memeriksa status hidup atau matinya proxy dari sebuah daftar. Tool ini menggunakan `ThreadPoolExecutor` untuk mempercepat proses pengecekan secara paralel.

## Fitur
- Pengecekan proxy HTTP/HTTPS secara paralel
- Output berwarna untuk membedakan proxy yang hidup dan mati
- Logging ke file (`proxy_checker.log`)
- Menyimpan hasil ke file: `live_proxies.txt` dan `dead_proxies.txt`
- Banner ASCII yang keren!

## Instalasi

1. Clone repository:
   ```bash
   git clone https://github.com/andirozaS-SKD/proxy-scanner.git
   cd proxy-scanner
