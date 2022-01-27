# assignment 03
Terdapat kode Python berikut ini yang akan digunakan.
```python
import html
char1 = html.unescape('&#x25FB;')
char2 = html.unescape('&#x25FC;')

NIM = '10219093'
for x in NIM:
  n = int(x, 10)
  s = ''
  for i in range(n):
    s += char
  print(n, ':', s, sep='')
```

## question 1
Ganti nilai variabel NIM dengan data Anda, jalankan kode yang diberikan, dan tampilkan hasilnya.

### anwser 1
Hasil kode di atas adalah
```
Traceback (most recent call last):
  File "HelloWorld.py", line 10, in <module>
    s += char
NameError: name 'char' is not defined

tested on
https://onecompiler.com/python/3xrkmrxp4
```

## question 2
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char1`, jalankan dan tampilkan hasilnya.

### anwser 2
Hasil modifikasi kode di atas adalah
```
1:◻
0:
2:◻◻
1:◻
9:◻◻◻◻◻◻◻◻◻
0:
9:◻◻◻◻◻◻◻◻◻
3:◻◻◻

tested on
https://onecompiler.com/python/3xrkmvsu9
```

## question 3
Ganti nilai variabel NIM dengan data Anda, modifikasi kode yang diberikan di atas dengan `s += char2`, jalankan dan tampilkan hasilnya.

### anwser 3
Hasil modifikasi kode di atas adalah
```
1:◼
0:
2:◼◼
1:◼
9:◼◼◼◼◼◼◼◼◼
0:
9:◼◼◼◼◼◼◼◼◼
3:◼◼◼

tested on
https://onecompiler.com/python/3xrkmye2p
```

## question 4
Jelaskan dengan singkat hal yang dihasillkan oleh kode yang diberikan.

### answer 4
Kode di atas berfungsi untuk
+ ..
Pada setiap NIM diidentifikasikan dengan kotak hitam dan kotak putih
+ ..
