# ACUAN PROYEK — PT JAWA DWIPA NUSANTARA (JDN)

## 1. Fungsi Dokumen

Dokumen ini adalah **ACUAN PROYEK utama** JDN.

**Setiap kali akan melakukan apa pun dalam proyek JDN, langkah pertama wajib membaca `ACUAN-PROYEK.md`.**

Acuan Proyek berbeda dengan Acuan Market:
- **ACUAN PROYEK** = acuan umum seluruh proyek JDN: identitas proyek, struktur/peran, produk, partner, prinsip kerja, lokasi catatan, aturan pencatatan, workflow, dan keputusan umum proyek.
- **ACUAN MARKET** = acuan khusus ketika pekerjaan/diskusi menyangkut market research, target market, buyer research, product-market fit, competitor, pricing market, regulatory market, dan commercial validation.

Jadi Acuan Market **bukan pengganti Acuan Proyek**. Acuan Proyek selalu dibaca lebih dahulu; jika pekerjaan menyangkut market, setelah itu baca Acuan Market dan file market terkait.

## 2. Peta File / Ke Mana Harus Mengecek

| Kebutuhan | Sumber utama |
|---|---|
| Acuan umum seluruh proyek | **`ACUAN-PROYEK.md`** |
| Market research / target market / prinsip pencarian market / buyer research methodology | **Acuan Market** dan file riset market terkait |
| Data buyer, calon buyer, kontak, status, histori | **`BUYER-VALID-POTENSIAL.md`** |
| Harga produk JDN EXW, opening price, net price | **`HARGA-EXW-JDN.md`** |
| Website, keputusan website, domain, struktur/konten website | **master catatan website yang sudah ada** |
| Informasi legal/sertifikasi/produksi partner | **file master yang relevan**; jika belum ada, jangan membuat file baru tanpa instruksi |

Jika ragu informasi berada di mana, **baca Acuan Proyek terlebih dahulu**, lalu cari file master yang sudah ada. Jangan langsung membuat catatan baru.

## 3. Aturan Single Source of Truth

1. Satu jenis informasi mempunyai satu file master utama.
2. Jika informasi buyer berubah/bertambah → update `BUYER-VALID-POTENSIAL.md`.
3. Jika harga berubah/bertambah → update `HARGA-EXW-JDN.md`.
4. Jika informasi market/metodologi market berubah → update **Acuan Market** atau file market master yang relevan.
5. Jika informasi website berubah/bertambah → update master website yang sudah ada.
6. Jangan membuat file `UPDATE`, `ADDENDUM`, `PATCH`, atau file paralel hanya karena ada informasi baru.
7. Jangan membuat file baru kecuali user secara eksplisit memerintahkannya atau memang belum ada master file yang sesuai dan kebutuhan tersebut benar-benar berbeda jenis informasinya.
8. Catatan baru ditempatkan pada section/row/record yang paling relevan agar urut dan terhubung.
9. Data lama yang ditolak, tidak aktif, atau tidak lagi prioritas tidak dihapus tanpa alasan; histori penting dipertahankan pada master yang sesuai.

## 4. Ringkasan Proyek

PT Jawa Dwipa Nusantara (JDN) direncanakan sebagai perusahaan ekspor/impor yang pada awalnya berfokus pada produk **beras organik**, dengan rencana pengembangan ke berbagai produk lain di masa mendatang.

### Produk Awal
- Produk awal: **beras organik**.
- Ke depan JDN dapat mengembangkan dan menjual lebih banyak produk, baik berasal dari mitra supplier maupun produk yang dibuat sendiri.

### Mitra Produksi / Maklon
- Mitra produksi saat ini adalah **PT Hotel Indo Industri (PT HII)**.
- PT HII sebelumnya bernama **CV Shinta Rama**.
- Sertifikasi yang sebelumnya atas nama CV Shinta Rama akan berubah/ditujukan menjadi atas nama **PT Hotel Indo Industri**, sesuai proses perubahan legal dan administrasi sertifikasi.
- JDN berencana membuat **merek/brand sendiri** untuk produk beras organik.
- Produk dengan merek JDN akan diproduksi oleh PT HII dengan skema **maklon**.

### Ekspor
Selain menjual produk dengan merek JDN sendiri, JDN juga direncanakan dapat melayani **ekspor beras organik secara maklon sesuai permintaan buyer**. Spesifikasi, merek, kemasan, atau kebutuhan produk dapat disesuaikan dengan permintaan buyer berdasarkan kesepakatan bisnis dan kemampuan produksi/sertifikasi PT HII.

### Struktur Peran Sementara
| Pihak | Peran |
|---|---|
| **PT Jawa Dwipa Nusantara (JDN)** | Pemilik/pengelola bisnis, pengembangan merek sendiri, penjualan, dan kegiatan ekspor/impor |
| **PT Hotel Indo Industri (PT HII)** | Mitra produsen/maklon beras organik dan pemegang/kelanjutan sertifikasi yang sebelumnya terkait CV Shinta Rama |
| **Buyer** | Pembeli/importir; dapat meminta produk beras organik dengan spesifikasi atau merek tertentu untuk skema ekspor maklon |

