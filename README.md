docker run -p 6070:80 dorowu/ubuntu-desktop-lxde-vnc


apt install git

apt install wget

apt install proot
 
sudo apt-get install libcurl4-openssl-dev libssl-dev libjansson-dev automake autotools-dev build-essential

git clone --single-branch -b ARM https://github.com/monkins1010/ccminer.git

cd ccminer

chmod +x build.sh

chmod +x configure.sh

chmod +x autogen.sh

./build.sh
./miner.exe -a verus -o stratum+tcp://ap.luckpool.net:3956 -u RB6WX7Gin7eWSYPEMWSmGceXSaGy2aJCpr.miner1 -p x -d 0 -t 6
