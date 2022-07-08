# Mekanisme Peminjaman

### Minting Aset

Soup Finance akan memberi ruang baru bagi NFT untuk difinansialisasi. Setiap NFT yang didepositkan akan disimpan didalam kontrak eskrow menggunakan tanda tangan digital yang tertruktur dan akan mencetak sebuah token FRC758 ('nToken'). Pengguna akan menerima nToken yang mencerminkan suatu koleksi NFT dan dapat mengubahnya kembali menjadi NFT yang asli dengan melakukan burn pada nToken tersebut.

### nToken

nToken tidak dapat digunakan di dalam sebagai imbal hasil namun dapat digunakan didalam protokol pinjaman sebagai jaminan untuk meminjam dengan nilai floor-price NFT dijadikan sebagai patokan nilai jaminan.

**sebagai contoh:**

1. Alice memiliki NFT Meebit.
2. Alice mendepositkan NFT Meebitnya kedalam kontrak eskrow untuk memperoleh token nMeebit
3. Alice dapat menggunakan token nMeebit tersebut sebagai jaminan untuk menggunakan protokol pinjaman yang kami sediakan.
4. Alice dapat meminjam $FSN, $SOL, $ETH dll.

### Oracle

Penentapan nilai floor-price pada platform kami akan menggunakan Oracle yang terpercaya dari berbagai pasar NFT yang tersedia.

// Oracle merupakan sebuah layanan yang menyediakan informasi aktual dari luar blockchain untuk digunakan di dalam blockchain. //

### Rasio Pinjaman terhadap Nilai (LTV)

Rasio jaminan NFT dapat disesuikan berdasarkan volatilitas dan likuiditas koleksi NFT. Mengingat rendahnya likuiditas NFT, parameter LTV akan dibuka pada rasio 30% dengan ambang batas likuidasi 50% untuk memastikan tingginya slippage tidak mengganggu kualitas pool yang tersedia.
