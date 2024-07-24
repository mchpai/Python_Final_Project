# Python Final Project
Data yang digunakan dalam Final Project ini merupakan data yang bukan sesungguhnya atau data yang dipakai hanya untuk bahan pembelajaran dalam dunia kerja nantinya.

## Deskripsi
Dalam portfolio ini, aplikasi yang digunakan yaitu pada aplikasi jupiter notebook untuk menjalankan bahasa pemograman python untuk mencari jawaban dari setiap data yang ingin di analisis.

## Dataset
### order_detail:		
- id -	angka unik dari order / id_order
- customer_id	-	angka unik dari pelanggan
- order_date	-	tanggal saat dilakukan transaksi
- sku_id	-	angka unik dari produk (sku adalah stock keeping unit)
- price	-	harga yang tertera pada tagging harga
- qty_ordered	-	jumlah barang yang dibeli oleh pelanggan
- before_discount	-	nilai harga total dari produk (price * qty_ordered)
- discount_amount	-	nilai diskon product total
- after_discount	-	nilai harga total produk ketika sudah dikurangi dengan diskon
- is_gross	-	menunjukkan pelanggan belum membayar pesanan
- is_valid	-	menunjukkan pelanggan sudah melakukan pembayaran
- is_net	-	menunjukkan transaksi sudah selesai
- payment_id	-	angka unik dari metode pembayaran

### sku_detail:		
- id	-	angka unik dari produk (dapat digunakan untuk key saat join)
- sku_name	-	nama dari produk
- base_price	-	harga barang yang tertera pada tagging harga / price
- cogs	-	cost of goods sold / total biaya untuk menjual 1 produk
- category	-	kategori produk

### customer_detail:		
- id	-	angka unik dari pelanggan
- registered_date	-	tanggal pelanggan mulai mendaftarkan diri sebagai anggota

### payment_detail:		
- id	-	angka unik dari metode pembayaran
- payment_method	-	metode pembayaran yang digunakan

## Lisensi
Kamu dapat menggunakan Dataset ini untuk membangun dan membuat praktekmu dalam skill python
