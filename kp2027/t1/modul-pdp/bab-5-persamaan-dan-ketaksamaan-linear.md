# Modul PdP Matematik T1 - Bab 5 Persamaan dan Ketaksamaan Linear (KP2027)

Tarikh: 19 Oktober 2026 · Penyedia: Cg Din · Dikemas kini: 21 November 2026

> **Status:** Bahan olahan Jurulatih Utama, bukan bahan rasmi BPK. Rujukan muktamad ialah Dokumen Kurikulum Matematik Tingkatan 1, Kurikulum Persekolahan 2027 (Bahagian Pembangunan Kurikulum, Terbitan 2026, ISBN 978-967-420-830-1).

Modul ini meliputi 9 SP Bab 5 dengan 70 soalan latihan bertahap (36 Asas, 27 Pengukuhan, 7 Pengayaan) yang jawapannya disemak dengan Python (SymPy). Versi 1.0, diselaraskan dengan Dokumen Kurikulum rasmi pada 21 November 2026.

## 1. Maklumat Makro

Bab 5 ialah bab terpadat (9 SP); cadangan saya: ajar 5.1 sebelum Peperiksaan Pertengahan Tahun dan 5.2 selepasnya, mengikut RPT cadangan.

| Perkara | Maklumat |
| --- | --- |
| Bidang Pembelajaran | Perkaitan dan Algebra |
| Tajuk | 5.0 Persamaan dan Ketaksamaan Linear |
| Tingkatan | 1 (KP2027) |
| Cadangan masa | 6 waktu seminggu; 5.1 minggu 17 hingga 18, 5.2 minggu 22 hingga 24 (RPT cadangan) (Dokumen Kurikulum tidak menetapkan peruntukan waktu; ini cadangan RPT sekolah) |
| Elemen nilai tambah | PKJR (had laju, jarak selamat, had muatan) wajib bagi 5.2; Pendidikan Kewangan (bajet) |
| Sasaran | Semua murid, dengan sokongan khas untuk murid belum mencapai tahap penguasaan minimum (TP1 hingga TP3 diberi penekanan) |

| Subtajuk | Kod SP | Pernyataan SP (Dokumen Kurikulum rasmi) |
| --- | --- | --- |
| 5.1 Persamaan Linear | 5.1.1 | Mengenal pasti persamaan linear dalam satu pemboleh ubah dan menghuraikan ciri-ciri persamaan tersebut. |
| 5.1 Persamaan Linear | 5.1.2 | Membentuk persamaan linear dalam satu pemboleh ubah berdasarkan suatu pernyataan atau situasi, dan sebaliknya. |
| 5.1 Persamaan Linear | 5.1.3 | Menyelesaikan persamaan linear dalam satu pemboleh ubah. |
| 5.1 Persamaan Linear | 5.1.4 | Menyelesaikan masalah yang melibatkan persamaan linear dalam satu pemboleh ubah. |
| 5.2 Ketaksamaan Linear | 5.2.1 | Membanding nilai nombor, memerihal ketaksamaan dan seterusnya membentuk ketaksamaan algebra. |
| 5.2 Ketaksamaan Linear | 5.2.2 | Melaksanakan operasi asas aritmetik apabila ditambah, ditolak, didarab atau dibahagi kedua-dua belah ketaksamaan. |
| 5.2 Ketaksamaan Linear | 5.2.3 | Membentuk ketaksamaan linear berdasarkan suatu pernyataan atau situasi, dan sebaliknya. |
| 5.2 Ketaksamaan Linear | 5.2.4 | Menyelesaikan masalah yang melibatkan ketaksamaan linear dalam satu pemboleh ubah. |
| 5.2 Ketaksamaan Linear | 5.2.5 | Menyelesaikan ketaksamaan linear serentak dalam satu pemboleh ubah. |

**Standard Prestasi (Dokumen Kurikulum rasmi):**

| Tahap Penguasaan | Tafsiran |
| --- | --- |
| TP1 | Murid boleh menyatakan huruf atau simbol yang sesuai bagi persamaan dan ketaksamaan linear dalam satu pemboleh ubah. |
| TP2 | Murid boleh menjelaskan ciri-ciri persamaan linear dan perbandingan nilai nombor bagi membentuk ketaksamaan algebra. |
| TP3 | Murid boleh melaksanakan pengiraan bagi persamaan dan ketaksamaan linear dalam satu pemboleh ubah. |
| TP4 | Murid boleh menyelesaikan masalah berkaitan persamaan dan ketaksamaan linear dalam satu pemboleh ubah yang melibatkan kehidupan harian. |


**Rujukan rasmi:** kod dan pernyataan SP disemak dengan Dokumen Kurikulum Matematik Tingkatan 1, Kurikulum Persekolahan 2027 (Bahagian Pembangunan Kurikulum, Terbitan 2026, ISBN 978-967-420-830-1) pada 21 November 2026. Manual penataran menyatakan enam pernyataan umum ketaksamaan WAJIB dibincangkan secara eksplisit (Nota 5.2) dan SP 5.2.1 wajib melibatkan nombor negatif serta tatatanda PKJR. Pernyataan umum ketaksamaan yang perlu dibincangkan (Nota SP 5.2.2, Dokumen Kurikulum): (i) jika a < b, maka b > a; (ii) jika a < b < c, maka a < c; (iii) jika a < b, maka −a > −b; (iv) jika a < b, maka 1/a > 1/b, dengan keadaan a > 0 dan b > 0 atau a < 0 dan b < 0; (v) jika a < b, maka 0 < b − a; dan (vi) jika a < b, maka ca < cb, dengan keadaan c > 0.

## 2. Strategi PdP, Kompetensi Kurikulum dan Kemahiran Matematik

Neraca (keseimbangan) ialah model utama bagi persamaan; garis nombor ialah model utama bagi ketaksamaan. Setiap prosedur simbolik diperkenalkan selepas model visual difahami.

| Strategi | Cara digunakan dalam Bab 5 | Sesuai untuk |
| --- | --- | --- |
| Neraca dan jubin algebra (konkrit) | Persamaan sebagai keseimbangan; buang benda sama dari kedua-dua belah | 5.1.1, 5.1.3 |
| Model bar (piktorial) | Umur, nombor berturutan, pemotongan bahan | 5.1.2, 5.1.4 |
| Garis nombor | Ketaksamaan, bulatan kosong/berlorek, kawasan sepunya | 5.2.1, 5.2.5 |
| Inkuiri terbimbing | Jadual operasi ke atas 4 < 9 untuk menemui bila simbol bertukar | 5.2.2 |
| Kontekstual PKJR dan kewangan | Had laju, jarak selamat, lif, bajet, untung minimum | 5.2.3, 5.2.4 |
| Alat digital | Desmos atau GeoGebra untuk melukis ketaksamaan pada garis nombor | 5.2.4, 5.2.5 |

