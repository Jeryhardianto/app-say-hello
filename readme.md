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

### Membaut Base Project dengan Module
```
> go mod init github.com/Jeryhardianto/go-say-hello
> go get github.com/Jeryhardianto/go-say-hello
> lalu panggil modulenya

``` 