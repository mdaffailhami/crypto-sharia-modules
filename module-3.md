## 1. Smart Contract

### 1.1 Pengertian Smart Contract

Smart contract adalah **program otomatis** yang berjalan di atas blockchain. Ia akan mengeksekusi instruksi tertentu **secara otomatis** ketika kondisi yang ditentukan terpenuhi — tanpa perlu perantara.

> 📜 Disebut "**Smart Bontract**" (kontrak pintar) karena ia menggantikan peran kontrak tradisional, namun dalam bentuk kode.

### 1.2 Analogi Sederhana

Bayangkan **mesin penjual otomatis (vending machine)**. Kita masukkan uang, pilih produk, lalu mesin langsung mengeluarkan barang. Tidak perlu kasir, tidak perlu tanya-tanya.

Smart contract bekerja dengan cara yang mirip:
- Masukkan syarat (misalnya: kirim ETH ke alamat tertentu),
- Jika syarat benar, maka kontrak akan otomatis mengirim token, NFT, atau akses lainnya.

> 💡 Semua terjadi tanpa ada pihak ketiga yang mengatur.

---

### 1.3 Smart Contract vs Kontrak Tradisional

| Aspek               | Kontrak Tradisional             | Smart Contract                        |
|--------------------|----------------------------------|----------------------------------------|
| Siapa yang Menjalankan? | Manusia (notaris, pengacara, dsb) | Kode yang berjalan di blockchain       |
| Bisa dimanipulasi?  | Bisa (korupsi, penipuan, dll)   | Tidak bisa, transparan dan otomatis    |
| Biaya               | Tinggi (jasa notaris, waktu, dsb)| Relatif rendah                         |
| Kecepatan           | Lambat (perlu proses manual)     | Instan selama kondisi terpenuhi          |

---

### 1.4 Contoh Smart Contract di Dunia Crypto

#### 🔹 1. Fungible Tokens

Token crypto seperti USDT, IDRT, ARB, dll sebenarnya merupakan sebuah **Smart Contract**. 

Kita bisa melihat langsung kodingan programnya di:
https://etherscan.io/token/0xdac17f958d2ee523a2206206994597c13d831ec7

Di sana kita bisa temukan fungsi seperti:
- `transfer()`: untuk mengirim token
- `balanceOf()`: untuk mengecek saldo
- `approve()`: untuk memberikan izin akses ke dompet lain

#### 🔹 2. NFT (Non-Fungible Token)

NFT (Token yang setiap unitnya itu unik) seperti gambar, tiket, sertifikat, dll juga dibangun dari smart contract.

#### 🔹 3. DEX (Decentralized Exchange)

Platform seperti **Uniswap** dibangun sepenuhnya dari **Smart Contract**. Tidak ada server pusat — semua logika seperti swap token, penambahan likuiditas, dan perhitungan harga dilakukan otomatis menggunakan **Smart Contract**.

---
---


## 2. Konsensus Blockchain

### 2.1 Pengertian Konsensus

Dikarenakan **Blockchain** itu bersifat **terdesentralisasi**, artinya tidak ada satu pihak pusat pun yang menentukan kebenaran data. Maka dari itu dibutuhkan lah yang namanya **mekanisme konsensus** — yaitu sebuah **cara untuk mencapai kesepakatan bersama** antar semua node (komputer) dalam jaringan tentang data mana yang valid.

> 📖 Tanpa konsensus, blockchain akan berantakan karena semua node bisa saja menyimpan versi data yang berbeda.
> Konsensus adalah **pondasi utama blockchain**. Tanpa adanya konsensus, maka data yang tercatat di blockchain tidak akan bisa dipercaya dan tidak akan punya arti.
> ✅ Dengan adanya konsensus, kita tidak butuh bank, notaris, atau pihak ketiga untuk menjaga keabsahan data.

---

### 2.2 Analogi Sederhana