**Kompetensi kurikulum:** kemahiran berfikir (mentafsir jawapan dalam konteks, pembundaran), literasi pelbagai (papan tanda jalan raya), fasih digital (Desmos).

**Kemahiran matematik:** mewakilkan (neraca, garis nombor), menaakul (mengapa simbol bertukar), berkomunikasi (menterjemah situasi), menyelesaikan masalah (kewangan, kejuruteraan, PKJR).

**Sokongan murid lemah (cadangan saya):** mulakan dengan cuba jaya sebelum prosedur; sentiasa semak jawapan dengan menggantikan; gunakan warna merah untuk langkah “darab/bahagi nombor negatif → tukar simbol”; Exit Ticket 2 soalan di hujung setiap SP.

## 3. SP 5.1.1: Mengenal pasti persamaan linear dalam satu pemboleh ubah dan menghuraikan ciri-ciri persamaan tersebut

**Subtajuk:** 5.1 Persamaan Linear

**Pengetahuan sedia ada:** Ungkapan algebra (Bab 4); konsep sama nilai.

**Aktiviti PdP**

- **Induksi set (5 min):** neraca dua belah: 3 kotak misteri + 2 guli = 11 guli. “Bilakah neraca seimbang?”
- **Aktiviti 1 (konkrit, 15 min):** neraca dan guli (atau aplikasi neraca maya); murid melihat persamaan sebagai keseimbangan.
- **Aktiviti 2 (sisih kad, 15 min):** asingkan kad kepada ungkapan, persamaan linear satu PU, dan bukan linear.
- **Aktiviti 3 (cuba jaya, 10 min):** uji nilai pemboleh ubah untuk melihat sama ada persamaan benar.
- **Penutup (5 min):** Exit Ticket: adakah x = 3 penyelesaian 4x − 5 = 7?

**Perkaitan dunia sebenar:** Menimbang bahan masakan, mengimbangi bajet dengan perbelanjaan.

**Salah konsep lazim:** Menganggap ungkapan dan persamaan sama; Menganggap x² = 9 linear; Menganggap persamaan dua pemboleh ubah sebagai satu pemboleh ubah.

**Latihan Asas**

- **A1** [TP1] Antara berikut, yang manakah persamaan linear dalam satu pemboleh ubah? (a) 2x + 3 = 11 (b) x² = 9 (c) 3x + y = 7 (d) 4m − 1 (e) p/2 = 5
- **A2** [TP1] Apakah beza antara 3x + 5 dan 3x + 5 = 20?
- **A3** [TP1] Dalam persamaan 5y − 2 = 18, nyatakan pemboleh ubah dan kuasa tertingginya.
- **A4** [TP2] Adakah x = 4 penyelesaian bagi 3x − 2 = 10? Tunjukkan.

**Latihan Pengukuhan**

- **P1** [TP2] Tentukan sama ada x = −2 ialah penyelesaian bagi 5 − 2x = 9.
- **P2** [TP2] Antara nilai 2, 3, 4 dan 5, yang manakah memuaskan 4k + 1 = 17? Gunakan kaedah cuba jaya.
- **P3** [TP3] Terangkan mengapa persamaan 2x + 3 = 2x + 5 tiada penyelesaian.

**Latihan Pengayaan** (KBAT)

## 4. SP 5.1.2: Membentuk persamaan linear dalam satu pemboleh ubah berdasarkan suatu pernyataan atau situasi, dan sebaliknya

**Subtajuk:** 5.1 Persamaan Linear

**Pengetahuan sedia ada:** Membentuk ungkapan (4.1.2); kamus operasi.

**Aktiviti PdP**

- **Induksi set (5 min):** teka-teki: “Saya fikir satu nombor, darab 3, tambah 4, dapat 19.” Murid menulis persamaan.
- **Aktiviti 1 (model bar, 15 min):** model bar umur ayah dan anak; tulis persamaan daripada model.
- **Aktiviti 2 (Think-Pair-Share, 15 min):** seorang menulis situasi, pasangan menulis persamaan.
- **Aktiviti 3 (kontekstual, 10 min):** perimeter dan harga barang sebagai persamaan.
- **Penutup (5 min):** Exit Ticket: “Separuh daripada suatu nombor ialah 9.”

**Perkaitan dunia sebenar:** Bajet membeli-belah, umur, perimeter tapak projek.

**Salah konsep lazim:** “dikurangkan daripada” ditulis tertib salah; Terlupa kurungan (4(x + 2) ditulis 4x + 2); Menulis ungkapan tanpa tanda sama.

**Latihan Asas**

- **A1** [TP2] Bentuk persamaan: “hasil tambah x dan 7 ialah 15”.
- **A2** [TP2] Bentuk persamaan: “tiga kali y ialah 27”.
- **A3** [TP2] Bentuk persamaan: “m dibahagi dengan 4 bersamaan 6”.
- **A4** [TP2] Harga sebuah buku ialah RM b. Harga 5 buah buku ialah RM40. Bentuk persamaan.

**Latihan Pengukuhan**

- **P1** [TP2] Bentuk persamaan: “dua kali suatu nombor n ditolak 3 ialah 11”.
- **P2** [TP3] Sisi sebuah segi empat sama ialah (x + 2) cm dan perimeternya 36 cm. Bentuk persamaan.
- **P3** [TP3] Tulis satu situasi harian yang diwakili oleh persamaan 3p + 5 = 20.

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Umur ayah 4 kali umur anaknya. Jumlah umur mereka 50 tahun. (a) Bentuk persamaan menggunakan a sebagai umur anak. (b) Gunakan model bar untuk mencari umur anak.

## 5. SP 5.1.3: Menyelesaikan persamaan linear dalam satu pemboleh ubah

**Subtajuk:** 5.1 Persamaan Linear

**Pengetahuan sedia ada:** Operasi songsang; ungkapan algebra (Bab 4).

**Aktiviti PdP**

- **Induksi set (5 min):** neraca: buang benda yang sama dari kedua-dua belah; neraca masih seimbang.
- **Aktiviti 1 (jubin algebra, 15 min):** selesaikan 3x + 4 = 19 dengan jubin; keluarkan 4 unit dari kedua-dua belah.
- **Aktiviti 2 (operasi songsang, 15 min):** carta aliran “darab 3, tambah 4” disongsangkan “tolak 4, bahagi 3”.
- **Aktiviti 3 (Rally Coach, 10 min):** selesaikan dan semak dengan menggantikan jawapan.
- **Penutup (5 min):** Exit Ticket: selesaikan 2x − 7 = 9.

