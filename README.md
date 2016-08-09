# conkyForGnome3
A conky script for a fast and beauty surpervision of your linux under Gnome 3 desktop


# Installation

You need to install 3 paquages :
$ sudo apt-get install conky-all hddtemp xsensors

$ sudo dpkg-reconfigure hddtemp
Say "Yes" for all requests.

Download the script and move it under ~/.conkyrc:
$ sudo mv ~/Download/conkyrc.sh  ~/.conkyrc

For starting automatically conky with linux, you need adding this under "Startup Applications Preferences" GUI:
bash -c "sleep 20 ; conky -c ~./conkyrc"

