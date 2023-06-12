# jweb-face-landmarker

A self contained example demonstrating how to use MediaPipe FaceLandmarker with Max's `jweb`

![Max patcher example of jweb-face-landmarker](./jweb-face-landmarker.gif)

## Features

MediaPipe FaceLandmarker provides 52 features (blendshapes) per face, which are mapped to `live.slider` objects in the example patcher.

|      |              |                |   |   |
|------|--------------|----------------|---|---|
| Eyes | browDownLeft | browDownRight | | |
| Eyes | browOuterUpLeft | browOuterUpRight | | |
| Eyes | cheekSquintLeft | cheekSquintRight | | |
| Eyes | eyeBlinkLeft | eyeBlinkRight | | |
| Eyes | eyeLookDownLeft | eyeLookDownRight | | |
| Eyes | eyeLookInLeft | eyeLookInRight | | |
| Eyes | eyeLookOutLeft | eyeLookOutRight | | |
| Eyes | eyeLookUpLeft | eyeLookUpRight | | |
| Eyes | eyeSquintLeft | eyeSquintRight | | |
| Eyes | eyeWideLeft | eyeWideRight | | |
| Brow, Cheek  | browInnerUp | cheekPuff | | |
| Nose  | noseSneerLeft | noseSneerRight | | |
| Mouth | jawLeft | jawRight | jawForward | jawOpen |
| Mouth | mouthClose | mouthFunnel | mouthPucker | |
| Mouth | mouthRollLower | mouthRollUpper | mouthShrugLower | mouthShrugUpper |
| Mouth | mouthDimpleLeft | mouthDimpleRight | | |
| Mouth | mouthFrownLeft  | mouthFrownRight  | | |
| Mouth | mouthLeft       | mouthRight       | | |
| Mouth | mouthLowerDownLeft | mouthLowerDownRight | | |
| Mouth | mouthPressLeft | mouthPressRight | | |
| Mouth | mouthSmileLeft | mouthSmileRight | | |
| Mouth | mouthStretchLeft | mouthStretchRight | | |
| Mouth | mouthUpperUpLeft | mouthUpperUpRight | | |



## Resources

This example is inspired by [an example by Rob Ramirez](https://github.com/robtherich/jweb-mediapipe), which is in turn inspired by [MediaPipe in JavaScript](https://github.com/LintangWisesa/MediaPipe-in-JavaScript). 