**Perkaitan dunia sebenar:** Mencari kuantiti tidak diketahui dalam rumus sains dan kewangan.

**Salah konsep lazim:** Melakukan operasi pada satu belah sahaja; Salah tanda ketika memindahkan sebutan; Tidak menyemak jawapan.

**Latihan Asas**

- **A1** [TP2] Selesaikan x + 8 = 15.
- **A2** [TP2] Selesaikan x − 5 = 12.
- **A3** [TP2] Selesaikan 4x = 28.
- **A4** [TP2] Selesaikan x/3 = 6.

**Latihan Pengukuhan**

- **P1** [TP3] Selesaikan 3x + 4 = 19.
- **P2** [TP3] Selesaikan 5 − 2x = 11.
- **P3** [TP3] Selesaikan 4(x − 1) = 2x + 6.

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Selesaikan (x + 2)/3 = (x − 1)/2 dan semak jawapan anda.

## 6. SP 5.1.4: Menyelesaikan masalah yang melibatkan persamaan linear dalam satu pemboleh ubah

**Subtajuk:** 5.1 Persamaan Linear

**Pengetahuan sedia ada:** 5.1.2 dan 5.1.3; 4 langkah Polya.

**Aktiviti PdP**

- **Induksi set (5 min):** harga tiket keluarga ke zoo (hipotetikal): “Berapa kanak-kanak jika jumlah RM62?”
- **Aktiviti 1 (Polya, 15 min):** takrif pemboleh ubah, bentuk persamaan, selesaikan, semak dengan konteks.
- **Aktiviti 2 (model bar, 15 min):** nombor berturutan dan pemotongan rasuk.
- **Aktiviti 3 (Gallery Walk, 10 min):** masalah kewangan, kejuruteraan dan sukan.
- **Penutup (5 min):** Exit Ticket: 4 pek air sama harga dan RM3 untuk beg; jumlah RM15; harga sepek?

**Perkaitan dunia sebenar:** Pendidikan Kewangan: perbandingan pelan; kejuruteraan: pemotongan bahan; sukan: mata pertandingan.

**Salah konsep lazim:** Tidak menakrif pemboleh ubah; Menjawab nilai x tetapi bukan soalan sebenar; Tidak menyemak kewajaran jawapan dalam konteks.

**Latihan Asas**

- **A1** [TP3] Ali membeli 3 buah buku yang sama harga dan membayar RM24. Bentuk persamaan dan cari harga sebuah buku.
- **A2** [TP3] Suatu nombor ditambah 9 menjadi 25. Cari nombor itu.
- **A3** [TP3] Sebuah segi empat tepat mempunyai panjang 12 cm, lebar w cm dan perimeter 40 cm. Cari w.
- **A4** [TP3] Sebuah pasukan memperoleh 21 mata hasil kemenangan sahaja, 3 mata setiap kemenangan. Berapakah bilangan kemenangan?

**Latihan Pengukuhan**

- **P1** [TP3] Tiket dewasa RM15 dan tiket kanak-kanak RM8. Sebuah keluarga dengan 2 orang dewasa dan k kanak-kanak membayar RM62. Cari k.
- **P2** [TP3] Hasil tambah tiga nombor bulat berturutan ialah 72. Cari nombor-nombor itu.
- **P3** [TP3] Sebatang rasuk keluli 9 m dipotong kepada dua bahagian; satu bahagian 1.5 m lebih panjang daripada yang lain. Cari panjang setiap bahagian.

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Pelan telefon A: RM20 sebulan + RM0.15 seminit. Pelan B: RM35 sebulan + RM0.05 seminit. (a) Bentuk persamaan apabila kos kedua-dua pelan sama. (b) Selesaikan dan nyatakan kos ketika itu. (c) Pelan manakah anda pilih jika menggunakan 200 minit sebulan?

## 7. SP 5.2.1: Membanding nilai nombor, memerihal ketaksamaan dan seterusnya membentuk ketaksamaan algebra

**Subtajuk:** 5.2 Ketaksamaan Linear

**Pengetahuan sedia ada:** Garis nombor dan nombor negatif (Bab 1); simbol < dan >.

**Aktiviti PdP**

- **Induksi set (5 min):** gambar papan tanda had laju 30, 60, 90 km/j (PKJR). “Apakah maksud had laju?”
- **Aktiviti 1 (garis nombor, 15 min):** murid berdiri di garis nombor lantai termasuk nombor negatif dan membandingkan kedudukan.
- **Aktiviti 2 (PKJR, 15 min):** tukar papan tanda had laju, had ketinggian dan had muatan kepada ketaksamaan (≤, ≥).
- **Aktiviti 3 (inkuiri, 10 min):** terokai a > b ⇔ b < a dan sifat transitif dengan contoh nombor negatif.
- **Penutup (5 min):** Exit Ticket: tulis ketaksamaan bagi “ketinggian h kenderaan tidak melebihi 4.5 m”.

**Perkaitan dunia sebenar:** PKJR: had laju, had ketinggian jambatan, had muatan lori; had umur; suhu negatif.

**Salah konsep lazim:** Menganggap −7 > −3; Keliru ≤ dan <; Bulatan kosong dan berlorek tertukar.

**Latihan Asas**

- **A1** [TP1] Isikan dengan < atau >: (a) −7 ___ −3 (b) 0 ___ −2 (c) −1.5 ___ −1.2
- **A2** [TP1] Tulis ketaksamaan: “x lebih besar daripada 5”.
- **A3** [TP2] Papan tanda had laju menunjukkan 90 km/j. Tulis ketaksamaan bagi laju kenderaan v yang dibenarkan.
- **A4** [TP2] Huraikan x ≥ −2 dengan perkataan dan nyatakan cara mewakilinya pada garis nombor.

**Latihan Pengukuhan**

- **P1** [TP2] Suhu Bandar P −3°C dan Bandar Q −8°C (hipotetikal). Tulis dua ketaksamaan yang membandingkan suhu itu.
- **P2** [TP3] Diberi a < b dan b < c. Apakah hubungan antara a dan c? Uji dengan a = −5, b = −1, c = 4.
- **P3** [TP3] Sebuah lori mempunyai had muatan 3 tan. Tulis ketaksamaan bagi jisim muatan m, dan senaraikan tiga nilai m yang dibenarkan.

**Latihan Pengayaan** (KBAT)

## 8. SP 5.2.2: Melaksanakan operasi asas aritmetik apabila ditambah, ditolak, didarab atau dibahagi kedua-dua belah ketaksamaan

**Subtajuk:** 5.2 Ketaksamaan Linear

**Pengetahuan sedia ada:** Ketaksamaan (5.2.1); operasi integer.

**Aktiviti PdP**

