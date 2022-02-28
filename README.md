# Flutter NFC Compatibility Check

## Supported NFC Format

| Platform | Supported NFC Tags               |
| -------- | -------------------------------- |
| Android  | **NDEF:**  A, B, F, V, BARCODE   |
| iOS      | **NDEF:** NFC TYPE 1, 2, 3, 4, 5 |



## Installation

Add to pubspec.yaml:

```yaml
dependencies:
  flutter_nfc_compatibility: ^0.0.1
```


```dart
import 'package:flutter_nfc_compatibility/flutter_nfc_compatibility.dart';
```

## How to use

### Android setup

Add those two lines to your `AndroidManifest.xml` on the top

```xml
<uses-permission android:name="android.permission.NFC" />
<uses-feature
        android:name="android.hardware.nfc"
        android:required="true" />
```


