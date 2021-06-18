# XMRig-Termux
XMRig for Termux on Android.
 
```
pkg install update && upgrade
apt-get install git 
apt install wget 
```
This is for Ubuntu.

```
git clone https://github.com/Neo-Oli/termux-ubuntu 
cd termux-ubuntu 
chmod +x ubuntu.sh 
sh ubuntu.sh 
./start-ubuntu.sh
```
XMRig

```
apt update 
apt upgrade
apt-get install git build-essential cmake libuv1-dev libmicrohttpd-dev   
git clone https://github.com/xmrig/xmrig.git 
cd xmrig 
mkdir build
cd build 
cmake -DWITH_HWLOC=OFF .. 
make
