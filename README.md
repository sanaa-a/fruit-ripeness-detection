# Fruit Ripeness Detection on Raspberry Pi

Real-time ripe vs unripe classification for apples and bananas, running on a Raspberry Pi with a camera.

Published at ICSEDI 2026 (IEEE):
https://ieeexplore.ieee.org/document/11568334

## What it does
- Takes live camera input on a Raspberry Pi
- Classifies the fruit as ripe or unripe using CNN and SVM models (OpenCV + TensorFlow)
- Shows the result on screen in real time

## Results
| Fruit  | Ripe   | Unripe |
|--------|--------|--------|
| Apple  | 81.21% | 77.73% |
| Banana | 83.17% | 45.82% |

Most errors on unripe fruit came from camera color bias. We improved this by changing the lighting setup and using a better camera.

## Dataset
Fruits-360 (Kaggle)