- **Induksi set (5 min):** “2 < 5. Jika kedua-dua orang dapat RM3 lagi, siapa masih kurang?”
- **Aktiviti 1 (inkuiri, 15 min):** jadual: mulakan dengan 4 < 9; tambah, tolak, darab, bahagi dengan nombor positif dan negatif; rekod bila simbol bertukar.
- **Aktiviti 2 (garis nombor, 15 min):** tunjuk pantulan merentasi sifar apabila didarab −1.
- **Aktiviti 3 (rumusan, 10 min):** murid menulis peraturan sendiri, kemudian bandingkan dengan pernyataan umum dalam dokumen kurikulum.
- **Penutup (5 min):** Exit Ticket: diberi x < 6, tulis −3x ___ −18.

**Perkaitan dunia sebenar:** Membandingkan baki wang selepas perbelanjaan yang sama, perubahan suhu.

**Salah konsep lazim:** Tidak menukar simbol apabila didarab atau dibahagi nombor negatif; Menukar simbol apabila menambah nombor negatif; Menukar simbol tanpa sebab.

**Latihan Asas**

- **A1** [TP2] Diberi 5 > 2. Tambah 3 pada kedua-dua belah. Adakah ketaksamaan masih benar?
- **A2** [TP2] Diberi 6 < 10. Darab kedua-dua belah dengan 2.
- **A3** [TP2] Diberi 4 < 9. Darab kedua-dua belah dengan −1. Apakah yang berlaku kepada simbol?
- **A4** [TP2] Diberi −6 < 3. Bahagi kedua-dua belah dengan −3.

**Latihan Pengukuhan**

- **P1** [TP3] Diberi x > 3, tulis ketaksamaan bagi (a) x + 4 (b) 2x (c) x − 5.
- **P2** [TP3] Diberi y ≤ 5, tulis ketaksamaan bagi −2y.
- **P3** [TP3] Diberi a > b. Lengkapkan dengan simbol yang betul: (a) a − 7 ___ b − 7 (b) −a ___ −b (c) a/4 ___ b/4

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Seorang murid menulis: “2 < 5, darab kedua-dua belah dengan −3, maka −6 < −15.” Nilaikan jawapan itu dan terangkan menggunakan garis nombor.

## 9. SP 5.2.3: Membentuk ketaksamaan linear berdasarkan suatu pernyataan atau situasi, dan sebaliknya

**Subtajuk:** 5.2 Ketaksamaan Linear

**Pengetahuan sedia ada:** 5.2.1; membentuk ungkapan (4.1.2).

**Aktiviti PdP**

- **Induksi set (5 min):** “Lif ini muat maksimum 800 kg.” Bincang maksud “maksimum”.
- **Aktiviti 1 (kamus kata kunci, 15 min):** sekurang-kurangnya (≥), tidak melebihi (≤), lebih daripada (>), kurang daripada (<), maksimum, minimum.
- **Aktiviti 2 (kontekstual, 15 min):** lif, bajet dan jarak selamat (PKJR) diterjemahkan kepada ketaksamaan.
- **Aktiviti 3 (Think-Pair-Share, 10 min):** tulis situasi bagi ketaksamaan yang diberi.
- **Penutup (5 min):** Exit Ticket: “Bilangan pelawat tidak boleh melebihi 120 orang.”

**Perkaitan dunia sebenar:** Bajet bulanan, kapasiti dewan, had laju dan jarak selamat.

**Salah konsep lazim:** “Sekurang-kurangnya” ditulis >; “Tidak melebihi” ditulis <; Terlupa kuantiti tetap dalam situasi.

**Latihan Asas**

- **A1** [TP2] Tulis ketaksamaan: “bilangan peserta n sekurang-kurangnya 30”.
- **A2** [TP2] Tulis ketaksamaan: “harga p tidak melebihi RM50”.
- **A3** [TP2] Tulis ketaksamaan: “umur a kurang daripada 18 tahun”.
- **A4** [TP2] Tulis satu situasi harian bagi t > 12.

**Latihan Pengukuhan**

- **P1** [TP3] Tulis ketaksamaan: “dua kali suatu nombor x ditambah 5 lebih besar daripada 17”.
- **P2** [TP3] Muatan maksimum sebuah lif ialah 800 kg. Sepuluh orang dengan jisim purata 70 kg dan barang b kg berada di dalam lif. Tulis ketaksamaan.
- **P3** [TP3] Bajet Dina RM100. Dia membeli 4 buah buku berharga RM x setiap satu dan sebuah beg RM30. Tulis ketaksamaan.

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Peraturan jarak selamat (PKJR): jarak d meter dengan kenderaan di hadapan mesti sekurang-kurangnya jarak yang dilalui dalam 2 saat pada laju v m/s. (a) Tulis ketaksamaan. (b) Cari jarak minimum pada laju 20 m/s dan 25 m/s. (c) Mengapakah jarak selamat bertambah apabila laju bertambah?

## 10. SP 5.2.4: Menyelesaikan masalah yang melibatkan ketaksamaan linear dalam satu pemboleh ubah

**Subtajuk:** 5.2 Ketaksamaan Linear

**Pengetahuan sedia ada:** 5.2.2 dan 5.2.3; menyelesaikan persamaan (5.1.3).

**Aktiviti PdP**

- **Induksi set (5 min):** “Berapa banyak kek perlu dijual untuk untung sekurang-kurangnya RM200?”
- **Aktiviti 1 (prosedur, 15 min):** selesaikan ketaksamaan seperti persamaan, kecuali tukar simbol apabila darab/bahagi nombor negatif.
- **Aktiviti 2 (konteks ekonomi, 15 min):** jadual kos, jualan dan untung; bandingkan dengan jawapan algebra.
- **Aktiviti 3 (perbincangan, 10 min):** pembundaran ke atas atau ke bawah mengikut konteks.
- **Penutup (5 min):** Exit Ticket: selesaikan 5 − x > 2.

**Perkaitan dunia sebenar:** Pembuatan (had bajet pengeluaran), ekonomi (untung minimum), markah sasaran.

**Salah konsep lazim:** Membundar ke arah salah; Lupa tukar simbol apabila bahagi nombor negatif; Menjawab dalam bentuk persamaan (=).

**Latihan Asas**

- **A1** [TP3] Selesaikan x + 5 > 12.
- **A2** [TP3] Selesaikan 3y ≤ 21.
- **A3** [TP3] Selesaikan x − 4 ≥ −1.
- **A4** [TP3] Selesaikan −2x < 8.

**Latihan Pengukuhan**

