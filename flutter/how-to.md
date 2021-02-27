### Update to dev

Apparantly I need to update to `dev` branch to fix a few errors

```bash
flutter channel dev
flutter upgrade
```

### Always run it before deploying

```bash
flutter pub get
flutter packages pub run build_runner build --delete-conflicting-outputs
```


Wirelessly install apps
```bash adb connect 192.168.31.177:5555```
