# fluttertestpaulasvb

A new Flutter project.

## Dev

```bash
flutter run
```

## Notification

https://pub.dev/packages/flutter_local_notifications
## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Init

https://wiki.archlinux.org/title/android

https://dev.to/awais/configure-flutter-development-environment-on-manjaro-arch-linux-4a0a

https://www.rockyourcode.com/how-to-get-flutter-and-android-working-on-arch-linux/

# How to install on Arch

```
yay -S flutter
sudo groupadd flutterusers
sudo gpasswd -a $USER flutterusers
sudo chown -R :flutterusers /opt/flutter
sudo chmod -R g+w /opt/flutter/
sudo chown -R $USER:flutterusers /opt/flutter
```
Should work now:
```
flutter
```

Should show potential problems:
```
flutter doctor
``


