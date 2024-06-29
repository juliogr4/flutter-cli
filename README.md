# FLUTTER CLI

### check flutter current version
```
flutter --version
```

### see all flutter commands
```
flutter --help --verbose
```

### create a flutter project
```flutter
flutter create <project_name>
```

### find issues
```flutter
flutter analyze
```

### flutter packages repository
```flutter
https://pub.dev/
```

### install package

| on | command |
| :--: | :-------: |
| dependency | flutter pub add `<package_name>` |
| dev dependency | flutter pub add -d `<package_name>` |
<br>

### remove a package in `pubspec.yaml`
```
flutter pub remove <package_name>
```

### project testing
```
flutter test
```

### run flutter project
```
flutter run ./lib/main.dart
```

### Install dependencies added manually in `pubspec.yaml`
```
flutter pub get
```

### list every outdated dependencies
```
flutter pub outdated
```

### update all dependencies to their latest versions
```
flutter pub upgrade
```
