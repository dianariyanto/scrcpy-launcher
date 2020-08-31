# Remote Android via ADB Wireless using scrcpy
Wireless remote your Android Phone or Tablet without Internet and any 3rd party software installed on your Android device (Android 5+). Older version of Android can still use this tool by installing *WiFi ADB - Debug Over Air* app available [here](https://play.google.com/store/apps/details?id=com.ttxapps.wifiadb). 

Install Depedency

```shell
sudo apt install git adb scrcpy -y
git clone https://github.com/dianariyanto/scrcpy-launcher.git
cd scrcpy-launcher
chmod +x install
```
Install Scrcpy Launcher
```shell
./install <DeviceName> <IPADDRESS>
```
Remove Scrcpy Launcher
```shell
./remove <DeviceName>
```