# conkyForGnome3 (Works on Unity)
<p>A conky script for a fast and beauty surpervision of your linux under Gnome 3 desktop</p>
<p></p>
# Installation
<p></p>
<p>You need to install 3 paquages :</p>
<h6>$ sudo apt-get install conky-all hddtemp xsensors</h6>
<p></p>
<h6>$ sudo dpkg-reconfigure hddtemp</h6>
<p>Say "Yes" for all requests.</p>
<p></p>
<p>Check your interface:</p>
<h6>§ ifconfig</h6>
<hr>
<p>Change "conkyrc" in the 2 commands under to what wlan interface you have, "conkywlan0rc" or "conkywlp2s0rc"</p>
<p></p>
<hr>
<p>Download the script and move it under ~/.conkyrc:</p>
<h6>$ sudo mv ~/Download/conkyrc.sh  ~/.conkyrc</h6>
<p></p>
<p>For starting automatically conky with linux, you need adding this under "Startup Applications Preferences" GUI:</p>
<h6>bash -c "sleep 20 ; conky -c ~./conkyrc"</h6>

