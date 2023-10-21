# Belajar Path

Apa itu `path`, path adalah suatu representasi lokasi suatu file atau folder dengan teks yang unik, bayangin saja seperti alamat file di file explorer, bentuknya mirip dengan hirarki pangkat yang dipisah dengan karakter khusus seperti `/` atau `\`. `path` ini dipakai dalam bahasa pemrograman dan bahasa markup (seperti HTML) jadi sangat bermanfaat untuk dipelajari dan dipahami maksud dari path berikut. Ada 2 jenis `path` antara lain : 

- Absolute Path
- Relative Path

## Absolute Path

Absolute path merupakan alamat komplit suatu file atau folder yang dimulai dengan `root`, `root` dalam konteks ini tergantung dengan sistem operasi misalnya : 

### Unix System

- `/home/user/documents/data.txt`
- `/opt/lampp/htdocs`
- `/etc/os-release`

### Windows System

- `C:\Users`
- `C:\Windows\System32`
- `C:\Users\Public\Documents`

## Relative Path

Relative path merupakan alamat yang relatif dengan posisi aplikasi atau terminal yang anda pakai. path ini dimulai dengan `./`, disini kita juga bisa menggunakan `../` untuk keluar dari folder.

### Unix System

Misalnya anda di posisi di `/home/user/documents`

- `./data.txt` -> `/home/user/documents/data.txt`
- `../downloads/file-download.txt` -> `/home/user/downloads/file-download.txt`
- `../../user-2/downloads/file-download.txt` -> `/home/user-2/downloads/file-download.txt`

### Windows System

Misalnya anda di posisi `C:\Users\Public\Documents`

- `.\document.txt` -> `C:\Users\Public\Documents\document.txt`
- `..\Downloads\download-file.txt` -> `C:\Users\Public\Downloads\download-file.txt`

## Note : 

Materi ini ada di [Github Cyber](https://github.com/Cyber-STMIK-Amikom-Surakarta/materi-path)

Nanti ada contoh (Unix (Terminal) dan Windows (Windows Explorer)) yang akan diberikan setelah ini

- [Windows](https://github.com/Cyber-STMIK-Amikom-Surakarta/materi-path/blob/main/Windows.md)
- Unix

Kalau ada masalah bisa membuka [issue](https://github.com/Cyber-STMIK-Amikom-Surakarta/materi-path/issues)
