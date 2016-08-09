# conkyForGnome3
<p>A conky script for a fast and beauty surpervision of your linux under Gnome 3 desktop</p>
<p></p>
# Installation
<p></p>
<p>You need to install 3 paquages :</p>
<p>$ sudo apt-get install conky-all hddtemp xsensors</p>
<p></p>
<p>$ sudo dpkg-reconfigure hddtemp</p>
<p>Say "Yes" for all requests.</p>
<p></p>
<p>Download the script and move it under ~/.conkyrc:</p>
<p>$ sudo mv ~/Download/conkyrc.sh  ~/.conkyrc</p>
<p></p>
<p>For starting automatically conky with linux, you need adding this under "Startup Applications Preferences" GUI:</p>
<p>bash -c "sleep 20 ; conky -c ~./conkyrc"</p>

