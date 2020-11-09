# Log

Init the test app:
```console
npx react-native init TestApp --template react-native@^0.63.2
cd TestApp
npx react-native-windows-init --overwrite
```
Test if app builds:
```console
npx react-native run-windows
```

Init the module:
```console
npx create-react-native-module --module-name "MyLibrary" MyLibrary
cd MyLibrary
yarn install
yarn upgrade react@16.13.1 --dev
yarn upgrade react-native@0.63.2 --dev
```

Do [Creating the Visual Studio Project / Solution](https://microsoft.github.io/react-native-windows/docs/native-modules-setup#creating-the-visual-studio-project--solution) step of the docs.

