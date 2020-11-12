apt-get update
apt-get upgrade

chmod +x hlds_run
chmod +x hlds_linux

apt-get install libc6-i386 lib32gcc1 -y
apt-get install lib32stdc++6

./hlds_run -game cstrike +ip 10.158.0.11 +port 27015 +maxplayers 16 +map de_dust2