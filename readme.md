Ubuntu 18.04:error  
0.0.0.0:53: bind: address already in use
sudo service systemd-resolved stop  
sudo nano /etc/resolv.conf  

change nameserver 127.0.0.53 becomes nameserver 127.0.0.1
