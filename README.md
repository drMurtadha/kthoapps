# kthoapps

**Senibina Sistem Aplikasi Web Kolej Tun Hussein Onn (KTHO)**

**Pengenalan**

Aplikasi web ini direka untuk menyokong aktiviti dan pengurusan pelajar di Kolej Tun Hussein Onn, Universiti Teknologi Malaysia. Pengguna aplikasi terdiri daripada lima kategori utama: Pelajar KTHO, Ahli Jawatankuasa Kolej Kediaman (JKM), Pengetua Kolej, Felo Kolej, dan Pembantu Felo Kolej. Tujuan utama pembangunan aplikasi ini adalah untuk merekodkan penglibatan pelajar dalam aktiviti kolej, membolehkan pendaftaran aktiviti oleh penganjur, dan mengurus penilaian tahap keaktifan pelajar untuk menentukan kelayakan kuota penginapan semester seterusnya.

**Pengguna dan Peranan**

1. **Pelajar KTHO** - Boleh merekodkan penyertaan mereka dalam aktiviti, mendaftar sebagai peserta aktiviti, dan menyemak rekod penglibatan serta markah tahap keaktifan mereka.
2. **Ahli Jawatankuasa Kolej Kediaman (JKM)** - Berperanan sebagai penganjur yang mendaftarkan aktiviti dan memuat naik butiran berkaitan aktiviti.
3. **Pengetua Kolej** - Meluluskan aktiviti yang didaftarkan dengan atau tanpa peruntukan.
4. **Felo Kolej dan Pembantu Felo** - Menyokong dan memberikan sokongan untuk aktiviti yang didaftarkan oleh Ahli JKM.

**Jadual Pengguna, Peranan, dan Modul Terkaitan**

| Pengguna                        | Peranan                                                    | Modul Terkaitan                          |
|---------------------------------|------------------------------------------------------------|------------------------------------------|
| Pelajar KTHO                    | Merekod penyertaan, mendaftar aktiviti, semak markah       | Kehadiran dan Penyertaan Pelajar, Penilaian Penglibatan Pelajar |
| Ahli Jawatankuasa Kolej (JKM)   | Mendaftarkan aktiviti, memuat naik butiran aktiviti        | Pendaftaran Aktiviti, Pengesahan Aktiviti |
| Pengetua Kolej                  | Meluluskan aktiviti dengan/atau tanpa peruntukan           | Pengesahan Aktiviti, Pelaporan dan Konfigurasi Sistem |
| Felo Kolej dan Pembantu Felo    | Menyokong dan memberikan sokongan kepada aktiviti          | Pengesahan Aktiviti                      |

**Jadual Bilangan Page/Antara Muka bagi Setiap Pengguna**

| Pengguna                        | Bilangan Page/Antara Muka                                  |
|---------------------------------|------------------------------------------------------------|
| Pelajar KTHO                    | 1. Halaman Log Masuk                                       |
|                                 | 2. Halaman Profil Pelajar                                  |
|                                 | 3. Halaman Senarai Aktiviti                                |
|                                 | 4. Halaman Pendaftaran Aktiviti                            |
|                                 | 5. Halaman Penilaian dan Markah Penglibatan                |
| Ahli Jawatankuasa Kolej (JKM)   | 1. Halaman Log Masuk                                       |
|                                 | 2. Halaman Profil JKM                                      |
|                                 | 3. Halaman Pendaftaran Aktiviti                            |
|                                 | 4. Halaman Pengurusan Butiran Aktiviti                     |
|                                 | 5. Halaman Semakan Status Aktiviti                         |
| Pengetua Kolej                  | 1. Halaman Log Masuk                                       |
|                                 | 2. Halaman Kelulusan Aktiviti                              |
|                                 | 3. Halaman Pengurusan Peruntukan                           |
|                                 | 4. Halaman Pelaporan Aktiviti                              |
| Felo Kolej dan Pembantu Felo    | 1. Halaman Log Masuk                                       |
|                                 | 2. Halaman Pengesahan Aktiviti                             |
|                                 | 3. Halaman Sokongan Aktiviti                               |

