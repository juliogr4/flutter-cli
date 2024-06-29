# FLUTTER CLI

### Check Flutter current version
```flutter
flutter --version
```

### See all Flutter commands
```flutter
flutter --help --verbose
```

### Create a Flutter project
```flutter
flutter create <project_name>
```

### Run flutter project
```
flutter run ./lib/main.dart
```

### Find issues
```flutter
flutter analyze
```

### Flutter packages repository
```flutter
https://pub.dev/
```

### Install a package in `pubspec.yaml` by name

| on | command |
| :--: | :-------: |
| dependency | `flutter pub add <package_name>` |
| dev dependency | `flutter pub add -d <package_name>` |
<br>

### Install packages added manually in `pubspec.yaml`
```flutter
flutter pub get
```

### Remove a package in `pubspec.yaml`
```flutter
flutter pub remove <package_name>
```

### Project testing
```flutter
flutter test
```

### List every outdated dependencies
```flutter
flutter pub outdated
```

### Update all dependencies to their latest versions
```flutter
flutter pub upgrade
```
