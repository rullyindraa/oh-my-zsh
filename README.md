# oh-my-zsh

## Apa itu Shell dan Zsh?

**Shell** adalah salah satu jenis program asli sistem operasi (seringnya merupakan program yang terpisah dari inti sistem operasi) yang menyediakan komunikasi langsung antara pengguna dan sistem operasi.

**Zsh (Z shell)** adalah salah satu shell untuk Unix yang merupakan pengembangan dari Bourne shell (sh). Beberapa peningkatan fiturnya antara lain ```cd completion```, ```git completion```, ```path expansion```, dll.

## Apa itu Oh-My-Zsh?

**Oh-My-Zsh** adalah sebuah framework untuk konfigurasi Zsh yang dikembangkan oleh Robby Russel. Dengan Oh My Zsh, terminal yang menjalankan Zsh menjadi lebih keren karena dilengkapi dengan functions, helpers, plugins, dan themes.

## Install Oh-My-Zsh sekarang

Ada dua cara untuk menginstall Oh-My-Zsh: 

1. Via curl
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

2. Via wget
```
sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"
```

## Ganti Tema Oh-My-Zsh

* Cari file `.zshrc` dengan cara mengetik perintah pada folder home:
```
ls -a
```
* Edit `ZSH-THEME` pada file `.zshrc` dengan perintah:
```
nano .zshrc
```
* Contohnya, saya mengganti tema  defaultnya dengan:
```
ZSH_THEME="cloud"
```


Untuk referensi tema lainnya, kamu bisa membuka halaman <https://github.com/robbyrussell/oh-my-zsh/wiki/Themes>.

## Fitur Zsh yang tidak ada di Bash

* `cd completion`

...Ketika mengetikkan perintah `cd` dan menekan tombol tab, maka direktori yang ada akan autocomplete, jika ditekan tab lagi nama direktori akan berpindah dari satu direktori ke direktori lainnya sampai berakhir di direktori yang dimaksud.

* `git completion`

Ketika mengetikkan perintah `git` lalu menekan tombol tab, maka akan muncul perintah-perintah yang ada.

* `path expansion`

Kita dapat mempersingkat perintah path directori dengan huruf depannya saja. Contohnya ketika akan menuju direktori `/usr/local/bin` cukup mengetikkan perintah:
```
cd /u/lo/b
```

* `alias`

Dapat mempersingkat perintah dengan menggunakan alias. Salah satu contohnya adalah ketika akan mengetikkan perintah:
```
ls -lh
```
maka cukup menyingkatnya dengan perintah:
```
ll
```


