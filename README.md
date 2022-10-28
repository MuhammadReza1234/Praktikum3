## Nama = Muhammad Reza Maulana
## NIM = 312210303
## Kelas = TI.22.A3

# Latihan 1 
# Penggunaan end

  Parameter akhir dalam fungsi cetak digunakan untuk menambahkan string apa pun. Di akhir output dari pernyataan print dengan python.
  Secara default, fungsi cetak diakhiri dengan baris baru.
  Melewati spasi putih ke parameter akhir (end=' ') menunjukkan bahwa karakter akhir harus diidentifikasi oleh spasi putih dan bukan baris baru.
```
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')
```


![Screenshot (129)](https://user-images.githubusercontent.com/115542704/197797294-23da89d9-af0b-40ab-a225-407809b04cc1.png)


# Penggunaan Seperator
```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```


![Screenshot (132)](https://user-images.githubusercontent.com/115542704/197803903-c5ac84d1-5bda-446c-a55c-b227f6a8189d.png)




# String Format 
String Formatting atau Pemformatan string memungkinkan kita menyuntikkan item ke dalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation. 
```
# string format
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```


![Screenshot (131)](https://user-images.githubusercontent.com/115542704/197804071-d6fd54b5-13a1-4b61-b8ac-b3a15ac357ee.png)


# String Format 2
```
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(0, 10**1))
print('{0:>3} {1:>16}'.format(0, 10**2))
print('{0:>3} {1:>16}'.format(0, 10**3))
print('{0:>3} {1:>16}'.format(0, 10**4))
print('{0:>3} {1:>16}'.format(0, 10**5))
print('{0:>3} {1:>16}'.format(0, 10**6))
print('{0:>3} {1:>16}'.format(0, 10**7))
print('{0:>3} {1:>16}'.format(0, 10**8))
print('{0:>3} {1:>16}'.format(0, 10**9))
print('{0:>3} {1:>16}'.format(0, 10**10))
```
![Screenshot (133)](https://user-images.githubusercontent.com/115542704/197805183-31f870f2-4b99-4d2f-b28b-9d87d6445a6d.png)

# Hasil Latihan 1

![Hasil1](https://user-images.githubusercontent.com/115542704/197807033-6f5ca248-a3ca-465f-9b55-f80847d32ce5.png)



## Latihan 2

# Input Variable
Penggunaan python untuk menginput nilai variabel dengan cara
```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
```
![Screenshot (134)](https://user-images.githubusercontent.com/115542704/197808978-be493c4d-985d-4440-893e-2a6d2eaef741.png)


# Cetak Variable
Mencetak nilai kedua variabel ketika sudah di input 
```
print("variable a=",a)
print("variable b=",b)
```
![Screenshot (135)](https://user-images.githubusercontent.com/115542704/197810613-29a7a0db-4066-4783-82ac-1e0a49a6e2f9.png)


# Penggabungan Variable
Penggabungan kedua nilai Variable 
```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```
![Screenshot (134)](https://user-images.githubusercontent.com/115542704/197813586-dff1c200-7095-484a-8ca3-3dfb92b684c7.png)


# Input Variable 2
Penggunaan python untuk menginput kedua variable
```
a=int(a)
b=int(b)
```
![Screenshot (136)](https://user-images.githubusercontent.com/115542704/197814554-017054b1-2708-4a60-ab2e-513e255770e9.png)


# Konversi Nilai Variable
Mencetak kembali hasil mengkonversi nilai kedua variabel  
```
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
```
![Screenshot (136)](https://user-images.githubusercontent.com/115542704/197814795-a8b0e6db-6e20-43de-85be-d96ebbfb5836.png)

# Hasil Latihan 2

![Screenshot (137)](https://user-images.githubusercontent.com/115542704/197817527-0c1424c9-d1cb-4ae3-892e-5c688fbfb5e2.png)

# Latihan 3 Menggunakan String Format untuk membuat Belah Ketupat

![Screenshot (144)](https://user-images.githubusercontent.com/115542704/198204689-4a57ddc7-68ed-4b07-928c-adbd97645b01.png)

# Latihan 4 Luas Lingkaran
# Flowchart untuk mencari Luas Lingkaran 

![Flowchart-menghitung-luas-keliling-lingkaran-1](https://user-images.githubusercontent.com/115542704/198233052-6978bcd6-30e5-4042-ba37-48b7d8ca8acd.png)

# Membuat Program untuk Mencari Luas Lingkaran
Rumus Luas Lingkaran adalah phi * (r * r) atau phi * r² 

Rumus Keliling Lingkaran adalah 2 * phi * r
```
print('Menghitung luas dan keliling lingakaran')
print('==============================')
```
# Menginput Nilai Jari-Jari
Menginput jari jari untuk mencari luas dan keliling lingkaran
```
r = int(input('masukan jari-jari lingkaran: '))
```
# Mendeklarasikan Nilai Phi
Nilai Phi adalah 3,14 atau 22/7
```
phi = 3.14
L = phi * (r * r)
K = 2 * phi * r
```
# Mencetak Hasil Luas dan keliling Lingkaran
```
print('Luas dan keliling lingkaran dengan jari-jari {} adalah {}'.format(r, L))
```
<img width="437" alt="Screenshot (146)" src="https://user-images.githubusercontent.com/115542704/198237416-2da1eaf4-aa25-4a58-b04a-dee312ed89cd.png">

# Hasil Latihan 4 Luas Lingkaran
<img width="323" alt="Screenshot (147)" src="https://user-images.githubusercontent.com/115542704/198237674-d5751c8b-f99a-441b-9d1d-702414e4b023.png">

# =======SEKIAN TERIMAKASIH=========
