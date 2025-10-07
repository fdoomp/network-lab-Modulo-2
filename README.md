# network-lab-Modulo-2
Comandos usados practica 1
sudo apt update 

sudo apt upgrade 

cat /etc/apt/sources.list

grep ^deb /etc/apt/sources.list.d/*.list 

apt search bashtop 

https://es.linux-console.net/?p=438#gsc.tab=0

sudo apt install bashtop -y 

bashtop

sudo apt purge bashtop -y 

sudo apt autoremove -y 

============================================

Comandos usados practica 2
crontab -e

HORA: 0 23 * * * sudo apt update && sudo apt upgradre -y

crontab -e 

0 3 * * 0 sudo reboot

sudo systemctl enable --now atd 

ls /tmp

sudo su

echo "sudo rm -rf /temp/* | at now + 1 minute 

atq 

ls /tmp 

============================================

Comandos usados practica 3
sudo fdisk -l 

sudo fdisk /dev/sdb 

sudo fdisk -l

sudo mkfs.ext4 /dev/sb1 

mkdir 'la direccion de la carpeta' 

sudo mount /dev/sdb1 'la direccion de la carpeta' 

cd 'la direccion de la carpeta' 

sudo touch AdrianAlcantara.txt 

cd

sudo umount /dev/sdb1 

sudo mount /dev/sdb1 /mnt 

ls /mnt 

============================================
