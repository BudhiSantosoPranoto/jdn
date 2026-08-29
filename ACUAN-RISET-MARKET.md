# ACUAN PROYEK — JDN

Dokumen ini adalah **acuan proyek utama** untuk pekerjaan JDN. Setiap kali akan melakukan apa pun dalam proyek ini, baca dokumen ini terlebih dahulu. Jangan mengambil keputusan berdasarkan ingatan percakapan saja jika informasi sudah atau seharusnya tercatat di repository.

## 1. Peta Catatan / Single Source of Truth

Gunakan file master berikut sesuai jenis informasi:

- **Buyer / calon buyer / status buyer / kontak buyer** → `BUYER-VALID-POTENSIAL.md`
- **Harga EXW JDN / opening price / net price** → `HARGA-EXW-JDN.md`
- **Website / pekerjaan dan keputusan website** → file master website yang sudah ada di repository
- **Market research / metodologi / target market / product-market fit / regulatory / commercial screening** → file acuan market ini
- Jika informasi sudah mempunyai file master, **update file master tersebut**, jangan membuat file catatan baru/UPDATE/ADDENDUM/PATCH kecuali user secara eksplisit memerintahkan.

### Aturan umum pencatatan
1. Satu jenis informasi mempunyai satu sumber kebenaran utama.
2. Informasi baru ditambahkan langsung ke file master yang relevan.
3. Letakkan record pada section/row yang relevan agar urutan dan hubungan antar-data tetap jelas.
4. Jangan membuat salinan informasi yang berpotensi berbeda dengan master.
5. Sebelum setiap pekerjaan/rise​t/update, baca ulang acuan proyek ini dan file master yang relevan.

## 2. Prinsip Riset Buyer

### 2.1 Jangan membatasi buyer berdasarkan varietas
Buyer yang sudah mengimpor/menjual Organic Rice tetap potensial walaupun varietas yang sekarang mereka jual adalah Basmati, Sonamasuri, Jasmine, Long Grain, Ponni, Matta, Sella, Brown, White, atau varietas lain.

Perbedaan varietas bukan alasan mencoret buyer. Itu dapat menjadi **new SKU opportunity / category expansion**.

Analogi strategi: buyer yang selama ini menjual Android tidak berarti tidak mungkin menjual iPhone. JDN dapat menawarkan lini baru tanpa harus menggantikan varietas existing.

### 2.2 Dua jalur pencarian
**A. Organic Rice buyer**
- Importer/distributor/buyer yang sudah mengimpor atau menjual Organic Rice jenis apa pun.

**B. Specialty / Premium Rice buyer**
- Buyer yang menangani Black, Red, Brown, Fragrant/Aromatic, Jasmine, Heritage, Healthy/Superfood, Specialty, atau Premium Rice.

### 2.3 Product matching
Varietas existing buyer digunakan untuk menentukan cara menawarkan SKU JDN, bukan untuk menolak buyer.

Contoh:
- Organic Jasmine → Indonesian Organic Pandan Wangi sebagai aromatic/fragrant SKU baru.
- Organic Basmati/Brown → Red Premium/Brown/Specialty sebagai lini berbeda.
- Black Rice → JDN Black sebagai alternatif/new supplier.
- Premium/Healthy Rice → SKU JDN dengan diferensiasi kuat.
- Basmati/health-oriented → dapat diuji untuk Sugar Free/Parboiled Low-GI, dengan syarat claim harus memiliki substantiation dan memenuhi regulasi label market tujuan.

## 3. SKU JDN

- Hotel Super Head / White Rice
- Premium Red Rice
- Black Rice
- Pandan Wangi / Indonesian Fragrant Rice
- Rainbow Rice
- Sugar Free Rice / Parboiled Low-GI Rice
- Milk Rice
- Varian baru yang ditambahkan kemudian

Pandan Wangi diposisikan sebagai **aromatic/fragrant Indonesian specialty rice**, bukan sekadar pengganti Jasmine. Perbedaan varietas adalah bagian dari positioning.

## 4. Aturan Harga

Semua harga produk JDN untuk screening adalah **EXW**, bukan CIF.

**Source of truth harga: `HARGA-EXW-JDN.md`.**

File harga memisahkan:
1. **Opening Price** — harga penawaran awal dengan ruang negosiasi.
2. **Net Price / Negotiation Floor** — harga net yang sudah menyisakan margin JDN Rp5.000/kg.

IDR adalah source of truth. USD hanya hasil konversi sesuai kurs analisis/tanggal.

