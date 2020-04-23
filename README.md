# end_credits

[![pub](https://img.shields.io/badge/pub-1.0.0+1-blue)](https://pub.dev/packages/end_credits)
![end_credits](https://github.com/pblinux/end_credits/workflows/end_credits/badge.svg?branch=master)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![style: effective dart](https://img.shields.io/badge/style-effective_dart-40c4ff.svg)](https://github.com/pblinux/end_credits)

Show a simple end credits screen in your Flutter app.

<img src="https://raw.githubusercontent.com/pblinux/end_credits/master/images/end_credits.gif" alt="drawing" style="width:200px;"/>

## Getting Started

```dart
EndCredits(
    sections,
    backgroundColor: Colors.black,
    curve: Curves.linear,
    delay: Duration(seconds: 1),
    speedFactor: normalSpeedFactor,
);
```

You need to pass an array of Section:
```dart
Section(title: 'Cast', roles: [
    Role(name: 'Role 1', crew: [Responsable('John Doe')])
])
```

You can customize the text style of:
- Section
- Crew
- Role

There are 3 predefined speed factors, but you can pass a custom `double` value
- Slow
- Normal
- Fast