- **P1** [TP3] Bajet Dina RM100: 4x + 30 ≤ 100, dengan x ialah harga sebuah buku. Cari harga maksimum sebuah buku.
- **P2** [TP3] Sebuah bengkel membuat bekas dengan kos tetap RM500 dan kos RM2 sebiji. Bajet ialah RM1,500. Bentuk dan selesaikan ketaksamaan untuk mencari bilangan maksimum bekas.
- **P3** [TP3] Markah Hana dalam dua ujian ialah 65 dan 72. Berapakah markah minimum ujian ketiga supaya purata sekurang-kurangnya 70?

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Kelab keusahawanan menjual kek cawan RM6 sebiji. Kos tetap RM90 dan kos bahan RM2.50 sebiji. Kelab mahu untung sekurang-kurangnya RM200. (a) Bentuk ketaksamaan. (b) Cari bilangan minimum kek cawan yang perlu dijual. (c) Mengapakah jawapan perlu dibundarkan ke atas?

## 11. SP 5.2.5: Menyelesaikan ketaksamaan linear serentak dalam satu pemboleh ubah

**Subtajuk:** 5.2 Ketaksamaan Linear

**Pengetahuan sedia ada:** 5.2.4; garis nombor.

**Aktiviti PdP**

- **Induksi set (5 min):** “Suhu akuarium mesti sekurang-kurangnya 24°C tetapi tidak melebihi 27°C.”
- **Aktiviti 1 (garis nombor, 15 min):** lukis dua ketaksamaan pada garis nombor berlainan warna; kawasan bertindih ialah penyelesaian.
- **Aktiviti 2 (prosedur, 15 min):** selesaikan setiap ketaksamaan secara berasingan, kemudian cari kawasan sepunya.
- **Aktiviti 3 (cabaran, 10 min):** kes tiada penyelesaian (x > 5 dan x < 2).
- **Penutup (5 min):** Exit Ticket: senaraikan integer bagi −1 < x ≤ 3.

**Perkaitan dunia sebenar:** Julat suhu, julat umur penyertaan, julat berat bagasi.

**Salah konsep lazim:** Mengambil gabungan, bukan kawasan sepunya; Bulatan kosong dan berlorek salah di sempadan; Tidak menyedari kes tiada penyelesaian.

**Latihan Asas**

- **A1** [TP2] Senaraikan integer x yang memuaskan x > 2 dan x ≤ 6.
- **A2** [TP2] Tulis ketaksamaan serentak bagi x > −1 dan x < 4 dalam satu bentuk.
- **A3** [TP2] Pada garis nombor, terdapat bulatan berlorek di −2 dan bulatan kosong di 3, dengan garis di antara kedua-duanya. Tulis ketaksamaan serentak.
- **A4** [TP3] Cari penyelesaian sepunya bagi x ≥ 1 dan x ≥ 4.

**Latihan Pengukuhan**

- **P1** [TP3] Selesaikan ketaksamaan serentak 2x + 1 > 5 dan x − 3 ≤ 2. Senaraikan integer yang memuaskan.
- **P2** [TP3] Selesaikan ketaksamaan serentak 3x − 2 ≥ 7 dan 10 − x > 3.
- **P3** [TP3] Selesaikan −2x < 6 dan 4x ≤ 12. Berapakah bilangan integer yang memuaskan kedua-duanya?

**Latihan Pengayaan** (KBAT)

- **Y1** [TP4] Suhu air T°C bagi sebuah akuarium mesti memenuhi 2T − 10 ≥ 38 dan T + 5 ≤ 32. (a) Selesaikan ketaksamaan serentak itu. (b) Senaraikan suhu dalam integer yang sesuai. (c) Adakah ketaksamaan serentak x > 5 dan x < 2 mempunyai penyelesaian? Terangkan.

## 12. Bahasa Matematik dan Salah Konsep Bab 5

**Bahasa Matematik (glosari)**

| Istilah | Inggeris | Maksud ringkas |
| --- | --- | --- |
| Persamaan linear | linear equation | Persamaan dengan pemboleh ubah berkuasa 1, contohnya 3x + 4 = 19 |
| Penyelesaian / punca | solution / root | Nilai pemboleh ubah yang menjadikan persamaan benar |
| Operasi songsang | inverse operation | Operasi yang membatalkan operasi lain (tambah ↔ tolak, darab ↔ bahagi) |
| Ketaksamaan | inequality | Hubungan dua kuantiti yang tidak sama, menggunakan <, >, ≤, ≥ |
| Ketaksamaan linear | linear inequality | Ketaksamaan dengan pemboleh ubah berkuasa 1, contohnya 2x + 5 > 17 |
| Sekurang-kurangnya | at least | ≥ |
| Tidak melebihi / maksimum | at most / maximum | ≤ |
| Ketaksamaan serentak | simultaneous inequalities | Dua ketaksamaan yang mesti dipenuhi pada masa yang sama |
| Bulatan berlorek | closed dot | Nilai sempadan termasuk (≤, ≥) |
| Bulatan kosong | open dot | Nilai sempadan tidak termasuk (<, >) |

**Salah konsep dan cara mengesan**

| Salah konsep | Cara mengesan | Pemulihan |
| --- | --- | --- |
| Operasi pada satu belah sahaja | Selesaikan 3x + 4 = 19 | Neraca: apa yang dibuat pada satu belah mesti dibuat pada belah lain |
| Simbol tidak ditukar apabila darab/bahagi nombor negatif | Selesaikan −2x < 8 | Jadual inkuiri 4 < 9 dan garis nombor |
| −7 > −3 | Banding nombor negatif | Garis nombor lantai |
| “Sekurang-kurangnya” ditulis > | Soalan situasi | Kamus kata kunci; uji nilai sempadan |
| Bulatan kosong dan berlorek tertukar | Lukis x ≥ −2 | Tanya “adakah −2 dibenarkan?” |
| Pembundaran salah dalam konteks | Bilangan kek minimum | Semak nilai bulat di kedua-dua sisi sempadan |
| Gabungan, bukan kawasan sepunya | x > 2 dan x ≤ 5 | Dua garis berwarna; penyelesaian di kawasan bertindih |

## 13. Rekreasi Matematik dan Projek PBL

**Rekreasi Matematik (cadangan)**

- **Neraca Misteri:** teka-teki gambar neraca dengan kotak dan guli; murid mencari isi kotak. (5.1.3)
- **Teka Nombor Saya:** seorang murid memberi petunjuk persamaan, kelas menyelesaikannya. (5.1.2, 5.1.3)
- **Pemburuan Papan Tanda:** murid mengambil gambar papan tanda jalan raya di sekitar sekolah (dengan pengawasan) dan menukarkannya kepada ketaksamaan. (5.2.1, PKJR)
- **Garis Nombor Manusia:** dua kumpulan berdiri mewakili dua ketaksamaan; murid yang berada dalam kedua-dua kumpulan ialah penyelesaian serentak. (5.2.5)

