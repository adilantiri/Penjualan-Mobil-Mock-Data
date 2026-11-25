# Penjualan Mobil Mock Data (Jan–Jun 2026)

Dataset simulasi transaksi penjualan unit mobil di berbagai kota dealer di Indonesia selama periode **1 Januari 2026 – 30 Juni 2026**, disusun untuk keperluan latihan analisis data dan pengolahan spreadsheet (Excel).

## Ringkasan Dataset
* **Format file:** `.xlsx` (`Book2.xlsx`, sheet `Sheet1`)
* **Jumlah transaksi (baris):** 1.000 baris (`JM-0001` s.d. `JM-1000`)
* **Total unit terjual:** 1.168 unit (rata-rata 1,17 unit/transaksi; rentang 1–12 unit)
* **Rentang waktu:** 1 Januari 2026 (09:10) – 30 Juni 2026 (16:46)
* **Jumlah kode mobil unik:** 27 kode (`D01`–`D02`, `H01`–`H04`, `M01`–`M07`, `P01`–`P05`, `S01`–`S09`)
* **Kota dealer (10 kota):** Jakarta, Surabaya, Bandung, Makassar, Semarang, Medan, Denpasar, Yogyakarta, Palembang, dan Balikpapan
* **Transmisi:** Otomatis (621 transaksi) dan Manual (379 transaksi)
* **Warna:** Putih, Hitam, Silver, Abu-abu, Merah, dan Biru

## Struktur Kolom
| Nama Kolom | Tipe / Format | Keterangan |
| :--- | :--- | :--- |
| `ID Penjualan` | Teks (`JM-XXXX`) | Kode unik tiap catatan transaksi penjualan |
| `Waktu Penjualan` | Tanggal & Jam | Timestamp terjadinya transaksi |
| `Kode Mobil` | Teks | Kode kategori/model kendaraan (27 kode unik) |
| `Jumlah Unit` | Angka (Integer) | Banyaknya unit mobil dalam satu transaksi |
| `Transmisi` | Teks | Jenis transmisi (`Otomatis` atau `Manual`) |
| `Kota Dealer` | Teks | Kota lokasi dealer tempat transaksi terjadi |
| `Warna` | Teks | Warna unit mobil yang terjual |

## Catatan Sumber Data
Data ini merupakan **dataset simulasi / buatan sendiri (mock data)** yang dibuat untuk kebutuhan latihan pengolahan data, bukan data transaksi resmi dari produsen atau dealer kendaraan.
