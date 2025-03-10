# bebasit
bebasit adalah repo turunan bebasid yang berisikan aplikasi untuk keperluan penembusan deep packet inspection (DPI).

<b>Indonesia</b> | <a href="README.en.md">English</a>
## Daftar Aplikasi
Berikut ini adalah daftar aplikasi yang sudah diuji dalam kemampuan menembus DPI.
### Windows
- GoodbyeDPI.
- PowerTunell (JRE).
### Linux
- Green Tunnel (NodeJS + NPM).
- PowerTunnel (JRE).
- Zapret (saat ini masih dalam tahap ujicoba mengingat bahwa zapret tidak memasukkan DoH dalam tpws).
### Mac
- Green Tunnel (NodeJS + NPM).
- PowerTunnel (JRE).
## Catatan
### Windows
- Tidak semua versi Windows work, Windows 7 yang belum pernah update ada permasalahan, yaitu minta update KBxxxxxx.
### Linux dan MacOS
- Green Tunnel "hoki-hokian" dalam menembus DPI (bukan berarti Green Tunnel tidak dapat menembus bypass DPI).
### Tambahan
- Versi aplikasi dalam repo ini tidak menggunakan skema auto update ke versi terbaru dengan alasan bahwa mungkin ada fitur terbaru dari aplikasi yang memang tidak diperlukan.
### Mengapa dipisah antara bebasid dengan bebasit
- Memudahkan pengontrolan kesesuaian aplikasi.
- Jika aplikasi seperti GoodbyeDPI, Green Tunnel, PowerTunnel, dan Zapret diletakkan ke repo bebasid, akan terjadi pemborosan data. Seringkali orang menggunakan perintah `git clone` dalam mengunduh bebasid sehingga aplikasi yang semestinya dipasang di Mac ikut terunduh di Windows.
- Ada proyek baru.
- Agar bebasid lebih terlihat formal.
## bebasit Dependencies
- [GoodbyeDPI](https://github.com/ValdikSS/GoodbyeDPI)
- [Green Tunnel](https://github.com/SadeghHayeri/GreenTunnel/)
- [PowerTunnel](https://github.com/krlvm/PowerTunnel)
- [Zapret](https://github.com/bol-van/zapret)
## Lisensi

bebasit dilisensikan di bawah [Lisensi MIT](https://github.com/bebasid/bebasit/blob/master/LICENSE).

---

# Syarat dan Ketentuan

Dengan menggunakan layanan ini, anda setuju mematuhi peraturan yang kami buat dan menerima segala akibat yang ditimbulkan. Untuk selengkapnya, lihat [ATURAN](https://github.com/bebasid/bebasit/blob/master/dev/readme/RULES.md) nya.
