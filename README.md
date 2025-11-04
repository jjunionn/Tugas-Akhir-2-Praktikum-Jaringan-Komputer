# Tugas-Akhir-2-Praktikum-Jaringan-Komputer

1. Sebelum Konfigurasi
   <img width="603" height="588" alt="ping sebelum konfigurasi" src="https://github.com/user-attachments/assets/96536b6f-c2c3-4fcb-bf58-ab473938cc0e" />
   proses ping ke alamat IP tujuan mengalami “request timed out” karena switch dan router belum dikonfigurasi. Dalam kondisi awal, perangkat jaringan seperti router belum memiliki informasi routing yang jelas untuk meneruskan paket data antar jaringan, sementara switch mungkin belum memiliki VLAN atau port yang diaktifkan dengan benar. Selain itu, PC belum memiliki gateway yang dapat mengarahkan trafik keluar dari subnetnya. Tanpa konfigurasi dasar seperti pemberian IP router, pengaktifan interface, pengaturan routing, serta penyambungan port switch yang benar, perangkat tidak mampu saling mengenali atau meneruskan paket ICMP (ping) ke jaringan lain. Akibatnya, komunikasi tidak dapat dilakukan dan ping akan gagal hingga konfigurasi pada router maupun switch selesai dilakukan.

2. Setelah Konfigurasi
   <img width="461" height="607" alt="ping setelah konfigurasi" src="https://github.com/user-attachments/assets/b02eebc1-a666-4652-9248-2f47c034ef8d" />
   proses ping sudah berhasil setelah konfigurasi dilakukan pada perangkat jaringan yang terlibat. Hal ini terjadi karena router, switch, dan PC telah diberikan parameter jaringan yang benar, seperti alamat IP, gateway, aktivasi interface, serta pengaturan routing sehingga perangkat dapat saling mengenali dan meneruskan paket data dengan benar. Setelah konfigurasi diterapkan, tabel routing pada router mulai berisi informasi jaringan tujuan, sementara switch dapat mempelajari MAC address melalui forwarding, memungkinkan pengiriman paket ICMP tanpa hambatan. Selain itu, koneksi fisik antar perangkat juga sudah aktif dengan status interface yang “up”, sehingga jalur komunikasi terbentuk. Akibatnya, paket ping dapat mencapai alamat tujuan dan menghasilkan balasan (reply) yang menunjukkan bahwa jaringan telah berfungsi secara normal.

**LINK YOUTUBE**
https://www.youtube.com/watch?v=ctAFXR2cmq4
