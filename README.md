# Evaluasi Tengah Semester 2026

**Nama:** Nabil Irawan

**NRP:** 5025241231

**Kelas:** PBKK C

## 1. Jelaskan perbedaan aplikasi desktop dengan aplikasi lain? Mengapa masih dibutuhkan?

Aplikasi desktop adalah perangkat lunak yang dipasang dan dijalankan secara langsung pada sistem operasi komputer, seperti Windows, macOS, atau Linux. SIHIFA termasuk aplikasi desktop karena dibuat menggunakan WPF dan .NET untuk dijalankan pada sistem operasi Windows. Berbeda dengan aplikasi web yang diakses melalui browser dan umumnya bergantung pada koneksi internet serta server, aplikasi desktop dapat menjalankan proses dan menyimpan data secara langsung pada komputer pengguna. Sementara itu, aplikasi mobile dirancang khusus untuk ponsel atau tablet sehingga antarmukanya disesuaikan dengan layar kecil, penggunaan layar sentuh, serta keterbatasan sumber daya perangkat.

Aplikasi desktop masih dibutuhkan karena dapat tetap digunakan saat koneksi internet tidak tersedia. Penyimpanan lokal juga memberikan kendali dan privasi yang lebih baik kepada pengguna karena data tidak harus dikirim ke server pihak ketiga. Selain itu, aplikasi desktop sesuai untuk aktivitas yang dilakukan dalam waktu lama pada layar besar, membutuhkan navigasi yang lengkap, serta melibatkan data dalam jumlah besar. Performa yang stabil dan akses langsung ke fasilitas komputer membuat aplikasi desktop tetap relevan meskipun aplikasi web dan mobile semakin banyak digunakan.

Pada SIHIFA, bentuk aplikasi desktop dipilih agar pengguna dapat mengelola koleksi media dengan cepat dan memakai seluruh fungsi utama secara offline. Data disimpan dalam basis data SQLite pada perangkat pengguna sehingga koleksi pribadi tetap berada di bawah kendali pengguna. Teknologi WPF juga memungkinkan SIHIFA menyediakan antarmuka yang kaya dan responsif, seperti navigasi sidebar, daftar koleksi, dashboard statistik, pencarian instan, serta pilihan tema gelap dan terang.

## 2. Tuliskan problem yang akan diselesaikan oleh aplikasi yang kamu buat? Definisikan fitur aplikasi yang merupakan solusi dari problem tersebut!

SIHIFA atau Sistem Informasi Hiburan dan Media Favorit adalah aplikasi desktop untuk mencatat, mengatur, mencari, dan memantau koleksi media pribadi. Jenis media yang dapat dikelola meliputi anime, film, musik, buku, dan materi pembelajaran. Aplikasi ini dibuat untuk mengatasi masalah pengelolaan informasi media yang biasanya tersebar di berbagai platform.

Masalah utama yang ingin diselesaikan adalah fragmentasi data koleksi. Pengguna sering menyimpan daftar anime pada satu platform, daftar film pada platform lain, musik pada layanan streaming, buku pada aplikasi pencatat buku, dan materi pembelajaran pada aplikasi catatan. Penyimpanan yang terpisah tersebut membuat pengguna kesulitan melihat dan mengelola seluruh koleksinya secara terpadu. Sebagai solusinya, SIHIFA menyediakan fitur manajemen media terintegrasi agar semua jenis media dapat disimpan dalam satu aplikasi dan satu basis data.

Masalah berikutnya adalah kesulitan dalam menambah, memperbarui, dan mengatur informasi koleksi. SIHIFA mengatasinya melalui fitur CRUD yang memungkinkan pengguna menambah, melihat, mengubah, dan menghapus data media. Formulir dilengkapi validasi agar data penting, seperti judul dan rating, dapat dimasukkan dengan benar. Pengguna juga dapat memberikan genre, gambar sampul, serta catatan pribadi pada setiap media.

Pengguna juga dapat kesulitan mengingat progres setiap media, misalnya media yang ingin dinikmati, sedang dinikmati, telah selesai, ditunda, atau ditinggalkan. Untuk menyelesaikan masalah tersebut, SIHIFA menyediakan fitur status media. Dengan fitur ini, pengguna dapat mengetahui progres koleksinya dan memperbarui status sesuai perkembangan aktivitasnya. Fitur rating dan catatan juga tersedia agar pengguna dapat menyimpan penilaian serta kesan pribadi terhadap setiap media.

Ketika jumlah koleksi semakin banyak, pengguna akan kesulitan menemukan item tertentu secara manual. Oleh karena itu, SIHIFA menyediakan pencarian dan penyaringan instan. Pengguna dapat mencari media berdasarkan judul serta menyaring koleksi berdasarkan jenis, genre, atau status. Daftar media dirancang agar tetap responsif meskipun berisi banyak data sehingga pengguna tidak perlu memeriksa seluruh koleksi satu per satu.

Ketergantungan terhadap internet dan layanan pihak ketiga menjadi masalah lain yang ingin diselesaikan. Platform daring dapat mengubah kebijakan, membatasi fitur, menghentikan layanan, atau mengenakan biaya berlangganan. SIHIFA menggunakan basis data SQLite yang tersimpan secara lokal sehingga seluruh fitur utama tetap dapat digunakan tanpa koneksi internet. Penyimpanan lokal juga meningkatkan privasi karena informasi mengenai preferensi media tidak harus dikirim kepada pihak lain.
