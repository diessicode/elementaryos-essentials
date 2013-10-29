# Elementary OS: essential kit

A kit of essential tools to equip your Elementary OS after installation. Useful for those who are migrating from Windows to Elementary or wants to migrate someone. :-) 

All software recommended here have a installation tutorial **via Terminal**, for objectivity. However, if you want, the software is also available in **Software Center**.

## Language
* [Português](https://github.com/diessicode/elementaryos-essentials/blob/master/translations/pt-br/README.md)

## Kit
1. [System monitor](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#1-system-monitor)
2. [Office suite](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#2-office-suite)
3. [System and disk cleaner](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#3-system-and-disk-cleaner)
4. [CD/DVD burner](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#4-cddvd-burner)
5. [Disk manager](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#5-disk-manager)
6. [Virtual drive emulator](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#6-virtual-drive-emulator)
7. [Graphic editor](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#7-graphic-editor)
8. [Video editor](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#8-video-editor)
9. [Antivirus](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#9-antivirus)
10. [Torrent client](https://github.com/diessicode/elementaryos-essentials/blob/master/README.md#10-torrent-client)

## 1. System monitor and task manager
**GNOME System Monitor**

![System Monitor in action](http://screencloud.net/img/screenshots/07804f1e8ec0aece79f8c4026caba171.png)

### Alternatives
* [SoftMaker Office](#)
* [Google Docs](#)

### Installation
1. `sudo apt-get install gnome-system-monitor`

## 2. Office suite
**Libre Office**

![Libre Office 3](http://screencloud.net//img/screenshots/96a09927db99b0cdebc3b15a7735f387.png)

### Installation
#### Terminal
1. `sudo add-apt-repository ppa:libreoffice/ppa`
2. `sudo apt-get update`
3. `sudo apt-get install libreoffice`

#### [Other ways](http://www.libreoffice.org/download)

### Alternatives
* [SoftMaker Office](#)
* [Google Docs](#)

-- 

## 3. System and disk cleaner
**BleachBit**

### Installation
1. `sudo apt-get install bleachbit`

-- 

## 4. CD/DVD burner
**Brasero**

-- 

## 5. Disk manager
**Disks**
![Disks showing data](http://screencloud.net/img/screenshots/ed6538b6aeda987de8cac06760198ab1.png)

### Installation
1. `sudo apt-get install gnome-disk-utility`

-- 

## 6. Virtual drive emulator
**AcetoneISO**

### Installation
1. `sudo apt-get install kommander p7zip` - **kommander** will be installed additionally. 
2. `sudo apt-get install AcetoneISO-6.7.deb`

-- 

## 7. Graphic editor
**GIMP**

### Installation
1. `sudo add-apt-repository ppa:otto-kesselgulasch/gimp`
2. `sudo apt-get update`
3. `sudo apt-get install gimp`

-- 

## 8. Video editor
**PiTiVi**

### Installation
1. `sudo apt-get install pitivi`

### Alternatives
* [OpenShot](#)

-- 

## 9. Antivirus
**Bitdefender**

### Installation
1. `wget -O- -q http://download.bitdefender.com/repos/deb/bd.key.asc | sudo apt-key add -`
2. `sudo sh -c 'echo "deb http://download.bitdefender.com/repos/deb/ bitdefender non-free" >> /etc/apt/sources.list'`
3. `sudo apt-get update`
4. `sudo apt-get  install bitdefender-scanner-gui`

### Alternatives
* [ESET](#)
* [ClamAV](#)

-- 

## 10. Torrent client
**Deluge**

### Installation
1. `sudo apt-get install deluge`

### Alternatives
* [qBitTorrent](#)
* [Transmission](#)

## 11. Backup
**luckyBackup**

### Installation
1. `sudo apt-get install luckybackup`

### Alternatives
* [Deja-Dup](https://launchpad.net/deja-dup)


## Installation problems?
Before installation, enter in your Terminal any of the following commands:

1. `sudo apt-get update` → Update the **package list**.
2.  `sudo apt-get dist-upgrade` → Upgrade your **operational system**.

## Freedom thanks you!
Thanks for contributing to free software. **GNU/Linux** are really awesome!
