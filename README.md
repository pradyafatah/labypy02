# Laporan Praktikum 2

## KASUS 1 : PROGRAM PEMESANAN TIKET BIOSKOP
```phython
# Program Pemesanan Tiket Bioskop

# Harga tiket
harga_reguler = 50000
harga_vip = 100000

# Input tipe tiket
tipe_tiket = input("Masukkan tipe tiket (reguler/vip): ").lower()

# Input status member
status_member = input("Apakah Anda memiliki kartu member? (ya/tidak): ").lower()

# Hitung harga tiket
if tipe_tiket == "reguler":
    total_harga = harga_reguler
elif tipe_tiket == "vip":
    total_harga = harga_vip
else:
    print("Tipe tiket tidak valid.")
    total_harga = 0

# Cek status member dan berikan diskon jika berlaku
diskon = 0.2 if status_member == "ya" else 0
harga_final = total_harga * (1 - diskon)

# Tampilkan hasil
if total_harga > 0:
    print(f"Total harga yang harus dibayar: Rp{harga_final:.2f}")

 
```
# KASUS 2 : KALKULATOR SEDERHANA
```phython
# Program Kalkulator Sederhana

# Input dua angka dan satu operator
angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))
operator = input("Masukkan operator (+, -, *, /): ")

# Hitung hasil sesuai operator
if operator == "+":
    hasil = angka1 + angka2
elif operator == "-":
    hasil = angka1 - angka2
elif operator == "*":
    hasil = angka1 * angka2
elif operator == "/":
    if angka2 != 0:
        hasil = angka1 / angka2
    else:
        hasil = "Error: Pembagian dengan nol!"
else:
    hasil = "Operator tidak valid!"

# Tampilkan hasil
print(f"Hasil: {hasil}")
