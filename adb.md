# ADB Commands
| Command | Use | Example |
|---------|-----|---------|
| `adb devices` | List connected devices | `adb devices` |
| `adb install <path_to_apk>` | Install an app | `adb install myapp.apk` |
| `adb uninstall <package_name>` | Uninstall an app | `adb uninstall com.example.app` |
| `adb push <local> <remote>` | Copy file/dir to device | `adb push file.txt /sdcard/` |
| `adb pull <remote> <local>` | Copy file/dir from device | `adb pull /sdcard/file.txt ./` |
| `adb shell` | Start a remote shell | `adb shell` |
| `adb logcat` | View device logs | `adb logcat` |
| `adb reboot` | Reboot the device | `adb reboot` |
| `adb backup` | Create a full backup | `adb backup -all` |
| `adb restore` | Restore a backup | `adb restore backup.ab` |
| `adb shell screencap` | Take a screenshot | `adb shell screencap /sdcard/screen.png` |
| `adb shell screenrecord` | Record the screen | `adb shell screenrecord /sdcard/video.mp4` |
| `adb shell pm list packages` | List installed packages | `adb shell pm list packages` |
| `adb shell am start -n <package>/<activity>` | Start an app | `adb shell am start -n com.example.app/.MainActivity` |
| `adb shell input text "<text>"` | Input text | `adb shell input text "Hello World"` |