**Projek PBL: “Audit Keselamatan Zon Sekolah”**

- **Objektif:** menggunakan persamaan dan ketaksamaan linear untuk menganalisis keselamatan jalan raya di hadapan sekolah (data hipotetikal atau pemerhatian berpengawasan).
- **Senario KBAT:** had laju zon sekolah ditetapkan oleh papan tanda di lokasi (catat nilai sebenar). Kumpulan menganggar masa kenderaan melalui jarak 50 m, mengira laju (v = jarak ÷ masa), menyemak sama ada laju memenuhi ketaksamaan had laju, dan menulis cadangan kepada PIBG.
- **Fasa:** (1) faham masalah; (2) bentuk ketaksamaan had laju dan jarak selamat d ≥ 2v; (3) kumpul dan analisis data; (4) bentang cadangan; (5) refleksi.
- **Kriteria penilaian:** ketaksamaan betul (TP2 dan TP3), analisis dan cadangan berasas data (TP4), keselamatan semasa kerja lapangan, kerjasama kumpulan.
- **Nota keselamatan:** pemerhatian hanya dari kawasan selamat dalam pagar sekolah dengan pengawasan guru; jangan rekodkan nombor pendaftaran kenderaan.

## 14. Skema Jawapan Guru (cetak pada muka surat berasingan)

Semua jawapan dikira dan disemak dengan Python (70 soalan; tiada soalan berulang). Jawapan terbuka menerima penyelesaian lain yang betul.

**SP 5.1.1**

- **A1** (a) dan (e). (b) kuasa 2; (c) dua pemboleh ubah; (d) ungkapan, tiada tanda sama
- **A2** 3x + 5 ialah ungkapan; 3x + 5 = 20 ialah persamaan kerana ada tanda sama dan dua belah yang sama nilai
- **A3** Pemboleh ubah y; kuasa 1 (linear)
- **A4** Ya. 3(4) − 2 = 10
- **P1** Ya. 5 − 2(−2) = 5 + 4 = 9
- **P2** k = 4 kerana 4(4) + 1 = 17
- **P3** Tolak 2x daripada kedua-dua belah: 3 = 5, iaitu pernyataan palsu. Tiada nilai x yang menjadikan kedua-dua belah sama.


**SP 5.1.2**

- **A1** x + 7 = 15
- **A2** 3y = 27
- **A3** m/4 = 6
- **A4** 5b = 40
- **P1** 2n − 3 = 11
- **P2** 4(x + 2) = 36
- **P3** Contoh: 3 batang pen berharga RM p setiap satu dan sebuah buku RM5; jumlah bayaran RM20 (situasi lain yang sesuai diterima)
- **Y1** (a) a + 4a = 50, iaitu 5a = 50  (b) 5 unit = 50, 1 unit = 10: anak 10 tahun, ayah 40 tahun


**SP 5.1.3**

- **A1** x = 15 − 8 = 7
- **A2** x = 12 + 5 = 17
- **A3** x = 28 ÷ 4 = 7
- **A4** x = 6 × 3 = 18
- **P1** 3x = 15; x = 5
- **P2** −2x = 6; x = −3
- **P3** 4x − 4 = 2x + 6; 2x = 10; x = 5
- **Y1** Darab dengan 6: 2(x + 2) = 3(x − 1); 2x + 4 = 3x − 3; x = 7. Semak: 9/3 = 3 dan 6/2 = 3


**SP 5.1.4**

- **A1** 3b = 24; b = RM8
- **A2** n + 9 = 25; n = 16
- **A3** 2(12 + w) = 40; 12 + w = 20; w = 8 cm
- **A4** 3w = 21; w = 7
- **P1** 30 + 8k = 62; 8k = 32; k = 4
- **P2** n + (n + 1) + (n + 2) = 72; 3n + 3 = 72; n = 23. Nombor: 23, 24, 25
- **P3** x + (x + 1.5) = 9; 2x = 7.5; x = 3.75. Bahagian: 3.75 m dan 5.25 m
- **Y1** (a) 20 + 0.15m = 35 + 0.05m  (b) 0.10m = 15; m = 150 minit; kos RM42.50  (c) 200 minit: A = RM50, B = RM45; pilih B


**SP 5.2.1**

- **A1** (a) <  (b) >  (c) <
- **A2** x > 5
- **A3** v ≤ 90 (laju tidak boleh melebihi 90 km/j)
- **A4** x lebih besar daripada atau sama dengan −2. Garis nombor: bulatan berlorek di −2 dengan anak panah ke kanan
- **P1** −8 < −3 dan −3 > −8
- **P2** a < c. Contoh: −5 < −1 dan −1 < 4, maka −5 < 4
- **P3** m ≤ 3; contoh 1.5 tan, 2.8 tan, 3 tan (nilai lain ≤ 3 diterima)


**SP 5.2.2**

- **A1** 8 > 5; benar, arah tidak berubah
- **A2** 12 < 20
- **A3** −4 > −9; simbol bertukar arah
- **A4** 2 > −1; simbol bertukar arah
- **P1** (a) x + 4 > 7  (b) 2x > 6  (c) x − 5 > −2
- **P2** −2y ≥ −10 (darab dengan nombor negatif, simbol bertukar)
- **P3** (a) >  (b) <  (c) >
- **Y1** Salah. −6 > −15 kerana −6 terletak di sebelah kanan −15 pada garis nombor. Mendarab dengan nombor negatif memantulkan nombor merentasi sifar, jadi tertib terbalik dan simbol mesti ditukar.


**SP 5.2.3**

- **A1** n ≥ 30
- **A2** p ≤ 50
- **A3** a < 18
- **A4** Contoh: suhu bilik sejuk t°C mesti lebih tinggi daripada 12°C (situasi lain diterima)
- **P1** 2x + 5 > 17
- **P2** 700 + b ≤ 800
- **P3** 4x + 30 ≤ 100
- **Y1** (a) d ≥ 2v  (b) 20 m/s: d ≥ 40 m; 25 m/s: d ≥ 50 m  (c) Kenderaan laju bergerak lebih jauh dalam masa tindak balas yang sama, jadi lebih banyak ruang diperlukan untuk berhenti dengan selamat.


**SP 5.2.4**

- **A1** x > 7
- **A2** y ≤ 7
- **A3** x ≥ 3
- **A4** x > −4 (bahagi dengan −2, simbol bertukar)
- **P1** 4x ≤ 70; x ≤ 17.5. Harga maksimum RM17.50
- **P2** 2n + 500 ≤ 1500; 2n ≤ 1000; n ≤ 500. Maksimum 500 bekas
- **P3** (137 + x)/3 ≥ 70; 137 + x ≥ 210; x ≥ 73. Markah minimum 73
- **Y1** (a) 6n − (90 + 2.5n) ≥ 200, iaitu 3.5n − 90 ≥ 200  (b) 3.5n ≥ 290; n ≥ 82.86; minimum 83 biji  (c) Bilangan kek mesti nombor bulat; 82 biji memberi untung RM197 sahaja (< RM200)


