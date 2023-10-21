# Windows Path

Sebelumnya kalau belum membaca [`README.md`](https://github.com/Cyber-STMIK-Amikom-Surakarta/materi-path/blob/main/README.md) tolong dibaca terlebih dahulu karena itu merupakan pembukaan.

## Contoh

Jadi sebelum kita memulai ini ada beberapa screenshot struktur folder dan file di File Explorer

![](./images/windows/belajar-path-root-1.png)

Posisi kita di drive `F:\` di folder `belajar-path` jadi jika diketikan menjadi path akan menjadi `F:\belajar-path`.

Selalu perhatikan path yang ditunjukan oleh `File Explorer`

![](./images/windows/belajar-path-root-1-highlighted.png)

Mari kita lihat folder data

![](./images/windows/data-path.png)

okay, mari kita liat folder koding yang tadi

![](./images/windows/koding-path.png)

huuu, ada folder lagi, mari kita cek

![](./images/windows/js-path.png)

hohoho, ada lagi

![](./images/windows/assets-path.png)

### Absolute Path

Okay, setelah melihat semua screenshot itu, kita bisa menuliskan hirarki agar enak dilihat

- `F:\`

    - belajar-path (`F:\belajar-path`)

        - data (`F:\belajar-path\data`)
        
            - tugas-kampus.odt (`F:\belajar-path\data\tugas-kampus.odt`)

        - koding (`F:\belajar-path\koding`)

            - catatan.txt (`F:\belajar-path\koding\catatan.txt`)

            - js (`F:\belajar-path\koding\js`)

                - index.html (`F:\belajar-path\koding\js\index.html`)

                - assets (`F:\belajar-path\koding\js\assets`)

                    - index.js (`F:\belajar-path\koding\js\assets\index.js`)
                    - style.css (`F:\belajar-path\koding\js\assets\style.css`)

Okay sangat menarik, apakah bentuk seperti ini membuat kepala anda sakit, kalau iya berarti kita sama, berikut yang berbentuk list

- `F:\`
- `F:\belajar-path`
- `F:\belajar-path\data`
- `F:\belajar-path\data\tugas-kampus.odt`
- `F:\belajar-path\koding`
- `F:\belajar-path\koding\catatan.txt`
- `F:\belajar-path\koding\js`
- `F:\belajar-path\koding\js\index.html`
- `F:\belajar-path\koding\js\assets`
- `F:\belajar-path\koding\js\assets\index.js`
- `F:\belajar-path\koding\js\assets\style.css`

### Relative Path

Nanti dulu yak

## Note : 

Sekian, kalau ada permasalahan atau pertanyaan bisa buka [issue](https://github.com/Cyber-STMIK-Amikom-Surakarta/materi-path/issues)