**Modul Aplikasi dan Aliran Kerja**

1. **Modul Pendaftaran Aktiviti**
   - **Fasa 1: Pendaftaran Aktiviti**
     - **Pengguna Terlibat**: Ahli Jawatankuasa Kolej (JKM)
     - **Tindakan**: Ahli JKM mendaftarkan aktiviti dengan memasukkan butiran aktiviti, seperti nama, kategori impak, tarikh, dan peruntukan diperlukan.
   - **Fasa 2: Sokongan Aktiviti**
     - **Pengguna Terlibat**: Felo Kolej, Pembantu Felo
     - **Tindakan**: Aktiviti yang didaftarkan disemak dan disokong oleh Felo Kolej dan Pembantu Felo.
   - **Fasa 3: Kelulusan Aktiviti**
     - **Pengguna Terlibat**: Pengetua Kolej
     - **Tindakan**: Pengetua meluluskan atau menolak aktiviti, dengan atau tanpa peruntukan yang dipohon.

   **Diagram Aliran Kerja Modul Pendaftaran Aktiviti**
   
   ```
   [JKM] --Mendaftarkan Aktiviti--> [Felo/Pembantu Felo] --Semak & Sokong--> [Pengetua Kolej] --Kelulusan/Tolakan--> [Aktiviti Diluluskan/Ditolak]
   ```

**Cadangan Rupa Borang Pendaftaran Aktiviti oleh Penganjur (JKM)**

Borang pendaftaran aktiviti ini perlu direka bentuk agar dapat memudahkan penganjur untuk memasukkan semua maklumat yang diperlukan dengan jelas dan teratur. Berikut adalah cadangan butiran yang perlu dimasukkan dalam borang pendaftaran aktiviti:

1. **Maklumat Asas Aktiviti**
   - **Nama Aktiviti**: Nama rasmi aktiviti yang akan dianjurkan.
   - **Kategori Aktiviti**: Jenis atau kategori aktiviti (contoh: Kebajikan, Akademik, Rekreasi, Sukan, Sosial).
   - **Impak Aktiviti**: Pilihan untuk memilih tahap impak aktiviti (contoh: Sangat Tinggi, Tinggi, Sederhana Tinggi, Sederhana, Rendah).
   - **Penerangan Aktiviti**: Penerangan ringkas mengenai tujuan dan objektif aktiviti.

2. **Maklumat Jadual dan Lokasi**
   - **Tarikh Aktiviti**: Tarikh mula dan tamat aktiviti.
   - **Masa Aktiviti**: Masa mula dan tamat aktiviti.
   - **Lokasi Aktiviti**: Lokasi di mana aktiviti akan dijalankan (boleh pilih dari senarai lokasi sedia ada atau masukkan lokasi baru).

3. **Maklumat Penganjur dan Jawatankuasa**
   - **Nama Penganjur**: Nama individu atau organisasi penganjur.
   - **Nama Pengarah Program**: Nama penuh pengarah program.
   - **Jawatankuasa Utama**:
     - **Timbalan Pengarah**: Nama penuh timbalan pengarah.
     - **Setiausaha**: Nama penuh setiausaha.
     - **Bendahari**: Nama penuh bendahari.
   - **Jawatankuasa Pelaksana**: Senarai ahli jawatankuasa pelaksana lain beserta jawatan masing-masing.

4. **Maklumat Penyertaan**
   - **Sasaran Peserta**: Kategori dan anggaran jumlah peserta (contoh: Semua pelajar KTHO, Maksimum 100 orang).
   - **Pendaftaran Peserta**: Tarikh mula dan tamat untuk pendaftaran peserta.

