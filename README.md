# Gitopia membuat Repository

1. Login ke https://gitopia.com/
2. Connect Via Recovery Exisiting Wallet
3. Masukan Pharse Wallet Kepler/Validator Kalian
4. Buat Password dan Done
5. Create Repository, Buat Nama dan Deskripsi Bebas

## Open VPS

## Install Git Remote 
```curl https://get.gitopia.com | bash```
## Buat Folder (sesuaikan yang ada di web)
```
mkdir nama-repository
``` 
**nama repository yang diweb**
```
cd nama-repository
```
**nama repository yang baru di buat tadi**

## Buat Config
```
git config --global user.email "isi email"
```
```
git config --global user.name "Akun-Gitopia"
```

## Buat File readme.md
```
echo "# welcome to bent0000-guide" >> README.md
git init
git add README.md
git commit -m "initial commit"
```

## Push Repository

- Login ke https://gitopia.com/
- Klik Profil & Download Wallet
<p align="center">
  <img height="500" height="auto" src="https://github.com/bent0000/photo/blob/main/Screenshot%20from%202022-11-23%2002-38-22.png?raw=true">
</p>

- Upload wallet yang udah di download ke VPS kalian.
<p align="center">
  <img height="500" height="auto" src="https://github.com/bent0000/photo/blob/main/Screenshot%20from%202022-11-23%2002-36-44.png?raw=true">
</p>

## Export Wallet
```
export GITOPIA_WALLET=/root/bent0000-guide/bent0000.json
```
**bent0000-guide ganti pake nama folder atau akun kalian**
## Upload File ke Akun Gitopia
```
git remote add origin gitopia://bent0000-guide/Testnet
git push -u origin master
```
**bent0000-guide ganti pake nama akun kita yang di web**


## Done. 
