# OvertoneSynth
A synthesizer for playing the overtone series in the browser.

## Background
An overtone series is a sequence of musical tones in which each frequency is an integer multiple of the first tone. Eg, if the first tone in a sequence is 110hz (A2), the next notes in the overtone series would be 220hz (A3), 330hz (E4-ish), 440hz(A4), 550hz(C#5-ish) and so on. Overtone series occur naturally when a fundamental is resonated or reflected, and as such a sound's reflected overtones determine much of what a listener percieves as the "character" of a sound. Western harmony derives many of its structures from the mathematical relationships of these series. This synthesizer plays the overtone series that comes from a fundamental note of 300hz (which we might call "D half sharp"). As such, it will be equally out of tune with all traditional instruments.

## Implementation
This page uses 16 oscillators from JS' Web Audio API. Each of them is attached to its own gain node, and keypresses turn the gain to 0 (no sound) or 1 (full sound). Original styling is set by CSS, but then altered by JS as the user plays. 

## Where can this be played?
It is hosted on my portfolio here: https://benjamingordoncody.github.io/overtonesynth/
