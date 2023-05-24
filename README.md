# MobCalc
Calculator for Mobile project<br>
Made in Android Studio - Flutter<br>
Android language - Kotlin<br>
iOS language - Swift<br>
Platforms - Android, iOS<br>
<code style="color : red">Requires "rxdart: 0.27.1" in pubspec.yaml Dependencies</code><br>
Every next Task is updated version of the last<br>
Task 4 contains Task 3 which contains Task 2, etc<br>

<details>
<summary>Task 2 Basic calculator UI (lib)</summary>
<br>
Contains 3 dart files:<br>
  1) main.dart - Responsible for starting the app<br>
  2) calculator_app.dart - Defines the MyApp class<br>
  3) calculator.dart - Contains the Calculator widget<br>
  x) Refer to "Task 2 Calculator preview.jpg" for preview
</details>
<details>
<summary>Task 3 Basic calculator logic (lib)</summary>
<br>
  Contains 4 dart files:<br>
  1) main.dart - Responsible for starting the app<br>
  2) calculator_app.dart - Defines the MyApp class<br>
  3) calculator.dart -> calculator_screen.dart - Responsible for the UI and user input. Communicates with the CalculatorController to handle the calculator logic<br>
  4) calculator_controller.dart - Logic for handling numbers, operators, and calculating results<br>
  x) Requires rxdart: 0.27.1 in pubspec.yaml dependencies under flutter:<br>
  dependencies:<br>
  flutter:<br>
    sdk: flutter<br>
  rxdart: 0.27.1<br>
</details>

[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
<details>
<summary>Task 4 Kilometer to Mile converter in your calculator (lib)</summary>
<br>
Contains previous 4 dart files + 1 new for kilo to miles and back:<br>
  5) converter_sceen.dart (new) - switches to new screen. Converts kilometers to miles and back.
  x) Refer to "Task 4 Kilo to Miles preview.jpg" for preview
</details>
<details>
<summary>Task 5 Add history and persistence to your app (lib)</summary>
<br>
Placeholder
</details>
<details>
<summary>Task 6 Add equation support for your calculator (lib)</summary>
<br>
Placeholder
</details>
<details>
<summary>Task 7 Add Firestore support to your app (lib)</summary>
<br>
Placeholder
</details>