**SP 5.2.5**

- **A1** 3, 4, 5, 6
- **A2** −1 < x < 4
- **A3** −2 ≤ x < 3
- **A4** x ≥ 4
- **P1** x > 2 dan x ≤ 5, maka 2 < x ≤ 5. Integer: 3, 4, 5
- **P2** x ≥ 3 dan x < 7, maka 3 ≤ x < 7
- **P3** x > −3 dan x ≤ 3, maka −3 < x ≤ 3. Integer: −2, −1, 0, 1, 2, 3 (6 integer)
- **Y1** (a) T ≥ 24 dan T ≤ 27, maka 24 ≤ T ≤ 27  (b) 24, 25, 26, 27 °C  (c) Tiada penyelesaian kerana tiada nombor yang serentak lebih besar daripada 5 dan kurang daripada 2.

## Lampiran: Heuristik dan Standard Proses (Bab 5)

Lampiran ini memetakan soalan Pengukuhan dan Pengayaan kepada strategi heuristik dan 5 Standard Proses (Penyelesaian Masalah, Penaakulan, Perkaitan, Perwakilan, Komunikasi), menambah dua soalan bukan rutin, satu Tugasan Berfikir gaya Bilik Darjah Fikrah, borang Polya dan cadangan laluan modular. Pemetaan dibuat secara sistematik dan ialah cadangan; guru boleh mengubahnya.

### A. Pemetaan soalan kepada heuristik dan Standard Proses

Daripada 34 soalan Pengukuhan dan Pengayaan, 18 dikaitkan dengan strategi heuristik, konteks dunia sebenar atau penaakulan, manakala 16 ialah soalan prosedur terus (rutin). Taburan: Rutin (prosedur terus) 16; Guna algebra (model persamaan) 11; Bina jadual / senarai sistematik 3; Lukis gambar rajah / Model Bar 2; Cuba jaya 1; Uji kes khusus / contoh penyangkal 1.

| SP dan kod | TP | Soalan (ringkas) | Heuristik | Standard Proses utama |
| --- | --- | --- | --- | --- |
| 5.1.1 P1 | TP2 | Tentukan sama ada x = −2 ialah penyelesaian bagi 5 − 2x = 9. | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.1.1 P2 | TP2 | Antara nilai 2, 3, 4 dan 5, yang manakah memuaskan 4k + 1 = 17? Gunakan kaedah cuba jaya. | Cuba jaya | — (kemahiran prosedur) |
| 5.1.1 P3 | TP3 | Terangkan mengapa persamaan 2x + 3 = 2x + 5 tiada penyelesaian. | Rutin (prosedur terus) | Penaakulan, Komunikasi |
| 5.1.2 P1 | TP2 | Bentuk persamaan: “dua kali suatu nombor n ditolak 3 ialah 11”. | Rutin (prosedur terus) | Perwakilan |
| 5.1.2 P2 | TP3 | Sisi sebuah segi empat sama ialah (x + 2) cm dan perimeternya 36 cm. Bentuk persamaan. | Rutin (prosedur terus) | Perwakilan |
| 5.1.2 P3 | TP3 | Tulis satu situasi harian yang diwakili oleh persamaan 3p + 5 = 20. | Rutin (prosedur terus) | Komunikasi |
| 5.1.2 Y1 | TP4 | Umur ayah 4 kali umur anaknya. Jumlah umur mereka 50 tahun. (a) Bentuk persamaan menggunakan a … | Lukis gambar rajah / Model Bar | Penyelesaian Masalah, Perwakilan |
| 5.1.3 P1 | TP3 | Selesaikan 3x + 4 = 19. | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.1.3 P2 | TP3 | Selesaikan 5 − 2x = 11. | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.1.3 P3 | TP3 | Selesaikan 4(x − 1) = 2x + 6. | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.1.3 Y1 | TP4 | Selesaikan (x + 2)/3 = (x − 1)/2 dan semak jawapan anda. | Rutin (prosedur terus) | Penyelesaian Masalah, Penaakulan |
| 5.1.4 P1 | TP3 | Tiket dewasa RM15 dan tiket kanak-kanak RM8. Sebuah keluarga dengan 2 orang dewasa dan k … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perkaitan |
| 5.1.4 P2 | TP3 | Hasil tambah tiga nombor bulat berturutan ialah 72. Cari nombor-nombor itu. | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.1.4 P3 | TP3 | Sebatang rasuk keluli 9 m dipotong kepada dua bahagian; satu bahagian 1.5 m lebih panjang … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perkaitan |
| 5.1.4 Y1 | TP4 | Pelan telefon A: RM20 sebulan + RM0.15 seminit. Pelan B: RM35 sebulan + RM0.05 seminit. (a) … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perwakilan |
| 5.2.1 P1 | TP2 | Suhu Bandar P −3°C dan Bandar Q −8°C (hipotetikal). Tulis dua ketaksamaan yang membandingkan … | Guna algebra (model persamaan) | Penyelesaian Masalah, Penaakulan |
| 5.2.1 P2 | TP3 | Diberi a < b dan b < c. Apakah hubungan antara a dan c? Uji dengan a = −5, b = −1, c = 4. | Uji kes khusus / contoh penyangkal | — (kemahiran prosedur) |
| 5.2.1 P3 | TP3 | Sebuah lori mempunyai had muatan 3 tan. Tulis ketaksamaan bagi jisim muatan m, dan senaraikan … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perwakilan |
| 5.2.2 P1 | TP3 | Diberi x > 3, tulis ketaksamaan bagi (a) x + 4 (b) 2x (c) x − 5. | Rutin (prosedur terus) | Perwakilan |
| 5.2.2 P2 | TP3 | Diberi y ≤ 5, tulis ketaksamaan bagi −2y. | Rutin (prosedur terus) | Perwakilan |
| 5.2.2 P3 | TP3 | Diberi a > b. Lengkapkan dengan simbol yang betul: (a) a − 7 ___ b − 7 (b) −a ___ −b (c) a/4 … | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.2.2 Y1 | TP4 | Seorang murid menulis: “2 < 5, darab kedua-dua belah dengan −3, maka −6 < −15.” Nilaikan … | Lukis gambar rajah / Model Bar | Penyelesaian Masalah, Penaakulan |
| 5.2.3 P1 | TP3 | Tulis ketaksamaan: “dua kali suatu nombor x ditambah 5 lebih besar daripada 17”. | Rutin (prosedur terus) | Perwakilan |
| 5.2.3 P2 | TP3 | Muatan maksimum sebuah lif ialah 800 kg. Sepuluh orang dengan jisim purata 70 kg dan barang b … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perwakilan |
| 5.2.3 P3 | TP3 | Bajet Dina RM100. Dia membeli 4 buah buku berharga RM x setiap satu dan sebuah beg RM30. Tulis … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perwakilan |
| 5.2.3 Y1 | TP4 | Peraturan jarak selamat (PKJR): jarak d meter dengan kenderaan di hadapan mesti … | Guna algebra (model persamaan) | Penyelesaian Masalah, Penaakulan |
| 5.2.4 P1 | TP3 | Bajet Dina RM100: 4x + 30 ≤ 100, dengan x ialah harga sebuah buku. Cari harga maksimum sebuah … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perkaitan |
| 5.2.4 P2 | TP3 | Sebuah bengkel membuat bekas dengan kos tetap RM500 dan kos RM2 sebiji. Bajet ialah RM1,500. … | Guna algebra (model persamaan) | Penyelesaian Masalah, Perwakilan |
| 5.2.4 P3 | TP3 | Markah Hana dalam dua ujian ialah 65 dan 72. Berapakah markah minimum ujian ketiga supaya … | Rutin (prosedur terus) | — (kemahiran prosedur) |
| 5.2.4 Y1 | TP4 | Kelab keusahawanan menjual kek cawan RM6 sebiji. Kos tetap RM90 dan kos bahan RM2.50 sebiji. … | Guna algebra (model persamaan) | Penyelesaian Masalah, Penaakulan |
| 5.2.5 P1 | TP3 | Selesaikan ketaksamaan serentak 2x + 1 > 5 dan x − 3 ≤ 2. Senaraikan integer yang memuaskan. | Bina jadual / senarai sistematik | Perwakilan |
| 5.2.5 P2 | TP3 | Selesaikan ketaksamaan serentak 3x − 2 ≥ 7 dan 10 − x > 3. | Rutin (prosedur terus) | Perwakilan |
| 5.2.5 P3 | TP3 | Selesaikan −2x < 6 dan 4x ≤ 12. Berapakah bilangan integer yang memuaskan kedua-duanya? | Bina jadual / senarai sistematik | — (kemahiran prosedur) |
| 5.2.5 Y1 | TP4 | Suhu air T°C bagi sebuah akuarium mesti memenuhi 2T − 10 ≥ 38 dan T + 5 ≤ 32. (a) Selesaikan … | Bina jadual / senarai sistematik | Penyelesaian Masalah, Penaakulan |

