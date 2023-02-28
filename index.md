# zeev-api

Sedikit penjelasan tentang [zeev-api](https://github.com/Zeev-x/zeev-api).


## ```INSTALL```
> npm install zeev-api
## ``` UNINSTALL ```
> npm uninstall zeev-api


## ```Otakudesu```
``` 
const zeev = require('zeev-api');
const judul = 'kaifuku'

zeev.otakudesu(judul)
    .then(result => {
     console.log(result)
});
```
## ```Covid```
``` 
const zeev = require('zeev-api');

zeev.covid()
    .then(result => {
     console.log(result)
});
```

## ```Ongoing```
``` 
const zeev = require('zeev-api');

zeev.ongoing()
    .then(result => {
     console.log(result)
});
```

## ```Komiku```
``` 
const zeev = require('zeev-api');
const judul = 'kanojo mo kanojo'

zeev.komiku(judul)
    .then(result => {
     console.log(result)
});
```

## ```Tebak Gambar```
``` 
const zeev = require('zeev-api');

zeev.tebakgambar()
    .then(result => {
     console.log(result)
});
```

## ```Surah```
``` 
const zeev = require('zeev-api');
const no = '1'

zeev.surah(no)
    .then(result => {
     console.log(result)
});
```

## ```Sholat```
``` 
const zeev = require('zeev-api');
const no = '1'

zeev.sholat(no)
    .then(result => {
     console.log(result)
});
```

## ```Lirik```
``` 
const zeev = require('zeev-api');
const judul = 'black catcher'

zeev.lirik(judul)
    .then(result => {
     console.log(result)
});
```

## ```Chara```
``` 
const zeev = require('zeev-api');
const name = 'nino'

zeev.chara(name)
    .then(result => {
     console.log(result)
});
```

## ```Wattpad```
``` 
const zeev = require('zeev-api');
const judul = 'love'

zeev.wattpad(judul)
    .then(result => {
     console.log(result)
});
```

## ```Play Store```
``` 
const zeev = require('zeev-api');
const judul = 'game 8 bit'

zeev.playstore(judul)
    .then(result => {
     console.log(result)
});
```

## ```Link Wa```
``` 
const zeev = require('zeev-api');
const judul = 'Editod bekentod'

zeev.linkwa(judul)
    .then(result => {
     console.log(result)
});
```

## ```Pinterest```
``` 
const zeev = require('zeev-api');
const judul = 'nakano nino'

zeev.pinterest(judul)
    .then(result => {
     console.log(result)
});
```

## ```IG Downloader```
``` 
const zeev = require('zeev-api');
const link = 'https://www.instagram.com/p/CQpUpGvAhWq/?utm_source=ig_web_copy_link'

zeev.igdl(link)
    .then(result => {
     console.log(result)
});
```


## ```IG Story```
``` 
const zeev = require('zeev-api');
const username = 'yabegitulahaha'

zeev.igstory(username)
    .then(result => {
     console.log(result)
});
```
## ```IG Stalk```
``` 
const zeev = require('zeev-api');
const username = 'yabegitulahaha'

zeev.igstalk(username)
    .then(result => {
     console.log(result)
});
```

## ```Twitter Downloader```
``` 
const zeev = require('zeev-api');
const link = 'https://twitter.com/PassengersMovie/status/821025484150423557'

zeev.twitter(link)
    .then(result => {
     console.log(result)
});
```

## ```Facebook Downloader```
``` 
const zeev = require('zeev-api');
const link = 'https://fb.watch/6vQOvEENLW/'

zeev.fbdown(link)
    .then(result => {
     console.log(result)
});
```

## ```Youtube Downloader```
``` 
const zeev = require('zeev-api');
const link = 'https://youtu.be/5C8yvJUVB-0'

zeev.youtube(link)
    .then(result => {
     console.log(result)
});
```

## ```Tiktok Downloader```
``` 
const zeev = require('zeev-api');
const link = 'https://www.tiktok.com/@daniajaa7/video/6980287183517125890?sender_device=pc&sender_web_id=6978811994732938753&is_from_webapp=v1&is_copy_url=0'

zeev.ttdownloader(link)
    .then(result => {
     console.log(result)
});
```
# ```LIST JADWAL SHOLAT```
```
Jakarta = 1
Ambon = 39
Balikpapan = 42 
Banda Aceh = 17
Bandar Lampung = 22
Bandung = 7
Banjar = 44
Banjarbaru = 46
Banjarmasin = 32
Banyuwangi = 48
Batam = 8
Batu = 50
Bau-bau = 52
Bekasi = 54
Bengkulu = 21
Bima = 56
Binjai = 58
Bitung = 60
Blitar = 62
Bogor = 64
Bontang = 66
Bukittinggi = 68
Cilegon = 70
Cimahi = 72
Cirebon = 74
Denpasar = 6
Depok = 76
Dumai = 78
Gorontalo = 38
Gunungsitoli = 80
Jambi = 19
Jayapura = 9
Jember = 82
Kediri = 84
Kendari = 36
Kotamobagu = 86
Kupang = 28
Langsa = 88
Lhokseumawe = 90
Lubuklinggau = 92
Madiun = 94
Magelang = 98
Makassar = 13
Malang = 96
Mamuju = 37
Manado = 15
Manokwari = 41
Mataram = 29
Medan = 14
Mojokerto = 100
Padang = 16
Padangpanjang =  102 
Padangsidempuan = 104
Pagar Alam = 106
Palangkaraya = 31
Palembang = 20
Palopo = 108
Palu = 35
Pangkal Pinang = 23
Pangkalpinang = 110
Parepare = 112
Pariaman = 114
Pasuruan = 116
Payakumbuh = 118
Pekalongan = 120
Pekanbaru = 18
Pematangsiantar = 122
Pontianak = 30
Prabumulih = 124
Probolinggo = 126
Sabang = 128
Salatiga = 130
Samarinda = 33
Sawahlunto = 132
Semarang = 26
Serang = 27
Sibolga = 134 
Singkawang = 136
Sofifi = 138
Solo = 40
Solok = 140
Sorong = 142
Subulussalam = 144
Sukabumi  = 146 
Sungai Penuh = 148
Surabaya = 4
Surakarta = 150
Tangerang = 152
Tangerang Selatan = 154
Tanjung Pinang = 24
Tanjung Selor = 34
Tanjungbalai = 156
Tarakan = 158
Tasikmalaya = 160
Tebing Tinggi = 162
Tegal = 164
Ternate = 166
Tidore Kepulauan = 168
Tomohon = 170
Tual = 172
Yogyakarta = 25
```

  ## Untuk selengkapnya silahkan hubungi:
* [`Zeev-x`](https://github.com/Zeev-x)
  
