<div align="center">

![Fast Shopping logo][app-logo]

# Fast Shopping

[![Build status][build-status-badge]][build-status-link]
[![App Codecov][app-codecov-badge]][codecov-link]
[![Bloc Codecov][bloc-codecov-badge]][codecov-link]

[![Get it on Google Play][google-play-badge]][google-play-link]
[![Get it on F-Droid][fdroid-badge]][fdroid-link]
[![Explore it on AppGallery][appgallery-badge]][appgallery-link]

</div>

**Fast Shopping** is a mobile application developed with simplicity in mind. It allows you on having a simple set of shopping lists, that you can easily manage. It contains **no** ads. Targetted to everyone who wants a simple app to get the job done. Not limited to tech-savy users.

![App screenshots][app-screenshots]

## Goal

This application was made to resolve a certain problem in a certain way. 

There are many people that don't want to use a voice assistant and find other apps available on the market too overwhelming, too complex, bloated with features, bloated with ads or simply overengineered for their simple problem. In the past, you would get yourself a piece of paper and a pen and write down the stuff you need to buy, so you can read it while being in the market. **Fast Shopping** is an application that does exactly that and only that. Reducing number of taps to a minimum and offering a very readable interface.

## Building

**Note:** Use Flutter `stable` channel.

```bash
git clone git@github.com:Albert221/FastShopping.git && cd FastShopping
flutter pub get
flutter run --flavor foss # or just launch from VS Code
```

After you've edited your [freezed][freezed] models:

```bash
# You may also use `watch` instead of `build`
flutter pub run build_runner build --delete-conflicting outputs
```

## Translating

[![Localization at Crowdin][crowdin-badge]][crowdin-link]

## Available languages

There are current or past translation maintainers in the parentheses next to each language.

- English (me)
- Polish (me)
- Macedonian ([@MatejMecka])
- German ([@kojid0], [@divadsn])
- Russian ([@rikishi0071])
- French ([@ashledombos])

[app-logo]: android/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png

[build-status-badge]: https://img.shields.io/github/workflow/status/Albert221/FastShopping/Flutter%20test
[build-status-link]: https://github.com/Albert221/FastShopping/actions?query=workflow%3A%22Flutter+test%22
[app-codecov-badge]: https://img.shields.io/codecov/c/gh/Albert221/FastShopping?logo=codecov&flag=app&label=app%20coverage
[bloc-codecov-badge]: https://img.shields.io/codecov/c/gh/Albert221/FastShopping?logo=codecov&flag=bloc&label=bloc%20coverage
[codecov-link]: https://codecov.io/gh/Albert221/FastShopping

[google-play-badge]: assets/google-play-badge.png
[google-play-link]: https://play.google.com/store/apps/details?id=me.wolszon.fastshopping
[fdroid-badge]: assets/fdroid-badge.png
[fdroid-link]: https://www.f-droid.org/en/packages/me.wolszon.fastshopping/
[appgallery-badge]: assets/appgallery-badge.png
[appgallery-link]: https://appgallery.huawei.com/#/app/C103706177
[app-screenshots]: fastlane/metadata/android/en-US/images/featureGraphic.png

[freezed]: https://pub.dev/packages/freezed
[TRANSLATING.md]: TRANSLATING.md

[crowdin-link]: https://crowdin.com/project/fast-shopping
[crowdin-badge]: https://badges.crowdin.net/badge/dark/crowdin-on-light.png

[@matejmecka]: https://github.com/MatejMecka
[@kojid0]: https://github.com/kojid0
[@divadsn]: https://github.com/divadsn
[@rikishi0071]: https://github.com/rikishi0071
[@ashledombos]: https://github.com/ashledombos
