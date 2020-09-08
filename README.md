# Delaylay
Delay Plugin (VST3 and Audio Unit)

V. 0.1 (08.09.2020)

[Get the release here.](https://github.com/tob-har/Delaylay/releases/)

<img src="https://github.com/tob-har/Delaylay/blob/master/delaylay-screenshot.png" alt="Delaylay Plugin" width="500"/>


How to install:
Download the release, extract the .zip file, put the .vst3 and .components files into the plugin folder of your system.
In your DAW you find the plugins under /VST3/Tobias Hartmann/ and /AU/Tobias Hartmann/


Delaylay is a stereo delay plugin (VST3 and Audio Unit).
It features:
- Input Volume (0-1)
- Dry-Wet Mix (0-1)
- Feedback (0-1)
- Three Time Controller
  - 1ms-2000ms Slider: set a delay time between 1ms and 2sec
  - TAP: Tap in a tempo (needs 3 to 4 taps)
  - Time 0-127: Change those values for three types of delay at hand with one value:
    - 0-67 chromatically pitched resonating delay
    - 68-120 41ms to 1200ms delay times
    - 121-127 DAW BPM synced delay times (see Info Box for details!)
- Hi-Pass Filter (0-1)
- Lo-Pass Filter (0-1)
- Delay Mode (0-3)
  - Mode 0: 2 channel delay line (left and right)
  - Mode 1: Stereo Mode 1 
  - Mode 2: Stereo Mode 2 (adds ping pong, half time, slight detune)
  - Mode 3: Stereo Mode 3 (adds Ping Pong, half time, -12 semitones, detune)

The INFO box shows the current state of the delay engine
- Delay time in ms and BPM
- if the plugin is tempo-synced to the BPM of your DAW
- the status, what controller is setting the delay time (Milliseconds, TAP, Chromatic, Synced in 4th,4th-triplets, 8th, etc. upt to 32th)

ENJOY ;-)



---


Published under MIT License

Copyright 2020 Tobias Hartmann 

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions: The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software. 

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