Untuk varian yang belum memiliki net price, jangan mengarang angka net. Gunakan opening price sementara dan beri status.

Screening economics harus memakai dua skenario:
- opening price;
- net price.

EXW bukan landed cost. Untuk feasibility perlu menambahkan origin handling, inland/export handling, freight, insurance, customs, destination charges, distributor/retailer margin, dan biaya relevan lain.

## 5. Aturan Buyer

Semua buyer/lead yang ditemukan dicatat di **`BUYER-VALID-POTENSIAL.md`**, bukan hanya Top 10.

Top 10 hanya prioritas outreach.

Buyer yang menolak, tidak merespons, atau gagal kualifikasi **tidak dihapus**; status dan histori dipertahankan.

Kontak dicatat selengkap mungkin:
- company name
- country/city
- buyer type
- website
- official email
- phone
- address
- shipment/RFQ evidence
- product evidence
- organic evidence
- specialty/premium evidence
- source
- priority
- product fit
- verification notes

Jangan mengarang kontak atau identitas legal.

## 6. Klasifikasi Buyer

- **VALID POTENSIAL — SHIPMENT EVIDENCE:** ada shipment Organic Rice.
- **LEAD ORGANIC AKTIF:** ada RFQ Organic Rice relatif baru.
- **VALID SPECIALTY/PREMIUM RICE:** ada shipment specialty/premium rice relevan walaupun organic belum terbukti.
- **POTENSIAL — ORGANIC FIT:** ada portfolio/listing organic tetapi shipment evidence belum cukup.
- **RICE LEAD — ORGANIC BELUM TERBUKTI:** buyer rice aktif yang bisa menjadi target new SKU.
- **PERLU VERIFIKASI:** data/entity/contact belum cukup.

## 7. Regulatory

Untuk setiap market pisahkan:
- aturan impor beras;
- organic claim/certification;
- labeling;
- importer licensing;
- phytosanitary/food clearance;
- customs/tax;
- recognition/equivalence certification body.

Jangan menyimpulkan INOFICE diterima di suatu negara hanya karena negara tersebut menerima foreign organic certification. Recognition/equivalence INOFICE harus dibuktikan secara resmi jika diperlukan.

## 8. Target Market Status

Prioritas awal:
1. Qatar
2. Saudi Arabia
3. Kuwait
4. Singapore
5. Oman
6. Malaysia

Status setelah deep research 29-Aug-2026:
- **Tier 1:** Qatar + Saudi Arabia
- **Tier 2:** Singapore + Kuwait
- **Second wave:** Oman
- Malaysia selektif

Market generic research dianggap **SUFFICIENT** untuk first-wave outreach. Fokus selanjutnya adalah buyer expansion, SKU matching, actual trade price, competitor mapping, regulatory verification, landed economics, dan commercial validation.

## 9. Metodologi Riset Mendalam

Sedapat mungkin setiap riset menggabungkan:
1. demand evidence;
2. buyer/importer evidence;
3. organic evidence;
4. specialty/premium evidence;
5. competitor variety/origin;
6. shipment price benchmark;
7. retail/wholesale price benchmark;
8. product-market fit;
9. regulatory gate;
10. landed economics;
11. contactability;
12. outreach priority.

Jangan mengulang pencarian generic buyer jika bukti sudah cukup. Setelah market terbukti, pindah ke validasi komersial.

## 10. Commercial Screening — 29-Aug-2026

Pertanyaan: **Dengan harga EXW JDN, produk mana yang benar-benar berpotensi menghasilkan transaksi?**

Kurs kerja screening sekitar Rp17.800/USD; bukan harga tetap.

### Ranking sementara
1. **Black Rice** — kandidat komersial terkuat.
2. **Premium Red Rice** — sangat kuat, terutama GCC.
3. **Pandan Wangi** — differentiated aromatic SKU.
4. **Sugar Free / Parboiled Low-GI** — promising, perlu proof lebih lanjut.
5. **White** — feasible sebagai portfolio, tetapi jangan perang commodity.
6. **Rainbow** — perlu validasi tambahan.
7. **Milk Rice** — prioritas rendah sementara.

### Kesimpulan screening
Black dan Red memiliki ruang premium paling jelas di Qatar/Saudi. Pandan Wangi menarik sebagai differentiated aromatic SKU terutama pada buyer organic/premium/aromatic. Sugar Free/Parboiled Low-GI menarik sebagai health-positioned category tetapi claim harus disubstansiasi. White sebaiknya bukan hero SKU commodity.

