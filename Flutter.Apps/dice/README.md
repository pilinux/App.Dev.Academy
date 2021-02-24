## dice - A Flutter project for beginners

### Installation

- In the device's security settings, allow installing apps from unknown sources.
- Download the Android APK from [here][01], install it on your device, and play!

SHA1 Checksum: `9d30b5e33e09bcf55b84fff6a8d8f8a78f9e1cad`


### How to check the checksum

On any Linux machine, download the APK and verify the checksum:
`sha1sum app.apk`


### About the app

This simple app rolls two dices. Tap one of the dices to roll.

![app-outlook][02]


### For developers - getting started

- Create a new Flutter project `flutter create dice`
- Open with Android Studio (or any other IDE)
- Replace default files of the Flutter project with files from this repository
- Debug and build

Note: To build without null-safety, change `environment` to `sdk: ">=2.7.0 <3.0.0"` in `pubspec.yaml` file

App icon and dice images are provided by London App Brewery.


[01]: https://cdn.pilinux.me/binaries/App.Dev.Academy/Flutter.Apps/dice/app.apk
[02]: https://cdn.pilinux.me/images/App.Dev.Academy/Flutter.Apps/dice/diceApp.png
