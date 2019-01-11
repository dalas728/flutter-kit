# Flutter Starter Kit - App Store Example

A starter kit for beginner learns with Bloc pattern, RxDart, sqflite, Fluro and Dio to architect a flutter project. This starter kit build an App Store app as a example

![App Store Flutter Demo](https://i.ibb.co/wpQmxNf/Screen-Shot-2019-01-11-at-4-16-08-PM.png)

## Feature
- Bloc Pattern
- Navigate pages by [Fluro](https://github.com/theyakka/fluro)
- Local cache by using [sqflite](https://github.com/tekartik/sqflite)
- Restful api call by using [Dio](https://github.com/flutterchina/dio)
- Loading Network Image
- Localization by using Flutter i18n plugin
- Environment Config based on different project flavour (Development, Staging and Production)
- Build pojo by using json_serializable

## Install

1. Follow flutter [official setup guide](https://flutter.io/docs/get-started/install) to set up flutter environment
2. Install Flutter i18n plugin into Android Studio
    >Preference > Plugins > Browse repositories > Type ‘Flutter i18n’  > Install > Restart Android Studio

## Config
1. Add a run config to run demo

![Config](https://i.ibb.co/sgq2mTL/Screen-Shot-2019-01-11-at-6-13-32-PM.png)


## Useful Command
Generate json serialize adn deserialize functions

> flutter packages pub run build_runner build --delete-conflicting-outputs


## Reference

#### From other platform?
- [Flutter for Android developers](https://flutter.io/docs/get-started/flutter-for/android-devs)
- [Flutter for iOS developers](https://flutter.io/docs/get-started/flutter-for/ios-devs)
- [Flutter for React Native developers](https://flutter.io/docs/get-started/flutter-for/react-native-devs)
- [Flutter for web developers](https://flutter.io/docs/get-started/flutter-for/web-devs)
- [Flutter for Xamarin.Forms developers](https://flutter.io/docs/get-started/flutter-for/xamarin-forms-devs)

#### Learn Widget
- [Series of flutter widget of the week](https://www.youtube.com/playlist?list=PLOU2XLYxmsIL0pH0zWe_ZOHgGhZ7UasUE)
- [Series of Flutter Widgets 101](https://www.youtube.com/playlist?list=PLOU2XLYxmsIJyiwUPCou_OVTpRIn_8UMd)

#### Bloc Pattern
- [Architect your Flutter project using BLOC pattern](https://medium.com/flutterpub/architecting-your-flutter-project-bd04e144a8f1)

#### Json Serialization
- [JSON and serialization](https://flutter.io/docs/development/data-and-backend/json)

#### Localization
- [Flutter: internationalization tutorials: Part 3— Android Studio plugin](https://medium.com/@datvt9312/flutter-internationalization-tutorials-part-3-android-studio-plugin-8604e2dc90f0)
- [讓 Flutter App 支援多國語系的開發流程](https://medium.com/@zonble/%E8%AE%93-flutter-app-%E6%94%AF%E6%8F%B4%E5%A4%9A%E5%9C%8B%E8%AA%9E%E7%B3%BB%E7%9A%84%E9%96%8B%E7%99%BC%E6%B5%81%E7%A8%8B-ceb31532e2e1)

#### Flavouring
- [Flavoring Flutter](https://medium.com/@salvatoregiordanoo/flavoring-flutter-392aaa875f36)
