Tips: optional
Ubuntu 18.04 error: `0.0.0.0:53: bind: address already in use`
1. sudo service systemd-resolved stop  
2. sudo vi /etc/resolv.conf and change nameserver 127.0.0.53 becomes nameserver 127.0.0.1
