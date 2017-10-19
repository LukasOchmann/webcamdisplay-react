# Webcamdisplay-react
Display all your connected webcams on a single webpage.
Great for usability testing recordings and screencasts, stopwatch is included.

## Requirements
- A connected webcam / videoinput (wow!)
- A modern browser with [mediaDevices Web API](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices)

## Features
- Resizable and draggable timer
- Resizable and draggable webcam feeds
- Works offline

## Capture
- use any screensharing app like skype to broadcast
- Mac-users can use pre-installed quicktime to capture via "screencast" recording

## Tech
- Based on the awesome [react-boilerplate](https://github.com/react-boilerplate/react-boilerplate)
- Also includes a workflow for [electron](https://electron.atom.io/)

## Demo
See it working in action: [Click here](https://hamsterbacke23.github.io/webcamdisplay-react/)

## Local
1) Clone it

```bash
git clone https://github.com/hamsterbacke23/webcamdisplay-react.git
```
2) install dependencies and setup screensharing
  1. ```yarn install``` installs dependencies from yarn.lock/package.json
  2. ```yarn setup``` sets up ssl

2) run it
  ```npm start``` runs the App on https://localhost:3000
