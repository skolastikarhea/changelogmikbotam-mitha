CHANGELOG
PERINTAH TAMBAHAN BOT TELEGRAM YANG TERSEDIA
- /pppoe : untuk mengontrol user secret pppoe
- /otodepo : untuk deposit otomatis via payment gateway
- /laptgl spasi tglbulantahun, contoh : /laptgl 30012020
- /lapbul : untuk melihat laporan bulan ini
- /lap spasi tglblnthnawal spasi tglblnthnakhir, contoh : /lap 01012020 12022020
- /reseller : untuk menampilkan data reseller
- /cekvcr spasi kode voucher : untuk melihat masa aktif voucher yang dibuat menggunakan mitha
- /pesan spasi isi pesan : untuk mengirim pesan ke seluruh reseller
- /rekap : untuk memunculkan hasil transaksi hari ini
- /rekap spasi tglblnthn spasi tglblnthn, contoh : /rekap 12042020 07112020
- /rekapall : untuk melihat rekapan masing-masing reseller
- /delreport : untuk menghapus laporan bulan lalu atau laporan setelah 3 bulan yang lalu, membuat kinerja server dan bot menjadi ringan
- /help : untuk melihat perintah yang lain

Juli 2023 (M.I.T.H.Assistant) v3.2.5
- bugfix mikrotik ROS versi 7.10
- bugfix FUP sistem reset di profile hotspot
- support php 8
- max top up 9 digits
- bugfix pembayaran pppoe oleh reseller (/bayarpppoe spasi nama akunnya)
- tombol pada /deposit lebih banyak pilihan nominal
- optimasi generate voucher massal di web

Januari 2023 (M.I.T.H.Assistant) v3.2.4
- perbaikan bug $price di cetak voucher
- perbaikan bug pppoe

Desember 2022 (M.I.T.H.Assistant) v3.2.3
- pembayaran akun pppoe dapat dilakukan oleh reseller dengan perintah /bayarpppoe spasi nama akunnya
- payment gateway support lebih banyak metode pembayaran
- menu /deposit diperbanyak opsi nominalnya
- perbaikan bug $price di cetak voucher, dari (10000) menjadi Rp. 10.000
- perbaikan bug /help
- perbaikan bug pppoe

November 2022 (M.I.T.H.Assistant) v3.2.2
- optimasi generate voucher
- ketika voucher gagal generate gambar, maka akan dikirim tanpa gambar
- bug fix pppoe pindah profile

Januari 2022 (M.I.T.H.Assistant) v3.2.1
- bug fix logo, hanya png
- bug fix cetak voucher
- bug fix laporan per reseller

Desember 2021 (M.I.T.H.Assistant) v3.2
- notifikasi ke bot telegram jika ada yang login ke web
- /menu ada tahap konfirmasi (menghindari salah pencet voucher)
- /topup ganti tampilan, tidak perlu menghafal ID telegram
- group voucher untuk default user baru, jika tidak ada voucher yang masuk default maka user baru tidak akan melihat daftar voucher
- sistem uplink dan downlink (fee 10% dari margin)
- menu PPPoE dengan opsi pindah profile atau disable user secret
- /pppoe dan /otodepo command
- menu cetak ulang voucher fisik
- cetak voucher thermal dari telegram
- menu payment gateway tripay
- menu search untuk mencari user
- /daftar akan ada approval dari admin
- group telegram info seputar MIKBOTAM MITHA di Group INFO MIKBOTAM MITHA

Desember 2020 (M.I.T.H.Assistant) v3.1
- Template Generate Voucher bisa menggunakan template mikhmon (settings>settings template)
- Menu /hotspot dimunculkan kembali
- fitur transfer antar reseller : /transfer spasi nomor ID tujuan spasi nominal
- data omset bulan lalu dan bulan sekarang di dashboard
- fitur Grup Reseller dan Voucher (voucher dengan grup tertentu hanya bisa diakses oleh reseller dengan grup yang sama)
- topup instant via /deposit dimunculkan kembali
- fitur rekap omset reseller : /rekap (bisa dipakai semua reseller) dan /rekapall (hanya akses admin)
- fitur delete rekapan : /delreport , untuk menghapus laporan bulan lalu dan atau setelah 3 bulan yg lalu, berfungsi untuk meringankan kinerja server dan bot
- fitur FUP di Profile Hotspot

Juni 2020 (M.I.T.H.Assistant) v3.0
- rebranding jadi M.I.T.H.Assistant
- perbaikan bug bot
- voucher dengan nama yang diinginkan
- notif voucher ke reseller
- webhook pindah ke settings
- perbaikan tampilan voucher
- penghapusan section edit core.php karena sudah tidak relevan
- diskon dalam persen untuk masing masing reseller
- generate voucher secara massal, output berbentuk pdf, dan dikirim ke telegram admin
- fitur sinkronisasi tombol delete dengan mikrotik
- delete voucher secara massal berdasarkan username / tipe voucher (termasuk yang ada di mikrotik)
- perubahan tampilan dashboard
- info voc di dashboard menampilkan kapan user tsb online pertama kali dan kapan akan berakhir

April 2020 (rumahpetir) v2.7.1
- tambah command bot : /pesan untuk mengirim pesan massal ke reseller
- remake telegram voucher info
- menu logo voucher
- cek laporan range tanggal tertentu, termasuk detail reseller
- tombol hapus voucher dan history reseller
- prefix di voucher, untuk memberi ciri pada jenis voucher

3 April 2020 (rumahpetir) v2.6
- unlimited voucher profile list
- menu setting text response bot
- max top up 9.999.999

25 Februari 2020 (rumahpetir) v2.5
- tambah menu di USER PROFILE HOTSPOT
- tambah fitur pilihan auto delete voucher jika sudah berakhir
- tambah fitur pilihan notif via telegram ketika pertama kali voucher digunakan
(fitur ditambahkan di file add_profile.php)
- edit limit uptime di voucher dari null menjadi default 0
- hapus GoCostumer
- hapus Voucher Non Saldo
- hapus SMS Gateway
- menambah menu change log

05 Februari 2020 (rumahpetir) v2.3
- hapus /qrcode

28 Januari 2020 (rumahpetir) v2.3
- move some codes to new files

27 Januari 2020 (rumahpetir) v2.2.2
- update daily report via telegram
- update monthly report via telegram
- add /cekuser, /reseller, and new command to /help

24 Januari 2020 (rumahpetir) v2.2.1
- update check voucher

02 Januari 2020 (rumahpetir) v2.2
- Add reseller list to bot

19 November 2019 (rumahpetir) v2.1
- Add delete button on history user

2 November 2019 (rumahpetir) v2.0
- Add Check Voucher Expired page
- Add command /cekvcr
