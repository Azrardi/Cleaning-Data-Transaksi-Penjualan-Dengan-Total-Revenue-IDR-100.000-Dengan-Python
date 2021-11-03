# menyiapkan-data-transaksi-penjualan-dengan-total-revenue-IDR-100.000
SELECT kode_pelanggan, nama_produk, qty, harga, qty*harga AS total
FROM tr_penjualan
WHERE qty*harga >= 100000
ORDER BY total DESC;