Bayangkan kita sedang bermain arisan dengan teman-teman, tapi tanpa adanya ketua arisan. Setiap kali ada yang menang, semua anggota harus **setuju** siapa pemenangnya, berapa jumlah uangnya, dan siapa yang akan dapat giliran selanjutnya.  
Kalau tidak ada kesepakatan (konsensus), maka sistem arisan itu tidak akan berjalan.

Begitu juga di blockchain — semua transaksi atau blok baru harus **disetujui oleh mayoritas peserta jaringan** agar bisa dianggap valid.

---

### 2.3 Jenis-Jenis Konsensus

Berikut ini beberapa algoritma konsensus yang "umum" digunakan di dalam blockchain:

#### 🔹 1. Proof of Work (PoW)
Digunakan oleh Bitcoin.

- Setiap Node (Miner) diberikan tantangan untuk memecahkan soal teka-teki matematika rumit.
- Siapa yang berhasil duluan, berhak menambahkan blok baru dan mendapat reward.
- Butuh energi besar, tapi sangat aman.

> ⚒️ Ibaratnya seperti lomba tebak angka. Siapa yang paling cepat menebak, maka dia lah yang menang.

#### 🔹 2. Proof of Stake (PoS)
Digunakan oleh Ethereum sejak 2022.

- Node harus mengunci sejumlah token (Staking).
- Semakin banyak dan lama staking, semakin besar peluang dipilih untuk menambah blok baru.
- Lebih hemat energi dibanding PoW.

> 💰 Ibarat arisan: yang paling sering hadir dan menyetor uang, lebih dipercaya jadi pencatat arisan.

#### 🔹 3. Delegated Proof of Stake (DPoS)
Contoh: EOS, TRON.

- Pemilik token memilih sekelompok "wakil" untuk menjalankan validasi.
- Lebih cepat dan efisien, tapi sedikit lebih terpusat.

> 🗳️ Seperti pemilihan ketua kelas. Satu orang mewakili keputusan bersama.

---

### 2.4 Mengapa Konsensus Penting?

- Menjaga kepercayaan antar peserta jaringan tanpa perlu mengenal satu sama lain.
- Memastikan data tidak bisa dipalsukan atau diubah sepihak.
- Mencegah double-spending (transaksi ganda) pada aset digital.

---
---

## 3. Layer 1, Layer 2, dan Layer 3

### 3.1 Apa Itu “Layer” dalam Dunia Blockchain?

Istilah **layer** mengacu pada struktur bertingkat dalam arsitektur blockchain, di mana setiap lapisan memiliki fungsi dan tanggung jawab tertentu.  
Tujuannya adalah untuk **meningkatkan skalabilitas**, efisiensi, dan fungsionalitas blockchain.

> Setiap layer bekerja sama untuk membuat ekosistem blockchain lebih cepat, terjangkau, dan mudah digunakan.

---

### 3.2 Layer 1 (L1) – Dasar Utama Blockchain

Layer 1 adalah **blockchain utama itu sendiri** — tempat semua transaksi diproses dan dicatat secara langsung.

Contoh:
- Bitcoin
- Ethereum
- Solana
- SUI

Ciri-ciri:
- Menyediakan keamanan dan desentralisasi.
- Tapi sering lambat dan mahal ketika terlalu padat (contoh: Ethereum saat ramai bisa mahal gas fee (biaya admin)-nya).

---

### 3.3 Layer 2 (L2) – Solusi Skalabilitas di Atas Layer 1

Layer 2 adalah **blockchain yang dibangun di atas Layer 1**, biasanya tujuannya adalah untuk mempercepat transaksi dan menurunkan biaya, tanpa mengorbankan keamanan.

Contoh:
- Arbitrum
- Optimism
- zkSync
- Lightning Network (untuk Bitcoin)

Ciri-ciri:
- Transaksi diproses di luar L1, lalu hasilnya disimpan ke L1.
- Lebih cepat dan murah.

> 🔁 Ibaratnya seperti jalur tol tambahan di atas jalan utama yang macet.

---

### 3.4 Layer 3 – Aplikasi dan Infrastruktur

Layer 3 mengacu pada **layer aplikasi**, seperti:
- dApps (decentralized apps)
- Wallet
- Game Web3