5. **Maklumat Kewangan**
   - **Anggaran Perbelanjaan**: Butiran kos yang diperlukan untuk aktiviti (boleh dipecahkan mengikut kategori seperti logistik, makan minum, cenderamata).
   - **Permohonan Peruntukan**: Jumlah peruntukan yang dimohon dari kolej atau pihak tertentu.

6. **Maklumat Kelulusan dan Sokongan**
   - **Penasihat Aktiviti**: Nama Felo atau Pembantu Felo yang bertindak sebagai penasihat dan memberi sokongan terhadap aktiviti.
   - **Status Sokongan**: Status sokongan oleh Felo/Pembantu Felo (contoh: Disokong/Tidak Disokong).

7. **Lampiran Tambahan**
   - **Dokumen Sokongan**: Ruang untuk memuat naik dokumen seperti proposal program, jadual perjalanan, atau sebarang dokumen tambahan yang diperlukan.

8. **Maklumat Paparan dan Persijilan**
   - **Nama untuk Sijil Penghargaan**: Nama yang perlu dimasukkan dalam sijil penghargaan untuk jawatankuasa atau peserta.
   - **Keterangan Paparan Aktiviti**: Keterangan ringkas yang akan dipaparkan dalam senarai aktiviti yang pernah diikuti oleh peserta.

**Reka Bentuk Interface Borang Pendaftaran Aktiviti**
- **Antara Muka Ringkas dan Mesra Pengguna**: Borang ini perlu mempunyai reka bentuk yang jelas, dengan setiap bahagian dipisahkan secara visual agar memudahkan penganjur untuk memahami dan mengisi borang tanpa sebarang kekeliruan.
- **Bahagian Pengesahan**: Bahagian terakhir untuk mengesahkan butiran yang telah dimasukkan sebelum menghantar borang untuk sokongan dan kelulusan.
- **Navigasi yang Mudah**: Terdapat butang navigasi seperti 'Simpan sebagai Draf', 'Hantar untuk Sokongan', dan 'Batal' untuk memberikan fleksibiliti kepada pengguna.

**Modul dan Aliran Kerja Lain dalam Sistem**

1. **Modul Pengesahan Aktiviti**
   - **Fasa 1: Semakan Sokongan**
     - **Pengguna Terlibat**: Felo Kolej, Pembantu Felo
     - **Tindakan**: Memastikan semua butiran aktiviti adalah tepat dan sesuai sebelum memberi sokongan rasmi.
   - **Fasa 2: Kelulusan Pengetua**
     - **Pengguna Terlibat**: Pengetua Kolej
     - **Tindakan**: Aktiviti yang disokong dihantar untuk kelulusan akhir oleh Pengetua Kolej.

   **Diagram Aliran Kerja Modul Pengesahan Aktiviti**
   
   ```
   [Felo/Pembantu Felo] --Semakan Sokongan--> [Pengetua Kolej] --Kelulusan--> [Aktiviti Disahkan]
   ```

**Bentuk Pelaporan yang Boleh Dihasilkan**

1. **Pelaporan Penglibatan Pelajar**
   - Laporan individu mengenai aktiviti yang disertai oleh pelajar, termasuk markah penglibatan dan kategori impak.
   - **Pengguna Terlibat**: Pelajar KTHO, Pengetua Kolej, Ahli JKM

2. **Pelaporan Statistik Kehadiran Aktiviti**
   - Laporan statistik mengenai kehadiran pelajar untuk setiap aktiviti yang dianjurkan, termasuk jumlah peserta dan tahap keaktifan.
   - **Pengguna Terlibat**: Ahli JKM, Felo Kolej, Pengetua Kolej

3. **Pelaporan Kelulusan Aktiviti**
   - Laporan mengenai senarai aktiviti yang telah diluluskan atau ditolak, termasuk maklumat peruntukan dan kelulusan.
   - **Pengguna Terlibat**: Pengetua Kolej, Felo Kolej, Ahli JKM

4. **Pelaporan Kelayakan Penginapan**
   - Laporan senarai pelajar yang layak atau tidak layak untuk kekal di kolej berdasarkan markah keaktifan.
   - **Pengguna Terlibat**: Pengetua Kolej, Ahli JKM

