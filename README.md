# Kiosk
Application demonstrates basic usage of Android Lock Task mode for creating Kiosk app
### Article

### Presentation

### Usage
1. Make factory reset
2. Skip adding google acount
3. Install apk
```bash
$ adb install path/to/kiosk.apk
```
4. Set device owner
```bash
$ adb shell dpm set-device-owner pl.snowdog.kiosk/.MyDeviceAdminReceiver
```

### Screenshots
<img src="https://user-images.githubusercontent.com/12548284/37874490-775d37d6-3030-11e8-897c-e5d930a3d44f.png" width="292" height="519" /> <img src="https://user-images.githubusercontent.com/12548284/37874485-6c9b6a70-3030-11e8-8ea4-75ec19f10a59.png" width="292" height="519" />
