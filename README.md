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

## Penggunaan

1. Siapkan file proxy.txt di direktori yang sama, berisi daftar proxy dengan format:

192.168.1.1:8080
123.456.789.0:3128
...

2. Jalankan script:

python run.py
Clone repository:
   ```bash
pkg update && pkg upgrade -y
pkg install python
pkg install git
pip install requests colorama pyfiglet
git clone https://github.com/andirozaS-SKD/proxy-scanner.git
cd proxy-scanner
python run.py
```

3. Hasil akan tersimpan ke:

live_proxies.txt – Proxy yang berhasil terhubung

dead_proxies.txt – Proxy yang gagal


## Output Contoh

[LIVE] 123.123.123.123:8080 -> IP: 123.123.123.123

[DEAD] 111.111.111.111:8000

=== Proxy Check Completed ===

Total Proxies : 100

Live Proxies  : 45

Dead Proxies  : 55

## Tautan Terkait

- [Tutorial Video YouTube Saya](https://www.youtube.com/watch?v=contohLink)
- [Facebook Video YouTube Saya](https://www.youtube.com/watch?v=contohLink)
- [Repository GitHub Saya](https://github.com/andirozaS-SKD/Proxy-scnner)
