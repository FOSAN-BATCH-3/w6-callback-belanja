#  Callback Belanja

Terdapat 1 file beli.js yang berisikan function callback yang telah dibuat untuk digunakan melakukan proses pembelian.

cara pakainya adalah

```
beli(uang, objItem, callback)
```

**Uang**(number): jumlah uang yang dibawa ketika akan pergi Belanja

**objItem**(object):

- item(string): nama item yang akan dibeli
- harga(number): harga dari barang yang akan dibeli
- waktu(number): number dalam milliesecond perkiraan waktu untuk proses pembelian

**callback**(function):

- menerima 1 parameter kembalian dari proses belanja

## Release 0: Belanja

Gunakanlah Proses belanja tersebut dengan test case kalian masing-masing minimal 5 proses belanja dalam sekali jalan. misalnya: pertama beli permen setelah beli permen uang kemabaliannya dibelikan roti. begitu seterusnya sampai dengan 5 kali belanja