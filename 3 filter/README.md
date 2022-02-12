# workshop-12-02-2022

# Challenge

Ardi ingin membuat laporan tentang penjualan handphone hari ini. Data yang di miliki saat ini adalah:

```
const phone = [
  {
    brand: "Xiaomi",
    seri: "X6",
    terjual: true
  },
  {
    brand: "Realme",
    seri: "A8",
    terjual: true
  },
  {
    brand: "Iphone",
    seri: "13",
    terjual: false
  },
  {
    brand: "Iphone",
    seri: "12",
    terjual: false
  }
]
```

## 1 filterlah produk handphone yang terjual

output yang diharapkan:

```
[
  {
    brand: "Xiaomi",
    seri: "X6",
    terjual: true
  },
  {
    brand: "Realme",
    seri: "A8",
    terjual: true
  }
]
```

## 2 filterlah produk handphone yang belum terjual

output yang diharapkan:

```
[
  {
    brand: "Iphone",
    seri: "13",
    terjual: false
  },
  {
    brand: "Iphone",
    seri: "12",
    terjual: false
  }
]
```