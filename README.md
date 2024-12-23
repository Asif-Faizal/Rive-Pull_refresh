# Custom Pull-to-Refresh Animation with Rive in Flutter

This Flutter project demonstrates a custom pull-to-refresh animation using Rive and its state machines to reflect different states during the pull-to-refresh process. The project integrates Rive's powerful animation capabilities to create a smooth and visually appealing refresh interaction.

## Features

Custom Pull-to-Refresh: The pull-to-refresh interaction is animated with a Rive animation.
State Machines: Rive state machines are used to reflect different states of the pull-to-refresh, such as "idle," "pulling," "refreshing," and "completed."
Smooth Integration: The Rive animation is smoothly integrated with Flutter's RefreshIndicator.

## Installation

### Clone this repository:
```bash
git clone https://github.com/Asif-Faizal/Rive-Pull_refresh.git
```

### Navigate to the project directory:
```bash
cd flutter-pull-to-refresh-rive
```

### Install the dependencies:
```bash
flutter pub get
```

Make sure you have an active Rive account and use their tools to design your pull-to-refresh animation. Export the .riv file and place it in the assets directory.

Add the Rive package to your pubspec.yaml:
```yaml
dependencies:
  flutter:
    sdk: flutter
  rive: ^0.8.0
```

Update your pubspec.yaml to include the assets directory:
```yaml
flutter:
  assets:
    - assets/animations/pull_to_refresh.riv
```