Layer ini juga bisa mengacu pada **jembatan antar-blockchain (bridge)** atau **protokol komunikasi lintas jaringan**.

---
---

## 4. Hashing

### 4.1 Pengertian Hash

**Hash** adalah hasil dari proses kriptografi yang mengubah input (data apapun) menjadi deretan karakter unik dengan panjang tetap.

- Input bisa berupa: teks, file, transaksi, blok, dll.
- Output disebut sebagai **hash**, biasanya berupa string heksadesimal.

---

### 4.2 Contoh Hashing Sederhana

Sebenarnya ada banyak sekali algorithma hashing, tapi kali ini kita coba menggunakan salah satu yang paling umum yaitu **SHA256**.

- Original Text : _**Crypto Sharia**_
- Hashed Text   : _0f42dde232d16a1a7120913b5573d9a200263c23551b896e15bcabab90328bea_

Setiap perubahan (Meski kecil) yang terjadi pada teks originalnya, hasil hashing-nya akan berubah total.

- Original Text : _**crypto Sharia**_ (Huruf "C"-nya huruf kecil)
- Hashed Text   : _0fa73297b20bf994c7e774771a3e1d722721cf0c20379113ef0e861dbbbec9e0_

Kalau kalian tertarik mau nyoba-nyoba, bisa langsung aja cuss ke link berikut:

[https://tools.keycdn.com/sha256-online-generator](https://tools.keycdn.com/sha256-online-generator)

---

### 4.3 Perbedaan Hashing dengan Enkripsi

Banyak orang yang berpikir kalau **hashing** dengan **enkripsi** itu sama, padahal sebenarnya berbeda.

**Hashing** dan **enkripsi** sama-sama mengubah data menjadi bentuk lain, tapi tujuannya berbeda:

| Aspek            | **Hashing**                                              | **Enkripsi**                                             |
|------------------|----------------------------------------------------------|----------------------------------------------------------|
| Tujuan           | Menjaga integritas data (apakah data berubah)            | Menjaga kerahasiaan data                                 |
| Bisa dikembalikan? | ❌ Tidak bisa dikembalikan ke bentuk asli                | ✅ Bisa dikembalikan ke bentuk asli dengan kunci          |
| Contoh Algoritma | SHA-256, MD5                                             | AES, RSA                                                  |
| Penggunaan       | Verifikasi data, tanda tangan digital, blockchain       | Pesan rahasia, komunikasi terenkripsi, data sensitif     |
| Output           | Panjang tetap, unik untuk setiap input                   | Bisa bervariasi tergantung input dan algoritma           |

> 🔑 **Simpelnya**:  
> - Hashing: Data yang sudah hashed tidak akan bisa dikembalikan ke data originalnya.
> - Enkripsi: Data yang sudah dienkripsi bisa saja dikembalikan ke data originalnya (Dekripsi) selama kita punya kuncinya.

---

### 4.4 Fungsi Hash dalam Blockchain

Blockchain sangat bergantung pada hash untuk:

- 🔐 **Keamanan** data (data rahasia, tidak bisa dibaca langsung)
- 🔄 **Integritas** data (sekecil apa pun perubahan input, hash akan berubah drastis)
- 🔗 **Menghubungkan blok** (setiap blok menyimpan hash dari blok sebelumnya)

Setiap blok di dalam blockchain menyimpan:
- Daftar transaksi
- Timestamp
- Hash dari blok sebelumnya
- Hash-nya sendiri

Inilah yang membuat blockchain **tidak bisa dimodifikasi**:
- Kalau isi satu blok saja diubah, maka hash-nya akan berubah total,
- Maka semua blok setelahnya juga tidak akan valid (karena merujuk ke hash yang lama),
- Butuh kekuatan komputasi yang luarrr biasaaaa untuk mengubah semuanya (Which is most likely impossible).

---
---

Berikut adalah bagian **Tokenomic** dalam format raw Markdown, disusun untuk orang awam dengan analogi dan contoh:

---

## 5. Tokenomic: Ekonomi dalam Dunia Token

**Tokenomic** adalah gabungan dari kata *token* dan *economics*. Artinya, tokenomic membahas bagaimana token diciptakan, dibagikan, digunakan, dan dikelola dalam suatu proyek crypto.

> Tokenomic adalah fondasi ekonomi dari setiap token. Dengan memahami tokenomic, kita tidak hanya ikut-ikutan beli token, tapi tahu **kenapa** token itu bisa **punya nilai** atau justru **berisiko**.

Bayangkan token seperti **koin di taman bermain**. Setiap taman bermain (proyek blockchain) punya koinnya sendiri. Tapi:

* Siapa yang mencetak koinnya?
* Siapa yang dapat koin duluan?
* Apa kegunaan koinnya?
* Berapa banyak jumlah maksimalnya?

Semua ini diatur oleh **tokenomic**.

---

### 5.1 Elemen Penting dalam Tokenomic

#### 🔹 1. **Total Supply**

   > Jumlah maksimum token yang akan pernah ada.
   > Contoh: Bitcoin punya total supply 21 juta BTC. Tidak bisa dicetak lebih.

#### 🔹 2. **Initial Distribution**

   > Bagaimana token pertama kali dibagi saat peluncuran proyek.
   > Contoh: 40% untuk tim, 30% untuk investor awal, 30% untuk komunitas.

#### 🔹 3. **Utility (Kegunaan Token)**
   Token bisa dipakai untuk:

   * Biaya transaksi
   * Voting
   * Reward untuk holders (pemegang token)
   * Akses fitur premium
   * dll

#### 🔹 4. **Vesting Schedule**

   > Jadwal kapan token yang dikunci akan dilepas.
   > Ini mencegah tim proyek langsung menjual semua token dan kabur (*rug pull*).

#### 🔹 5. **Inflasi & Deflasi**

   * **Inflasi**: Token terus dicetak → supply bertambah → kelangkaan berkurang → nilai bisa turun
   * **Deflasi**: Ada mekanisme pembakaran token (burn) → supply berkurang → semakin langka → nilai bisa naik

#### 🔹 6. **Incentives**

   Insentif dalam dunia crypto berarti hadiah atau motivasi supaya orang mau:
   * Memegang token
   * Menggunakan platform
   * Ikut berkontribusi ke ekosistem
   * dll

---

### 5.2 Kenapa Tokenomic Penting?

Karena tokenomic menentukan **kelangsungan hidup** sebuah proyek. Kalau semua token dimiliki tim dan investor, lalu dijual ke publik tanpa kontrol → harga bisa anjlok.

Tokenomic yang sehat harus mempertimbangkan:

* Keseimbangan antara supply & demand
* Keadilan distribusi
* Insentif jangka panjang untuk komunitas

---

### 5.3 Contoh Perbandingan Tokenomic

| Proyek       | Supply Maksimum  | Sistem Burn | Vesting | Utility                    |
| ------------ | ---------------- | ----------- | ------- | -------------------------- |
| Bitcoin      | 21 juta BTC      | Tidak ada   | Tidak   | Uang digital               |
| Ethereum     | Tidak terbatas   | Ada         | Tidak   | Bayar gas + smart contract |
| BNB          | 200 juta → turun | Ya          | Ada     | Diskon fee & voting        |
| "_Shitcoin_"   | Tidak jelas      | Tidak ada   | Tidak   | Hanya spekulasi            |

---
---

## 6. Whitepaper

### 6.1 Pengertian Whitepaper

Whitepaper adalah dokumen resmi dari sebuah proyek crypto yang menjelaskan:
- Masalah yang ingin diselesaikan,
- Solusi yang ditawarkan,
- Teknologi yang digunakan,
- Rencana pengembangan (roadmap),
- Tokenomic (alokasi dan distribusi token),
- Tim pengembang.

> 📄 Whitepaper adalah “proposal” kepada publik yang ingin tahu apa sih tujuan dan mekanisme kerja dari proyek itu.

### 6.2 Pentingnya Whitepaper

- Sebagai bahan analisa sebelum berinvestasi
- Memberi gambaran apakah proyek punya visi yang jelas dan realistis
- Menunjukkan apakah proyek benar-benar punya use-case atau cuma “hype” semata

### 6.3 Contoh Whitepaper

- **Bitcoin** : [https://bitcoin.org/bitcoin.pdf](https://bitcoin.org/bitcoin.pdf)
- **Ethereum**: [https://ethereum.org/en/whitepaper/](https://ethereum.org/en/whitepaper/)

---
---

## 7. DAO (Decentralized Autonomous Organization)

### 7.1 Pengertian DAO

DAO adalah organisasi yang berjalan secara otomatis dan terbuka berdasarkan smart contract. Tidak ada CEO, bos, atau manajer — semua keputusan dilakukan lewat **voting oleh komunitas**.

> 🧠 DAO = organisasi berbasis kode dan dijalankan oleh komunitas sehingga tidak dikontrol oleh suatu pihak terpusat, .

### 7.2 Contoh DAO

- **MakerDAO** – komunitas yang mengelola stablecoin DAI
- **Aragon** – platform untuk membangun DAO sendiri
- **Uniswap DAO** – komunitas yang mengatur perkembangan protokol Uniswap

### 7.3 Cara Kerja

Biasanya setiap orang yang punya token (misal **UNI** untuk **Uniswap**) bisa mengajukan proposal dan ikut voting. Semakin banyak token, semakin besar hak suaranya.

---
---

## 8. Bridge

### 8.1 Pengertian Bridge

Bridge adalah jembatan yang menghubungkan dua jaringan blockchain yang berbeda. Misalnya:
- Dari Ethereum ke Arbitrum

Karena setiap blockchain punya sistem dan token yang berbeda, maka **Bridge** dibutuhkan agar users bisa:
- Memindahkan token antar jaringan,
- Berinteraksi dengan dApps di ekosistem berbeda.

> 🌉 Bridge membuat dunia crypto lebih saling terhubung.

### 8.2 Cara Kerja Sederhana

Misal kita kirim ETH dari Ethereum ke Arbitrum:
- **ETH** kita “dikunci” di Ethereum
- Lalu versi “tiruan”-nya (wrapped **ETH** / **wETH**) diterbitkan di Arbitrum

Kalau kita mau mengambil balik **ETH** kita yang terkunci itu, maka kita perlu menghanguskan (_burn_) **wETH** punya kita itu

---
---

## 9. Apa Itu Swap?

### 9.1 Pengertian Swap

Swap adalah proses menukar satu aset crypto ke aset lain secara instan. Biasanya dilakukan langsung dari wallet kita, tanpa perantara seperti CEX (_Centralized Exchange_).

Contoh:
- Swap ETH ke USDC di Uniswap
- Swap USDC ke SOL di Raydium

> 🔁 Swap = tukar menukar token secara langsung via smart contract

### 9.2 Prosesnya

1. Kita pilih dua token yang ingin ditukar
2. Smart contract akan mencari harga terbaik dari liquidity pool
3. Jika setuju, kita tinggal klik "Swap", maka token akan langsung bertukar

---
---

## 10. Macam-Macam Investasi di Dunia Crypto

### 10.1 Fungible Tokens

- **Bitcoin**
- **Ether**
- **Solana**
- **SUI**
- **Dogecoin**
- dll

### 10.2 NFT

Aset digital unik berbentuk:
- Gambar seni (art)
- Sertifikat, tiket, item game
- dll

### 10.3 DeFi

- **Staking**: Mengunci aset crypto untuk mendapatkan _reward_ 
- **Providing Liquidity**: Menyediakan likuiditas untuk mendapatkan _reward_
- dll

### 10.5 Launchpad & Presale
 
Berinvestasi di proyek crypto yang masih awal

> Risiko tinggi, tapi potensi reward besar

### 10.6 Tokenized Real World Asset

Aset di dunia nyata yang ditokenisasi, seperti:
- Emas: **PAXG**
- Saham: **NVDAx**, **TSLAx**, **MSFTx**, **GOOGLx**
- dll
