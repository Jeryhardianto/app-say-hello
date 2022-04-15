## Golang Module

### Membuat Module
```
> Buat repository baru dengan nama `github.com/<nama_repo>`
> Buat Folder atau project modulenya
> Dalam folder / Module tersebut ketik command berikut :
  > go mod init github.com/<nama_repo>
  > coding module yang ingin dibuat
```

### Upgrade Module
```
> push ulang code kita lalu buat tag menjadi versi terbaru
> push tag baru ke github
> pada go.mod, ubah versi terbaru dengan tag yang baru
> go get
> go run main.go
```

### Major Upgrade 
```
> perubahan code yang kita buat menjadi versi baru
> push ulang code tersebut
> push tag baru ke github
> pada go.mod, hapus versi lama
> go get github.com/Jeryhardianto/go-say-hello/v2
```

### Membaut Base Project dengan Module
```
> go mod init github.com/Jeryhardianto/go-say-hello
> go get github.com/Jeryhardianto/go-say-hello
> lalu panggil modulenya

``` 