Retail price gap **bukan bukti final profitability**. Final feasibility membutuhkan landed cost dan buyer-side margin validation.

## 11. Freight / Landed-Cost Screening

Screening awal memakai asumsi konservatif **20.000 kg/container**.

Indikasi freight yang pernah ditemukan:
- Indonesia → Qatar sekitar US$1.050–1.250 / 20 ft → sekitar Rp935–1.113/kg.
- Jakarta → Jeddah sekitar US$1.825–2.314 / 20 ft pada quote indikatif tertentu → sekitar Rp1.624–2.060/kg.
- Jakarta → Singapore indikasi sekitar Rp41,2 juta / 20 ft pada sumber tertentu → sekitar Rp2.060/kg.

Ini **proxy, bukan quotation CIF final**.

Freight-adjusted screening menunjukkan freight laut hanya menambah sekitar Rp1–2 ribu/kg pada model 20 ton untuk market utama. Bottleneck berikutnya adalah actual destination charges, importer/distributor margin, regulatory compliance, dan actual quotation.

### Regulatory observations
**Qatar:** rice HS 1006 pada informasi tariff yang ditemukan menunjukkan tariff 0%; rice tetap food-control item dan requirements label/food clearance berlaku.

**Saudi:** HS 100630 pada sumber tariff yang ditemukan menunjukkan default duty 0%, tetapi import VAT 15% berlaku. Organic claim merupakan regulatory gate dan memerlukan dokumentasi/registration yang sesuai. Recoverable VAT jangan otomatis dianggap permanent margin cost bagi importer VAT-registered.

**Singapore:** rice adalah controlled item; importer/re-exporter/wholesaler memerlukan SFA licence. Import GST 9% berlaku; perlakuan GST harus dimodelkan sesuai status importer.

## 12. Next Research Gate

Setelah market discovery generic sufficient, fokus tahap berikutnya:

1. cari/minta freight quotation aktual untuk 20 ft dari origin JDN → Hamad, Jeddah, Singapore;
2. pisahkan origin charges dan destination charges;
3. hitung CIF/landed-cost range;
4. hitung maximum buyer purchase price yang masih memungkinkan distributor/retailer margin;
5. cocokkan buyer master per SKU;
6. cek regulatory/document requirement pada buyer/market;
7. tentukan opening offer dan negotiation floor per market/SKU;
8. susun outreach priority.

Jangan menyatakan transaksi profitable secara final hanya dari retail price gap.

## 13. Workflow Aman Update GitHub

GitHub diperlakukan sebagai repository sungguhan dan **hasil write harus diverifikasi**.

Workflow normal:
1. fetch versi/HEAD terbaru;
2. fetch file master terbaru;
3. untuk file panjang, gunakan blob SHA dan ambil blob lengkap agar tidak bekerja dari response yang terpotong;
4. modifikasi isi lengkap di sisi kerja;
5. update file menggunakan SHA terbaru jika Contents API dapat digunakan dengan aman;
6. bila perlu gunakan Git Data API: create blob → create tree berdasarkan base tree → create commit dengan parent HEAD → update branch ref;
7. setelah write, verifikasi HEAD → commit → tree/blob/file;
8. jangan menyimpulkan update berhasil hanya dari tidak adanya error atau dari response wrapper; verifikasi repository;
9. jangan membuat file UPDATE/ADDENDUM/PATCH hanya untuk mengatasi masalah teknis.

Jika terjadi conflict/409, jangan memaksa overwrite dengan SHA lama. Ambil HEAD/SHA terbaru dan ulangi workflow yang aman.

## 14. Prinsip Operasional Utama

**SETIAP AKAN MELAKUKAN APA PUN DALAM PROYEK JDN → BACA ACUAN PROYEK INI TERLEBIH DAHULU.**

Kemudian:
- mau cek **harga** → buka `HARGA-EXW-JDN.md`;
- mau cek **buyer** → buka `BUYER-VALID-POTENSIAL.md`;
- mau cek **market/prinsip riset** → baca dokumen ini dan file riset terkait yang sudah ada;
- mau cek **website** → buka master website yang sudah ada;
- mau menambah informasi buyer → update master buyer;
- mau menambah/mengubah harga → update master harga;
- mau mengubah prinsip/metodologi/acuan → update dokumen ini;
- jangan membuat catatan paralel kecuali diperintahkan.

**Acuan proyek ini adalah titik awal sebelum setiap pekerjaan, riset, update, analisis, maupun keputusan.**