5. **Pelaporan Ringkasan Aktiviti Kolej**
   - Laporan ringkasan semua aktiviti yang telah dianjurkan, termasuk jenis aktiviti, kategori impak, dan statistik penyertaan.
   - **Pengguna Terlibat**: Pengetua Kolej, Ahli JKM, Felo Kolej

6. **Pelaporan Analisis Peruntukan**
   - Laporan mengenai peruntukan yang telah diberikan kepada aktiviti, termasuk status penggunaan dan baki peruntukan.
   - **Pengguna Terlibat**: Pengetua Kolej, Ahli JKM

**Rubrik Pemarkahan Berdasarkan Jenis Impak Aktiviti**

| Jenis Impak          | Markah yang Diberikan |
|----------------------|------------------------|
| Impak Sangat Tinggi  | 20 Markah              |
| Impak Tinggi         | 15 Markah              |
| Impak Sederhana Tinggi | 10 Markah            |
| Impak Sederhana      | 5 Markah               |
| Impak Rendah         | 2 Markah               |

**Rubrik Pemarkahan Berdasarkan Peranan dalam Penganjuran Aktiviti**

| Peranan Jawatankuasa           | Markah yang Diberikan |
|--------------------------------|------------------------|
| Pengarah Program               | 25 Markah              |
| Timbalan Pengarah              | 20 Markah              |
| Setiausaha                     | 18 Markah              |
| Bendahari                      | 18 Markah              |
| Ahli Jawatankuasa Pelaksana    | 15 Markah              |
| Peserta                        | 5 Markah               |

**Senibina Sistem**

Senibina sistem aplikasi ini dibahagikan kepada beberapa komponen utama:

1. **Antara Muka Pengguna (User Interface)**  
   Antara muka pengguna yang mesra pengguna dan interaktif direka menggunakan platform low-code atau no-code. Ia menyediakan akses untuk setiap kategori pengguna, mengikut peranan mereka dalam sistem.

2. **Pangkalan Data**  
   Pangkalan data disediakan untuk menyimpan semua data pelajar, aktiviti, penyertaan, dan markah keaktifan. Struktur pangkalan data ini merangkumi jadual pelajar, jadual aktiviti, jadual kehadiran, serta jadual markah yang boleh disesuaikan.

3. **Logik Perniagaan (Business Logic Layer)**  
   Logik perniagaan sistem mengawal proses pendaftaran aktiviti, kelulusan aktiviti, rekod kehadiran, dan pengiraan markah. Ia juga mengurus penilaian kelayakan kuota penginapan.

4. **API dan Integrasi**  
   API boleh digunakan untuk mengintegrasikan sistem ini dengan sistem sedia ada di UTM, seperti sistem Hal Ehwal Pelajar, untuk memudahkan kemas kini data pelajar dan penyelarasan aktiviti.

5. **Keselamatan dan Kawalan Akses**  
   Setiap pengguna mempunyai tahap akses yang berbeza, dan sistem keselamatan dibangunkan bagi memastikan data hanya boleh diakses oleh pengguna yang diberi kebenaran. Pengguna log masuk dengan kredensial unik dan kawalan akses berdasarkan peranan akan digunakan untuk melindungi data.

**Kesimpulan**

Aplikasi web ini bertujuan untuk memudahkan pengurusan aktiviti pelajar dan menyediakan penilaian yang objektif terhadap penglibatan pelajar dalam aktiviti kolej. Dengan menggunakan pendekatan low-code/no-code, pembangunan aplikasi ini boleh dipercepatkan dan memudahkan pengguna tanpa pengalaman teknikal untuk menggunakannya. Sistem ini bukan sahaja dapat meningkatkan keberkesanan pengurusan aktiviti di KTHO tetapi juga menggalakkan pelajar untuk lebih aktif terlibat dalam aktiviti kampus.

