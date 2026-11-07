# Tip Calculator — InternCircle Project 02

A responsive Flutter tip calculator built to meet the requirements in the InternCircle Project 02 learner guide.

## Features

- Bill amount input using a numeric `TextField`
- Tip percentage `Slider` from 0% to 30%
- People counter with plus and minus `IconButton`s
- Live calculations using `StatefulWidget` and `setState`
- Safe input parsing with `double.tryParse`; empty or invalid input is treated as 0
- People count cannot go below 1
- Currency values are formatted to two decimal places
- Reset button

## Run locally

1. Install Flutter and verify it with `flutter doctor`.
2. Open this folder in VS Code or Android Studio.
3. Run `flutter pub get`.
4. Run `flutter run`.

## Run in DartPad

1. Open https://dartpad.dev/?null_safety=true
2. Select Flutter mode if it is not already selected.
3. Replace the starter code with the contents of `lib/main.dart`.
4. Press Run and test the app.

## Required test case

| Input | Value |
|---|---:|
| Bill amount | 1000 |
| Tip percentage | 10% |
| People | 4 |
| Tip amount | 100.00 |
| Total bill | 1100.00 |
| Tip per person | 25.00 |
| Total per person | **275.00** |

## Before submitting

- [ ] Entering a bill updates the result immediately.
- [ ] Empty or invalid input does not crash the app.
- [ ] Tip slider moves between 0% and 30%.
- [ ] Minus button never reduces people below 1.
- [ ] All displayed amounts have two decimal places.
- [ ] The 1000 / 10% / 4 people test gives 275.00 per person.
- [ ] Add a screenshot of the running app showing the sample calculation.

## Submission items

The learner guide asks for a DartPad link, a screenshot with a sample calculation, and the test case results. You can keep this source code in GitHub and include the public repository link in your task submission. Also include your DartPad link if the dashboard asks for it.
