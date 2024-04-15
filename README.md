## Installation

Add `horizontal_week_calendar:` to your **pubspec.yaml** dependencies then run `flutter pub get`

```
 dependencies:
  horizontal_week_calendar:
```

## Import

Add this line to import the package.
```
import 'package:horizontal_week_calendar/horizontal_week_calendar.dart';
```


## How to use

```dart
HorizontalWeekCalendar(
  onDateChange: (date) {
    setState(() {
      selectedDate = date;
    });
  },
),
```

## Preview

![Horizontal Week Calendar](https://github.com/chandabdullah/horizontal_week_calendar/blob/main/assets/android.png =100x20)

