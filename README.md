### Nama  :  Uswatun Hasanah 
### Nim   :  312210343
### Kelas :  TI.22.A.3

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Python String|[Click Here](#Python-String)|
|2|Latihan 1|[Click Here](#Latihan-1)|
|3|Latihan 2|[Click Here](#Latihan-2)|

### Python String
- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
- Membuat string semudah memberi nilai pada sebuah variabel.

### Latihan1

![WhatsApp Image 2023-01-17 at 00 11 16](https://user-images.githubusercontent.com/115516474/212733857-2e1d1668-d7da-4f86-8bb5-8d3b4eaafaee.jpeg)


Penjelasan Latihan 1
Untuk menghitung jumlah karakter, gunakan fungsi `len().`

```# Menghitung jumlah karakternya
print(len(txt))
```

Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku `[ ]` dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY 
dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan index [-1]. Sedangkan untuk mengambil 
karakter index ke-2 sampai ke-4, gunakan index [2:5].

```
# Mengambil karakter terakhir
print(txt[-1])
# Mengambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])
```

Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang
baru atau paling banyak kemunculan.

Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).

```
# Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))
```

Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().

```
# Mengubah text menjadi huruf besar
print(txt.upper())
# Mengubah text menjadi huruf kecil
print(txt.lower())
```

Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace().

```
# Mengganti karakter H dengan karakter J
print(txt.replace("H", "J"))
print()
```
