pitch-detector
==============

A pitch detector base on web audio.

Inspired by [cwilso/PitchDetect](https://github.com/cwilso/PitchDetect).
But provide more frinedly API.

## Usage

First you need require [AudioContext-MonkeyPatch](https://github.com/cwilso/AudioContext-MonkeyPatch).
Then *pitch-detector* It will set `window.pitchDetector`.
Then you can use `pitchDetector.startLiveInput` to toggle web audio and start detect.

After that, you get these:

```
pitchDetector.pitch
pitchDetector.note
pitchDetector.noteString
pitchDetector.detune
```

Also you can check the [demo page](https://github.com/dead-horse/pitch-detector/blob/master/demo.html) to see how to use it.

## License
MIT
