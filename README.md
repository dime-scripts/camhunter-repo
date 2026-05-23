# CamHunter

Local network camera discovery tool for Linux.

## Install

scroll to the buttom for android/ios/samsung

```bash
echo "deb [trusted=yes] https://dime-scripts.github.io/camhunter-repo ./" | sudo tee /etc/apt/sources.list.d/camhunter.list

sudo apt update
sudo apt install camhunter
```

## Usage

```bash
camhunter
```

## Features

* Fast local network scanning
* Lightweight shell script
* Simple installation through APT
* Open source

## Notes

CamHunter only discovers devices on your local network.
It does not bypass authentication or access camera feeds.

## Repository

https://github.com/dime-scripts/camhunter-repo

---
## Install termux (android/ios/samusng support all-in-one tutorial)

first you will need to install termux, do that by going to play market and searching for termux.
```link
https://play.google.com/store/apps/details?id=com.termux&hl=en&pli=1
```
the recomended way is if you install the f-droid version, go-to:
```link
https://f-droid.org/F-Droid.apk
```
To download it

then in the f-droid app search for termux and download it from there
and you will be done!


## Download camhunter for android
```bash
# install requirements:
pkg install root-repo
pkg install unstable-repo
pkg install x11-repo
```
```bash
# This project is new so you will need to allow it first do that by: 

echo "deb [trusted=yes] https://dime-scripts.github.io/camhunter-repo ./" > $PREFIX/etc/apt/sources.list.d/camhunter.list
```

```bash
#update and install camhunter

pkg update
pkg install camhunter

```
# NOTES!

If you paid for this tool, you got scammed.
CamHunter is free and publicly available.

© dime
