# ndk-r24-installer
This bash script will install ndk r24 from jzinferno assets to AndroidIDE app.
- Install NDK-R24 for AndroidIDE in one command :
```Termux code 1 bash
wget https://github.com/FlutterGenerator/ndk-r24-installer/raw/main/ndk-install.sh && chmod +x ndk-install.sh && ./ndk-install.sh
```
```Termux code 2 bash
cd && pkg upg && idesetup -c
cd && pkg upgrade && pkg install wget && wget https://github.com/MrIkso/AndroidIDE-NDK/raw/main/ndk-install.sh --no-verbose --show-progress -N && chmod +x ndk-install.sh && bash ndk-install.sh
```
