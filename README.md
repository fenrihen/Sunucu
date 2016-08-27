# Sunucu
Sunucu yapılandırması.

## Kullanıcı Ayarları
Ayarlar için [Initial Server Setup with Ubuntu 16.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-16-04) adresindeki yönergelerden 1-3 ve 6-7 takip edildi.
## Klasör Ayarları
Anadizinde aşağıdaki gibi bir klasör yapısı kuruldu.
- Downloads
- Clones

## Uygulamalar
### Miniconda3 3.16
#### İndirme
```bash
wget https://repo.continuum.io/miniconda/Miniconda3-3.16.0-Linux-x86_64.sh 
```
#### Yükleme
**/home/fenrihen/Applications/Miniconda3-3.16 klasörüne standart yükleme.**
#### Ayarlar
```bash
conda update conda
conda config --add channels conda-forge
```
#### Modüller
##### jupyter
##### jupyter_contrib_nbextensions
##### numpy
##### matplotlib
##### pymongo

### MongoDB 3.2
#### İndirme ve Yükleme
[Install MongoDB Community Edition on Ubuntu — MongoDB Manual 3.2](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/) adresindeki 1-4 yönergeleri takip edilir.
