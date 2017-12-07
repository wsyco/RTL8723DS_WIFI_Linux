# RTL8723DS

Linux driver for RTL8723DS. The master branch is based on Realtek Version

**00007156-20161214_RTL8723DS_WiFi_linux_v5.1.1.5_20523_BT_ANDROID_6.0_COEX_8723D-1010_8703CS-0A0A.**

It has been modified to build cleanly for kernels through v3.13.0

Run the following commands in the Linux terminal.

```shell
git clone https://github.com/wsyco/RTL8723DS_WIFI_Linux.git
cd RTL8723DS_WIFI_Linux
make
make install
modprobe -v 8723ds
lsmod | grep 8723ds
```
