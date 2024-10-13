# Doni Wahyu Kurniawan

# TI-3H | 2241720015 | 08

# Lab - Recommend a Cloud Security Solution

## Part 1: Research and Recommend a Cloud Model and a Cloud Service Model

Cloud models include public cloud, private cloud, hybrid cloud, and community cloud. Cloud service models include Software as a Service (SaaS), Platform as a Service (PaaS), and Infrastructure as a Service (IaaS).

Which cloud service model would you recommend to meet the feature requirements of the company? Explain.

### Jawaban

> Tergantung kebutuhan perusahaan tersebut
>
> * Jika perusahaan membutuhkan solusi perangkat lunak siap pakai (misalnya, CRM, alat kolaborasi), saya akan merekomendasikan SaaS, karena ini meminimalkan overhead manajemen.
> * Jika perusahaan perlu mengembangkan aplikasi kustom tanpa harus mengelola infrastruktur yang mendasarinya, PaaS akan ideal, karena memungkinkan pengembangan dan penerapan yang lebih cepat.
> * Jika perusahaan membutuhkan fleksibilitas, kontrol penuh atas infrastruktur, dan ingin menjalankan berbagai aplikasi dengan kemampuan untuk meningkatkan atau mengurangi skala sesuai kebutuhan, IaaS adalah pilihan terbaik, karena memberikan fleksibilitas maksimum dalam manajemen infrastruktur.

## Part 2: Identify Shared Responsibility for Cloud Services and Cloud Security

Think about shared responsibility for security between the company and a cloud provider for the cloud service model recommended. Use the table below and mark each box with Client, Shared, or Cloud Provider.

Record your chosen cloud service model:

### Jawaban

> Model layanan dipilih: IaaS (Infrastructure as a Service)
> IaaS dipilih karena memberikan fleksibilitas dan kontrol penuh bagi perusahaan (client) dalam hal pengelolaan sistem operasi, aplikasi, dan data. Perusahaan dapat menyesuaikan lingkungan IT sesuai kebutuhan mereka, sementara penyedia cloud menangani infrastruktur fisik seperti server, penyimpanan, dan jaringan.
>
> | Deskripsi | Tanggung Jawab |
> | :----------- | :--------- |
> | Data | Client |
> | Endpoints | Shared |
> | Identity Management | Shared |
> | Application | Client |
> | Network Control | Shared |
> | Operating System | Client |
> | Physical Infrastructure | Cloud Provider |

## Part 3: Identify Five Security Threats Related to Cloud Computing

List at least 5 security threats related to cloud computing.

### Jawaban

> | Threat | Description |
> | :----------- | :--------- |
> | Kebocoran Data | Jika keamanan data tidak dikelola dengan baik, informasi sensitif seperti data pelanggan atau informasi pribadi dapat diakses oleh pihak yang tidak berwenang. |
> | Pembajakan Akun | Pembajakan akun terjadi ketika kredensial login, seperti username dan password, dicuri atau disusupi. Penyerang dapat memanfaatkan akun yang dibajak untuk mengakses data atau sistem penting yang tersimpan di cloud. |
> | API yang Tidak Aman | API yang digunakan untuk mengelola dan berinteraksi dengan layanan cloud harus aman. Jika API tersebut tidak dilindungi dengan baik, mereka dapat menjadi celah bagi penyerang untuk mengeksploitasi layanan cloud. |
> | DoS/DDoS | Serangan DoS atau DDoS dapat membanjiri sistem cloud dengan lalu lintas berlebih, membuat layanan menjadi tidak tersedia bagi pengguna yang sah. Serangan ini dapat mengakibatkan downtime yang signifikan dan memengaruhi kinerja layanan cloud. |
> | Ancaman dari Orang Dalam | Ancaman dari orang dalam terjadi ketika karyawan atau individu yang memiliki akses ke sistem cloud menyalahgunakan hak akses mereka untuk mencuri atau merusak data. Ini bisa terjadi karena motif ekonomi, ketidakpuasan, atau sekadar kesalahan manusia. |

## Part 4: Identify Five Security Measures for Deploying eCommerce Cloud Solution

Perform an internet search to find out security measures required to secure an eCommerce cloud solution.

### Jawaban

> 1. **Keamanan Berlapis**: Gunakan berbagai protokol keamanan seperti firewall, sistem deteksi intrusi (IDS), dan audit keamanan secara berkala.
> 2. **Penggunaan Sertifikat SSL**: Sertifikat SSL (Secure Socket Layer) sangat penting untuk mengenkripsi data yang ditransmisikan antara browser pengguna dan situs eCommerce.
> 3. **Otentikasi Multi-Faktor (MFA)**: MFA menambahkan lapisan keamanan tambahan dengan memerlukan metode otentikasi kedua selain kata sandi, seperti kode satu kali atau autentikasi biometrik.
> 4. **Enkripsi Data**: Pastikan data sensitif, baik saat disimpan maupun saat dikirimkan, dienkripsi.
> 5. **Pembaruan dan Patch Rutin**: Selalu perbarui platform eCommerce, plugin, dan perangkat lunak pihak ketiga untuk menutup kerentanan yang diketahui.
> 6. **Gerbang Pembayaran Aman**: Pastikan gerbang pembayaran yang digunakan telah memenuhi standar keamanan seperti PCI-DSS.
> 7. **Rencana Cadangan dan Pemulihan**: Lakukan pencadangan data secara berkala agar dapat memulihkan data dengan cepat jika terjadi serangan siber atau kegagalan sistem.

## Reflection Questions

1. What are some benefits of deploying online services in cloud?

    > * **Skalabilitas**: Layanan cloud memungkinkan perusahaan untuk dengan mudah meningkatkan atau menurunkan kapasitas sesuai kebutuhan bisnis, tanpa harus berinvestasi pada infrastruktur fisik tambahan.
    > * **Efisiensi Biaya**: Cloud mengurangi kebutuhan investasi awal dalam perangkat keras dan pemeliharaan, karena biaya layanan di cloud biasanya berdasarkan penggunaan (pay-as-you-go).
    > * **Aksesibilitas Global**: Layanan cloud memungkinkan akses dari mana saja selama ada koneksi internet, sehingga memudahkan kolaborasi antar tim dan mempermudah layanan pelanggan di seluruh dunia.
    > * **Keamanan dan Pembaruan Berkala**: Penyedia cloud umumnya menawarkan pembaruan keamanan dan patch secara otomatis untuk memastikan bahwa aplikasi dan data tetap aman dari ancaman terbaru.

2. Can the company rely on the cloud solution provider for everything including services and security? Explain.

    > **Tidak sepenuhnya**. Meskipun penyedia layanan cloud menawarkan berbagai layanan dan fitur keamanan, perusahaan tetap memiliki tanggung jawab dalam beberapa aspek keamanan, terutama yang terkait dengan manajemen data sensitif dan pengaturan akses pengguna. Konsep tanggung jawab bersama dalam cloud computing berarti bahwa penyedia cloud bertanggung jawab atas keamanan infrastruktur, tetapi perusahaan bertanggung jawab atas manajemen data, pengaturan identitas dan akses, serta perlindungan aplikasi yang mereka operasikan di atas cloud​. Jadi, penting bagi perusahaan untuk tetap menjaga kebijakan keamanan internal dan memastikan kepatuhan terhadap regulasi yang berlaku.
