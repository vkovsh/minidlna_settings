# Minidlna Server Settings
Linux 5.8.7-arch1-1 x86_64 GNU/Linux 
1) *sudo su*
2) *pacman -Syu minidlna*
3) *git clone minidlna_settings && cd minidlna_settings* 
4) *cp ./minidlna.conf /etc/minidlna.conf*
5) *cp ./minidlna /etc/default/minidlna*
6) *systemctl start minidlna*
7) *systemctl status minidlna*
8) *ss -4lnp | grep minidlna*
9) *cat /var/log/minidlna.log* 