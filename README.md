How to create Icon for UDA_QLSV app.
https://pub.dev/packages/flutter_launcher_icons
1. Setup the config file 
Add your Flutter Launcher Icons configuration to your pubspec.yaml or create a new config file called flutter_launcher_icons.yaml. An example is shown below. More complex examples can be found in the example projects.
dev_dependencies:
  flutter_launcher_icons: "^0.12.0"

flutter_icons:
  android: "launcher_icon"
  ios: true
  image_path: "assets/icon/icon.png"
For image_path. Create a folder containing icons. Example assets/icon/icon.png

2. Run the package:
After setting up the configuration, all that is left to do is run the package.
Run at terminal
flutter pub get
flutter pub run flutter_launcher_icons
When this message appears, it means success:

3. Rename App
Android: …\android\app\src\main\AndroidManifest.xml

IOS: …\ios\Runner\Info.plist


