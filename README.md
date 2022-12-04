# cyber-freebsd
The desktop environment from CyberOS, on FreeBSD<br><br>
<h3>Dirty installation:</h3><br>
<b>Install dependencies:</b><br>
# pkg rquery -e '%n~qt5-*' %n | xargs pkg install -y && pkg rquery -e '%n~libqt-*' %n | xargs pkg install -y && pkg rquery -e '%n~kf5-*' %n | xargs pkg install -y<br>
<br>
<b>Install binaries and libraries:</b><br>
# Move the binaries to /usr/bin, except "cyber-dock", which should go to /usr/local/bin<br>
# Move the libraries to /usr/local/lib/<br>
<br>
<b>Use Cyber</b><br>
# Create your .xinitrc file in your home directory and write "cyber-session" into it.<br>
<b>Screenshots:</b>
<br>
<img src="https://media.discordapp.net/attachments/727023752348434436/1048886476173234237/2022-12-04-110004_1920x1080_scrot.png?width=1015&height=571"></img><br><br>
<img src="https://media.discordapp.net/attachments/727023752348434436/1048886646998843472/2022-12-04-110055_1920x1080_scrot.png?width=1015&height=571"></img>
