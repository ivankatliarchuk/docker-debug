cat /etc/resolv.conf

nc $DNS $PORT -v -w1
wget -O- $ENDPOINT
