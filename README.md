pitch-detector
==============

a pitch detector base web audio

Inspired by [cwilso/PitchDetect](https://github.com/cwilso/PitchDetect).
But provide more frinedly API.

## Usage

It will set `window.pitchDetector`.
Then you can use `pitchDetector.startLiveInput` to use web audio and start detect.

After that, you get these:

```
pitchDetector.pitch
pitchDetector.note
pitchDetector.noteString
pitchDetector.detune
```
## License
MIT
