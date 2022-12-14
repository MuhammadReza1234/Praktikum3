# Nama   = Muhammad Reza Maulana
# NIM    = 312210303
# Kelas  = TI.22.A3

# Latihan 1 

## Penggunaan end

Parameter end berfungsi untuk mengganti karakter terakhir bawaan yang dicetak di layar. Jadi secara bawaan, setiap kali kita memanggil fungsi print() untuk mencetak sesuatu, python akan mencetak karakter ganti baris ( ) di setiap output.

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


## Penggunaan Seperator
sep adalah pemisah (separator) yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.
```
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
![Screenshot (132)](https://user-images.githubusercontent.com/115542704/197803903-c5ac84d1-5bda-446c-a55c-b227f6a8189d.png)

## String Format 
String formatting pada python adalah satu proses memasukkan atau menyisipkan variabel atau nilai ke dalam template string yang telah ditentukan
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


## String Format 2
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

## Hasil Latihan 1

![Hasil1](https://user-images.githubusercontent.com/115542704/197807033-6f5ca248-a3ca-465f-9b55-f80847d32ce5.png)



# Latihan 2

## Input Variable
Penggunaan python untuk menginput nilai variabel dengan cara
```
a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
```
![Screenshot (134)](https://user-images.githubusercontent.com/115542704/197808978-be493c4d-985d-4440-893e-2a6d2eaef741.png)


## Cetak Variable
Mencetak nilai kedua variabel ketika sudah di input 
```
print("variable a=",a)
print("variable b=",b)
```
![Screenshot (135)](https://user-images.githubusercontent.com/115542704/197810613-29a7a0db-4066-4783-82ac-1e0a49a6e2f9.png)


## Penggabungan Variable
Penggabungan kedua nilai Variable 
```
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))
```
![Screenshot (134)](https://user-images.githubusercontent.com/115542704/197813586-dff1c200-7095-484a-8ca3-3dfb92b684c7.png)


## Input Variable 2
Penggunaan python untuk menginput kedua variable
```
a=int(a)
b=int(b)
```
![Screenshot (136)](https://user-images.githubusercontent.com/115542704/197814554-017054b1-2708-4a60-ab2e-513e255770e9.png)


## Konversi Nilai Variable
Mencetak kembali hasil konversi nilai kedua variabel  
```
print("hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}+{0}=%d".format(a,b) %(a/b))
```
![Screenshot (136)](https://user-images.githubusercontent.com/115542704/197814795-a8b0e6db-6e20-43de-85be-d96ebbfb5836.png)

## Hasil Latihan 2

<img width="181" alt="reza10" src="https://user-images.githubusercontent.com/115516607/198473945-959b8997-e43e-43a8-a42b-a7562956674f.png">


# Latihan 3 Menggunakan String Format untuk membuat Belah Ketupat

<img width="692" alt="reza11" src="https://user-images.githubusercontent.com/115516607/198474429-5a1ab7fe-fc53-49fb-a083-7b1ef1df1ec0.png">

# Latihan 4 Luas dan keliling Lingkaran

## Flowchart untuk mencari Luas dan keliling  Lingkaran 

![Flowchart-menghitung-luas-keliling-lingkaran-1](https://user-images.githubusercontent.com/115542704/198233052-6978bcd6-30e5-4042-ba37-48b7d8ca8acd.png)

## Membuat Program untuk Mencari Luas dan keliling Lingkaran
Rumus Luas Lingkaran adalah phi * (r * r) atau phi * r?? 

Rumus Keliling Lingkaran adalah 2 * phi * r
```
print('Menghitung luas dan keliling lingakaran')
print('==============================')
```
## Menginput Nilai Jari-Jari
Menginput jari jari untuk mencari luas dan keliling lingkaran
```
r = int(input('masukan jari-jari lingkaran: '))
```
## Mendeklarasikan Nilai Phi
Nilai Phi adalah 3,14 atau 22/7
```
phi = 3.14
L = phi * (r * r)
K = 2 * phi * r
```
## Mencetak Hasil Luas dan keliling Lingkaran
```
print('Luas lingkaran dengan jari-jari {} adalah {}'.format(r, L))
print('Keliling lingkaran dengan jari-jari {} adalah {}'.format(r, K))
```
<img width="437" alt="Screenshot (146)" src="https://user-images.githubusercontent.com/115542704/198237416-2da1eaf4-aa25-4a58-b04a-dee312ed89cd.png">

## Hasil Latihan 4 Luas dan keliling Lingkaran

<img width="321" alt="reza13" src="https://user-images.githubusercontent.com/115516607/198475104-99ad5042-3f09-4d90-8ef9-785d16a16714.png">

# =======SEKIAN TUTORIAL DARI SAYA TERIMAKASIH========
