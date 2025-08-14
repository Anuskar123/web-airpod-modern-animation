# Web AirPod Modern Animation

A sleek, scroll-triggered AirPod sequence animation using HTML, CSS, and JavaScript.

## Demo

Include a link or screenshot here if you have a live demo or GIF.

## Features

- Smooth frame-by-frame animation of AirPods tied to scroll position
- Preloading of image sequence for performance optimization
- Responsive canvas setup ensures consistent display across browsers/views

## Tech Stack

- **HTML5** – Structure & canvas setup  
- **CSS3** – Layout, styling, and fullscreen canvas centering  
- **JavaScript** – Scroll handling, image preloading, and frame updates

## How It Works

1. A `<canvas>` element centered on the page remains fixed while scrolling.
2. `script.js` preloads a sequence of AirPod images.
3. On scroll, the script calculates the current scroll fraction and displays the corresponding frame using `canvas.drawImage()` :contentReference[oaicite:1]{index=1}.
4. Rendering is done efficiently using `requestAnimationFrame()` to avoid jank.

## Getting Started

1. Clone the repo:
 git clone https://github.com/Anuskar123/web-airpod-modern-animation.git

Open index.html in your browser (no server needed).
Scroll to see the AirPod animation in action.
