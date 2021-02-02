## [OneShot](https://github.com/drygdryg/OneShot) installer for [Termux](https://play.google.com/store/apps/details?id=com.termux)
### Setup
```
curl -sSf https://raw.githubusercontent.com/drygdryg/OneShot_Termux_installer/master/installer.sh | bash
```
### Run
Disable Wi-Fi in the system settings and run:
```
sudo python oneshot.py -i wlan0 -K
```
