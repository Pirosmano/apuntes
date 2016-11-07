## tutorial debian

### activar sudo:

'''sh
su
apt-get install sudo
sudo adduser nombre_usuario sudo
'''
###desinstalar programas y limpiar registros
sudo apt-get purge nombre_del_programa
sudo apt-get autoremove

###actualizar debian:

sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade && sudo apt-get autoremove


### instalar instalador grafico de paquetes debian

'''sh
sudo apt-get install gdebi
'''

### instalar mis aplicaciones favoritas
'''sh
sudo apt-get install htop
sudo apt-get install libreoffice
sudo apt-get install transmission-gtk

### ejecutar scripts
'''sh
bash nombre_script.sh
'''
