# Live Object Detector

Point your webcam at anything and this app draws labelled bounding boxes around the objects it recognises, live, with a confidence score for each.

**[Live demo →](https://ayanprakash35.github.io/almost-all-object-detector/)**

## Features

- Real-time detection with the **COCO-SSD** model (80 everyday object classes)
- Bounding boxes and confidence percentages drawn over the video
- Live count of how many objects are in view

## How to use

Open the page, allow camera access, and hold objects up to the camera.

## Built with

[p5.js](https://p5js.org/), [ml5.js](https://ml5js.org/) (COCO-SSD)

## Run it locally

The webcam needs a page served over `http://localhost` (not opened as a file):

```bash
git clone https://github.com/Ayanprakash35/almost-all-object-detector.git
cd almost-all-object-detector
python3 -m http.server 8000
```

Then open <http://localhost:8000> and allow camera access.

Everything runs in the browser. No video leaves your machine.
