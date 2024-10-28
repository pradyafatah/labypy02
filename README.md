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
```
## Flowchart
### Hasil Flowchart dari kalkulator sederhana
* (https://drive.google.com/file/d/1gfbKNvrkyFCih-75mY8iXWKneiaZAgPM/view?usp=drive_link)
### Hasil dari flowchart pemesanan tiket bioskop
* (https://drive.google.com/file/d/1n3snSiSYd6RM_T43Qw9dCDwG993oEtAt/view?usp=drive_link)

## Screenshot Hasil Eksekusi Program
### Pembelian tiket bioskop
(![Cuplikan layar 2024-10-27 225517](https://github.com/user-attachments/assets/210cd88d-71e5-4d10-a64d-fee39afbe456)
#### Hasil
(![Cuplikan layar 2024-10-27 225456](https://github.com/user-attachments/assets/05432099-8f5f-4ee5-b856-740eec60199a)
## Kalkulator sederhana
(![Cuplikan layar 2024-10-27 224525](https://github.com/user-attachments/assets/e05f2de7-8f17-4665-85f7-f6b67b7548e9)
#### Hasil
(![image](https://github.com/user-attachments/assets/88f30ee6-7e3f-4e70-a3f7-b575c81e605b)

(Terimakasih :)
