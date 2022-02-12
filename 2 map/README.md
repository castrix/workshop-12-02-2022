# workshop-12-02-2022

# Challenge

## 1 menghitung harga jual

Ratna ingin menjual beberapa produk, pada produk-produk tersebut terdapat informasi mengenai biaya produksi dan laba yang ingin dia dapatkan, tambahkan informasi **harga jual** berdasarkan penjumlahan dari biaya produksi dan laba yang diinginkan

```
const produk = [
  {
    nama: "Pisang Goreng",
    biayaProduksi: 1000,
    laba: 4000
  },
  {
    nama: "Es Teh",
    biayaProduksi: 100,
    laba: 1900
  },
  {
    nama: "Bakwan",
    biayaProduksi: 200,
    laba: 800
  }
]
```

output yang diharapkan adalah:

```
const produk = [
  {
    nama: "Pisang Goreng",
    biayaProduksi: 1000,
    laba: 4000,
    hargaJual: 5000
  },
  {
    nama: "Es Teh",
    biayaProduksi: 100,
    laba: 1900,
    hargaJual: 2000
  },
  {
    nama: "Bakwan",
    biayaProduksi: 200,
    laba: 800,
    hargaJual: 1000
  }
]
```

## konversi ke mata uang rupiah

Konversikan output di atas ke dalam mata uang rupiah

```
const produk = [
  {
    nama: "Pisang Goreng",
    biayaProduksi: "Rp. 1000",
    laba: "Rp. 4000",
    hargaJual: "Rp. 5000"
  },
  {
    nama: "Es Teh",
    biayaProduksi: "Rp. 100",
    laba: "Rp. 1900",
    hargaJual: "Rp. 2000"
  },
  {
    nama: "Bakwan",
    biayaProduksi: "Rp. 200",
    laba: "Rp. 800",
    hargaJual: "Rp. 1000"
  }
]
```