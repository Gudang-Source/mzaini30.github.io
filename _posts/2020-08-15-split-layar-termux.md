--- 
layout: post
title: Split layar Termux
category: termux
--- 

Jadinya seperti ini:

![Tampilan tmux](https://i.ibb.co/9n3ZvCb/Screenshot-2020-08-15-05-39-53-74-84d3000e3f4017145260f7618db1d683.png)

## Instalasi

```bash
pkg install tmux 
```

## Cara menggunakan

Jalankan `tmux`

### Split atas bawah

`^b` `"`

### Split kanan kiri

`^b` `%`

### Berpindah screen aktif

Kalau di Android, tinggal klik aja screen yang mau diaktifkan. Tapi, kalau di desktop, tekan `^b` lalu arah panahnya.

## Menutup screen yang terbuka

```bash
exit
```

## Scroll di tmux PC

Jalankan `^b` `[`
