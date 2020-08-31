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

# Log

```shell
dianariyanto@pop-os:~/$ git clone git@github.com:dianariyanto/scrcpy-launcher.git
Cloning into 'scrcpy-launcher'...
remote: Enumerating objects: 16, done.
remote: Counting objects: 100% (16/16), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 16 (delta 2), reused 16 (delta 2), pack-reused 0
Receiving objects: 100% (16/16), done.
Resolving deltas: 100% (2/2), done.

dianariyanto@pop-os:~/$ cd scrcpy-launcher/

dianariyanto@pop-os:~/scrcpy-launcher$ chmod +x install 

dianariyanto@pop-os:~/scrcpy-launcher$ ./install "Redmi Note 6 Pro" 192.168.11.24
Install Scrcpy Launcher : Add Redmi Note 6 Pro
Install Scrcpy Launcher : Processing..
Install Scrcpy Launcher : Copying Redmi Note 6 Pro to Launcher
Install Scrcpy Launcher : Processing..
Install Scrcpy Launcher : Fix Redmi Note 6 Pro Permission
Install Scrcpy Launcher : Processing..
Install Scrcpy Launcher : Done.

dianariyanto@pop-os:~/scrcpy-launcher$ ./remove "Redmi Note 6 Pro"
Remove Scrcpy Launcher : Delete Redmi Note 6 Pro
Remove Scrcpy Launcher : Processing..
Remove Scrcpy Launcher : Done.
```