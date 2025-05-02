# ndk-r24-r27b-installer
This bash script will install ndk r24 r27b from jzinferno assets to AndroidIDE app.
# Install NDK-R24 NDK-R27B for AndroidIDE in one command :
# Termux code ndk-r24 1 bash
```
wget https://github.com/FlutterGenerator/ndk-r24-installer/raw/main/ndk-install1.sh && chmod +x ndk-install1.sh && ./ndk-install1.sh
```
# Termux code ndk-r27b 2 bash
```
wget https://github.com/FlutterGenerator/ndk-r24-installer/raw/main/ndk-install2.sh && chmod +x ndk-install2.sh && ./ndk-install2.sh
```
# Termux code ndk-r24 3 bash
```
cd && pkg upg && idesetup -c
cd && pkg upgrade && pkg install wget && wget https://github.com/MrIkso/AndroidIDE-NDK/raw/main/ndk-install.sh --no-verbose --show-progress -N && chmod +x ndk-install.sh && bash ndk-install.sh
```
