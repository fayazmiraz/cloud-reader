# Amazon Cloud Reader

A very simple reader for Amazon Cloud Reader.

## Install from binary

Download latest deb package from [here](https://github.com/metalerk/cloud-reader/releases/latest)

```sh
$ sudo dpkg -i cloud-reader_<VERSION>_all.deb
```

## Install from source code

### Linux

```sh
$ git clone git@github.com:metalerk/cloud-reader.git
$ cd cloud-reader
$ GOOS=linux go build -o cloud-reader cloud_reader.go
```

### Other

```sh
$ go build -o cloud-reader cloud_reader.go
```

## Run

```sh
$ cloud-reader
```

## Screenshots

![screenshot1](https://i.imgur.com/SZhjZA5.png)
![screenshot1](https://i.imgur.com/0weXE1d.png)
![screenshot1](https://i.imgur.com/wbZgKQH.png)
![screenshot1](https://i.imgur.com/KXBxEjD.png)