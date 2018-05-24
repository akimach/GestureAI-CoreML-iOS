# GestureAI-CoreML-iOS

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE) ![](https://img.shields.io/badge/platform-iOS-red.svg) ![](https://img.shields.io/badge/language-Swift%204.x-orange.svg) 

Hand-gesture recognizer using CoreML

## Demo

![demo](images/demo.gif)

## Screenshots

![screenshot-01](images/screenshot-01.jpg) ![screenshot-02](images/screenshot-02.jpg) ![screenshot-03](images/screenshot-03.jpg)

This app is using RNN(Recurrent Neural network) with CoreML on iOS11. The model recognizes the gesture as long as the center button is pressed.

Click [here](https://github.com/akimach/GestureAI) to read more about GestureAI.

## Install

1. Clone this repository.
2. Download `GestureAI.mlmodel` (Trained RNN model) from [here](https://goo.gl/avdMjD).
3. Open `GestureAI.xcodeproj`
4. Drag and drop `GestureAI.mlmodel` to Xcode.
5. Add `GestureAI.mlmodel` into **Compile Sources** in Build Phases.
6. Build and run.

# Guide To CoreML Models

See [likedan/Awesome-CoreML-Models](https://github.com/likedan/Awesome-CoreML-Models).

## Licence

[MIT](https://github.com/akimach/GestureAI-iOS/blob/master/LICENSE)

## Author

[Akimasa KIMURA](https://github.com/akimach)