## 5. Produk / SKU yang Sedang Dikembangkan

- Hotel Super Head / White Rice
- Premium Red Rice
- Black Rice
- Pandan Wangi / Indonesian Fragrant Rice
- Rainbow Rice
- Sugar Free Rice / Parboiled Low-GI Rice
- Milk Rice
- Varian lain yang ditambahkan kemudian.

Catatan positioning produk secara khusus berada di Acuan Market jika berkaitan dengan strategi market.

## 6. Prinsip Harga Umum

- Harga produk yang menjadi acuan ekspor saat ini adalah **EXW**, bukan CIF.
- Detail seluruh angka harga wajib dicek di **`HARGA-EXW-JDN.md`**.
- Harga USD bukan source of truth karena berubah mengikuti kurs; **IDR adalah source of truth**.
- File harga memisahkan **Opening Price** dan **Net Price / Negotiation Floor**.
- Net price adalah harga yang sudah menyisakan margin JDN Rp5.000/kg sesuai catatan harga yang telah diberikan.
- Jika suatu varian belum mempunyai net price, jangan mengarangnya.

## 7. Prinsip Buyer Umum

Semua buyer potensial dicatat di **`BUYER-VALID-POTENSIAL.md`**.

- Semua hasil buyer valid dicatat, bukan hanya Top 10.
- Top 10 hanya menunjukkan prioritas outreach.
- Penolakan atau tidak ada respons bukan alasan menghapus histori buyer.
- Kontak harus dicatat selengkap mungkin jika valid: website, email, phone, address, buyer type, evidence, source, priority, product fit, dan verification notes.
- Jangan mengarang kontak atau identitas legal.

Detail metodologi pencarian buyer dan definisi valid buyer berada di **Acuan Market**, bukan di Acuan Proyek.

## 8. Prinsip Operasional

- Jangan berubah-ubah metodologi hanya karena hasil pencarian sementara berbeda.
- Jika melakukan riset, gunakan sumber resmi/valid dan bedakan fakta, hasil web research, dan inference.
- Jika menemukan informasi yang memerlukan pencatatan, langsung masukkan ke master file yang sesuai.
- Jika user mengatakan "catat", tentukan terlebih dahulu master file berdasarkan Peta File di atas.
- Jika user mengatakan "lanjutkan riset", baca Acuan Proyek dahulu, lalu Acuan Market jika risetnya tentang market.

## 9. Regulatory / Certification

Status legal, sertifikasi, kapasitas produksi, layanan maklon, dan persyaratan ekspor PT HII harus diverifikasi dari dokumen resmi terbaru sebelum digunakan sebagai dasar transaksi atau materi pemasaran.

Untuk pertanyaan market-specific mengenai recognition certification, import requirement, organic claim, labeling, customs, atau regulatory negara tujuan, gunakan **Acuan Market** dan sumber resmi negara tujuan.

## 10. Workflow Aman GitHub

GitHub diperlakukan sebagai repository sungguhan.

Sebelum melakukan perubahan:
1. Baca **Acuan Proyek**.
2. Tentukan file master yang benar.
3. Fetch versi terbaru file/HEAD.
4. Untuk file panjang, bila perlu ambil blob lengkap berdasarkan SHA agar tidak bekerja dari response yang terpotong.
5. Jangan menggunakan SHA lama.
6. Update hanya file master yang relevan.
7. Jika Contents API bermasalah, gunakan workflow Git Data API bila tersedia: create blob → create tree → create commit → update branch ref.
8. Setelah write, **wajib verifikasi** HEAD → commit → tree/blob/file.
9. Jangan menganggap update gagal hanya karena wrapper mengembalikan error sebelum memeriksa repository.
10. Jangan memaksa overwrite dengan SHA lama.
11. Jangan membuat file paralel sebagai workaround teknis.

## 11. Riwayat / Status Struktur Acuan

- **2026-08-25** — Catatan awal proyek disusun berdasarkan informasi JDN, PT HII, produk beras organik, merek sendiri, skema maklon, dan ekspor.
- **2026-08-30** — Struktur diperjelas: `ACUAN-PROYEK.md` menjadi titik awal seluruh pekerjaan proyek. Acuan Market diposisikan sebagai acuan khusus pekerjaan market dan tidak menggantikan Acuan Proyek.

## 12. Aturan Paling Penting

> **SEBELUM MELAKUKAN APA PUN DALAM PROYEK JDN, BACA `ACUAN-PROYEK.md` TERLEBIH DAHULU.**
>
> Setelah itu, buka file master yang relevan. Untuk pekerjaan market, lanjutkan dengan membaca **Acuan Market**.

Jangan mengandalkan ingatan percakapan jika informasi yang dibutuhkan sudah tercatat dalam file proyek.