### B. Soalan bukan rutin tambahan (dengan jawapan guru mengikut langkah Polya)

**B1. Kerja ke belakang.** Siti membelanjakan RM12, kemudian separuh daripada baki wangnya. Wang yang tinggal ialah RM19. Berapakah wang asal Siti? Selesaikan dengan dua cara: kerja ke belakang dan persamaan linear.

- **Fahami:** diberi baki akhir RM19.
- **Rancang (heuristik: kerja ke belakang; kemudian model persamaan):** songsangkan langkah, kemudian bandingkan dengan persamaan (x − 12)/2 = 19.
- **Laksana:** kerja ke belakang: 19 × 2 = 38; 38 + 12 = RM50. Persamaan: x − 12 = 38; x = 50.
- **Semak:** 50 − 12 = 38; separuh = 19. Betul; kedua-dua cara memberi jawapan sama.

**B2. Permudah masalah.** Sekumpulan 10 orang membeli tiket wayang: tiket dewasa RM12 dan tiket kanak-kanak RM7. Jumlah bayaran RM95. Berapakah orang dewasa?

- **Fahami:** jumlah orang 10, jumlah bayaran RM95.
- **Rancang (heuristik: bina jadual / cuba jaya, kemudian persamaan):** cuba bilangan dewasa 0, 1, 2, … dan perhatikan bayaran bertambah RM5 setiap kali.
- **Laksana:** semua kanak-kanak: 10 × 7 = RM70. Setiap dewasa menambah 12 − 7 = RM5. Perlu tambah 95 − 70 = RM25, maka 25 ÷ 5 = 5 orang dewasa. Persamaan: 12a + 7(10 − a) = 95; a = 5.
- **Semak:** 5 × 12 + 5 × 7 = 60 + 35 = 95. Betul.

### C. Tugasan Berfikir (Bilik Darjah Fikrah): Siapakah Saya?

**Tugasan:** Saya ialah integer. Dua kali saya ditambah 3 lebih besar daripada 11, tetapi tiga kali saya ditolak 4 tidak melebihi 20. Senaraikan semua kemungkinan diri saya. Kemudian tambah SATU petunjuk supaya hanya satu jawapan tinggal.

- Kumpulan rawak 3 orang di papan putih menegak; wakilkan setiap petunjuk pada garis nombor berlainan warna.
- Soalan guru: “Mengapa 4 tidak termasuk tetapi 8 termasuk?”
- Sambungan: cipta teka-teki ketaksamaan serentak sendiri untuk kumpulan lain.

**Nota guru:** 2x + 3 > 11 → x > 4; 3x − 4 ≤ 20 → x ≤ 8. Jawapan: 5, 6, 7, 8. Contoh petunjuk tambahan supaya satu jawapan: “saya kuasa tiga sempurna” → 8 sahaja (petunjuk lain yang sah diterima).

### D. Borang 4 Langkah Polya (salin untuk murid)

| Langkah Polya | Soalan panduan | Ruang jawapan murid |
| --- | --- | --- |
| 1. Fahami masalah | Apakah yang diberi? Apakah yang dicari? Garis kata kunci. |  |
| 2. Rancang strategi | Heuristik mana sesuai: lukis rajah/Model Bar, bina jadual, cari corak, cuba jaya, kerja ke belakang, permudah masalah, guna algebra? |  |
| 3. Laksana | Tunjukkan langkah kerja dengan teratur. |  |
| 4. Semak semula | Adakah jawapan munasabah? Gantikan semula atau guna cara lain. |  |

### E. Cadangan laluan Pembelajaran Modular (bukan linear)

- **Mendatar:** SP 5.2.3 (ketaksamaan) digabung dengan SP 8.1.2 (data laju kenderaan, PKJR).
- **Mendatar:** SP 5.1.4 (persamaan) digabung dengan SP 7.1.3 (perimeter diberi, cari sisi).
- **Menegak:** operasi songsang Tahun 6 sebagai intervensi sebelum SP 5.1.3.

Nota: laluan modular ialah cadangan manual penataran (paksi mendatar dan menegak); pilih mengikut keperluan murid.
