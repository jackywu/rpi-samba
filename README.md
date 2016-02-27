# rpi-samba
# samba share center for rpi

1. cp smb.conf /etc/samba
2. cp limits.conf /etc/security/limits.conf
3. add these two lines to /etc/rc.local: 
    ulimit -Hn 16384
    ulimit -Sn 16384
4. /etc/init.d/samba restart
