# Anki Android with voice control
I try to make only minimal changes to the original Anki Android while implementing the functionalities I want. Click the microphone icon that enable the voice control.

![alt text](https://github.com/Tuo-ZHANG/Anki-Android-with-voice-control/blob/master/showcase.png)

## Build
Please use Android studio bumblebee to build the project. Also consider to build the release apk instead of the debug apk as the debug version is quite slow.

## Supporting features
- [x] say "replay" or "media" to play the audio again
- [x] say "flip" to show the answer of the flashcard
- [x] say "again", "hard", "good" or "easy" to finish the current card and moves to the next card
- [x] say "undo" to undo the last card you have studied
- [x] say "suspend" to suspend the current card
- [x] when use Card Browser in context menu, search through all decks instead of through previous selected deck
- [x] when open Card Browser, show all cards instead of previously selected deck
- [x] some changes of UI layout

## Reference
https://github.com/ankidroid/Anki-Android

https://github.com/alphacep/vosk-android-demo