
---

# CamHunter

CamHunter is a lightweight local network tool that discovers devices on your network.

It is designed for quick network visibility and simple device scanning on Linux and Termux environments.

---

## Installation (Linux / Kali / Ubuntu)

```bash
echo "deb [trusted=yes] https://dime-scripts.github.io/camhunter-repo ./" | sudo tee /etc/apt/sources.list.d/camhunter.list

sudo apt update
sudo apt install camhunter
```

---

## Usage

```bash
camhunter
```

---

## Features

* Fast local network device discovery
* Lightweight and simple shell-based tool
* Easy installation via APT package system
* Works on Linux and Termux environments
* Open source

---

## What it does

CamHunter scans your local network and lists active devices connected to it.

It does not:

* Bypass authentication
* Access camera feeds
* Exploit devices
* Perform remote hacking

---

## Supported Platforms

* Linux (Debian / Ubuntu / Kali)
* Termux (Android)

---

# Termux Installation Guide (Android)

## Install Termux

You can install Termux from one of the following sources:

* Play Store (if available in your region)
* F-Droid (recommended)

F-Droid download:

```
https://f-droid.org/F-Droid.apk
```

After installing F-Droid, search for “Termux” and install it.

---

## Install CamHunter on Termux

First, install required repositories:

```bash
pkg update
pkg install root-repo unstable-repo x11-repo
```

Add the CamHunter repository:

```bash
echo "deb [trusted=yes] https://dime-scripts.github.io/camhunter-repo ./" > $PREFIX/etc/apt/sources.list.d/camhunter.list
```

Update and install:

```bash
pkg update
pkg install camhunter
```

---

## Notes

* CamHunter is free and open source.
* It only works on networks you are connected to.
* It does not access private data or remote systems.

---

## Repository

[https://github.com/dime-scripts/camhunter-repo](https://github.com/dime-scripts/camhunter-repo)

---

## Important

If you paid for this tool, you were scammed.

CamHunter is and will always be free software.

© dime

---
