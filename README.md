# tugas Data Karyawan yang tidak akan diubah
karyawan = (Yana,Andika,Risa,Nanda)
 
# Menampilkan data karyawan
    print(karyawan)
    
# Data transaksi penjualan
transaksi = (
    ("TRX001", "PRD001", 2),
    ("TRX002", "PRD002", 5),
    ("TRX003", "PRD003", 1),
)

# Menampilkan data transaksi
for data in transaksi:
    print(f"ID Transaksi: {data[0]}, ID Produk: {data[1]}, Jumlah: {data[2]}")
