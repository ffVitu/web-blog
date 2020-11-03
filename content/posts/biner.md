---
title: "Biner"
date: 2020-11-01T18:21:45+07:00
draft: false
toc: false
images:
tags: 
  - Binner
---

## Pengertian Biner

---

Bilangan Biner merupakan bilangan yang ditulis dengan dua simbol yaitu 0 dan 1 yang biasa disebut dengan basis 2.

contoh nilai biner

| Biner| Decimal|
| :--: |  :--:  |
| 0000 |   0    |
| 0001 |   1    |
| 0010 |   2    |
| 0011 |   3    |
| 0100 |   4    |
| 0101 |   5    |
| 0110 |   6    |
| 0111 |   7    |
| 1000 |   8    |
| 1001 |   9    |
| 1010 |   10   |
| 1011 |   11   |
| 1100 |   12   |
| 1101 |   13   |
| 1110 |   14   |
| 1111 |   15   |
| Etc.|  Etc. |

## Contoh

---

1. 1001110101
2. 1110011000
3. 010101110

## konversi Biner ke Desimal

---

Desimal merupakan bilangan yang ditulis dengan delapan simbol yaitu 0 hingga 9 yang biasa disebut dengan basis 10.

rumus untuk mengkorversi biner ke desimal :

![Biner2Decimal](/picture/biner2decimal.png)

K = nilai biner(0/1)

n = nilai ke- (dihitung dari kanan dan dimulai dari 0)

contoh :

↓ 1010 ↓
![contoh](/picture/cthdec.png)

![contoh](/picture/cthdec1.png)

![contoh](/picture/cthdec2.png)

![contoh](/picture/cthdec3.png)

kemudian seluruhnya dijumlahkan

![contoh](/picture/cthdec4.png)

### 1001110101[2]

1001110101 jadi, 512 + 0 + 0 + 64 + 32 + 16 + 0 + 4 + 0 + 1 = **_629_**

### 1110011000[2]

1110011000 jadi, 512 + 256 + 128 + 0 + 0 + 16 + 8 + 0 + 0 + 0 = **_920_**

### 010101110[2]

010101110 jadi, 0 + 128 + 0 + 32 + 0 + 8 + 4 + 2 + 0 = **_174_**

## Konversi Biner ke Oktal

---

Oktal merupakan bilangan yang ditulis dengan delapan simbol yaitu 0 hingga 9 yang biasa disebut dengan basis 8.

- Kelompokkan biner menjadi 3 bilangan perkelompok
- Ubah biner tersebut menjadi desimal dengan metode yang sama seperti konversi biner ke desimal
- Nilai tidak dijumlahkan

Contoh :

110010 → 110 010 → 6, 2 → 62[8]

### 1001110101[2]

1001110101 jadi, 1 001 110 101 → 1, 1, 6, 5 → **_1165_**

### 1110011000[2]

1110011000 jadi, 1 110 011 000 → 1, 6, 3, 0 → **_1630_**

### 010101110[2]

010101110 jadi, 010 101 110 → 2, 5, 6 → **_256_**

## Konversi Biner ke Hexa

---

hexa merupakan bilangan yang ditulis dengan delapan simbol yaitu 0 hingga 9 dan A hingga F yang biasa disebut dengan basis 16.

- Kelompokkan biner menjadi 4 bilangan perkelompok
- Ubah biner tersebut menjadi desimal dengan metode yang sama seperti konversi biner ke desimal
- Nilai tidak dijumlahkan
- Ubah nilai desimal tersebut lebih dari 9 akan diubah menjadi alfabet yang dimulai dari A untuk nilai 10 hingga F untuk nilai 15

Contoh :

10101101 → 1010 1101 → 10, 13 → A, D → AD

### 1001110101[2]

1001110101 jadi, 10 0111 0101 → 2, 7, 5 → **_275_**

### 1110011000[2]

1110011000 jadi, 11 1001 1000 → 3, 9, 8 → **_398_**

### 010101110[2]

010101110 jadi, 0 1010 1110 → 0, 10, 14 → 0, A, E → **_AE_**