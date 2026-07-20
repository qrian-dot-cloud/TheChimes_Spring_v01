# The Chimes - Spring v01

**The Chimes - Spring v01** is a prototype system for live audiovisual performance controlled through hand gestures. It uses MediaPipe hand tracking in TouchDesigner, OSC communication, and sound synthesis in Max/MSP to generate a blooming flower form, pollen-like particles, ambient sound, harmony, and spatial textures in real time.

## How to Run

1. Open the TouchDesigner project file.
2. Make sure the camera is connected and MediaPipe hand tracking is active.
3. Open the Max/MSP patch.
4. Turn on audio in Max/MSP.
5. Check that OSC is being sent from TouchDesigner to Max/MSP on the correct port.
6. Perform in front of the camera using hand gestures.

## Gesture Controls

- Left-hand pinching activates small, fast randomised frequencies resembling moving particles.
- Right-hand pinching activates the main voiced pitch with wind-like noise.
- The left thumb’s height changes the low-cut frequency and shapes the intensity of wind-like noise.
- Pinching with both hands opens harmonic layers.
- Right-hand height controls randomised pitch changes in D Mixolydian mode.
- The distance between the hands shapes spatial and spectral textures.
- Gestures trigger noise, shaping a blooming flower form and expanding pollen-like particles.

## Technical Notes

The MediaPipe hand-tracking base patch was provided as Week 7 teaching material by Olivier Pasquet. The gesture mapping, OSC routing, TouchDesigner visual translation, and Max/MSP synthesis system were developed and adapted for this project.

The sound is generated through synthesis in Max/MSP. No sampled sounds or pre-made musical material are used in the submitted version.

## Requirements

- TouchDesigner
- Max/MSP
- Webcam
- Audio output / headphones / speakers

## References and AI Declaration

References, source acknowledgements, and the Generative AI Declaration are included in the submitted PDF documentation.

## Author

Kyuri Kim (QRIAN)  
MA Computational Arts  
Goldsmiths, University of London  
2026
