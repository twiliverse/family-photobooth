# 📸 Photobooth For family

A lightweight, browser-based photobooth inspired by the popular "Life Four Cuts" (인생네컷) studios found across South Korea. This application uses your device's webcam to capture four sequential images and formats them into a vertical, pastel-themed photo strip like you see in korea.

## Features

* **Webcam Integration:** Directly connects to the user's camera via the browser.
* **Classic 4-Cut Layout:** Automatically stacks four images into a vintage-style vertical strips.
* **Auto-Mirroring:** Flips the camera feed so users see themselves naturally, just like a mirror.
* **Timestamp Watermark:** Automatically adds the current date to the bottom of the photo strip once all four photos are taken.
* **Zero Dependencies:** Built entirely with plain HTML, CSS, and Vanilla JavaScript. No installations required.

## How to Run

1. Clone or download this repository.
2. Ensure you have a working webcam connected to your device.
3. Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge, Opera, Brave).
4. Grant the browser permission to access your camera when prompted.
5. Click the **Capture Photo** button four times each time one pic to fill your strip!

## Technologies Used

* **HTML5:** Page structure and Video/Canvas elements.
* **CSS3:** Flexbox layout and pastel UI styling.
* **JavaScript (ES6):** MediaDevices API (`getUserMedia`) for webcam access and Canvas API for image rendering.
