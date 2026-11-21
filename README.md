### Halo, saya en1gma 👋

Saya membangun perangkat lunak desktop yang bekerja tanpa internet untuk lembaga pendidikan,
terutama pondok pesantren.

**Proyek utama: [si administrator](https://github.com/en1gma-workspace/si-administrator-rilis)**
Aplikasi administrasi pondok pesantren untuk Windows: data santri, akademik, keuangan,
Madrasah Diniyyah dengan rapor berbahasa Arab, hingga Pondok Ramadhan. Satu program,
data tersimpan di komputer lembaga sendiri.

- **Inti:** Go, SQLite, antarmuka web tertanam di WebView2
- **Keamanan:** lisensi Ed25519 terikat perangkat, update offline bertanda tangan digital
- **Infrastruktur:** Cloudflare Workers + D1 untuk aktivasi lisensi
- **Distribusi:** installer tanpa hak administrator, transaksional, dengan pemeriksaan SHA-256

[Unduh rilis terbaru](https://github.com/en1gma-workspace/si-administrator-rilis/releases/latest)
