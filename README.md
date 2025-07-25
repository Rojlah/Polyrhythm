# Polyrhythm Visualizer

This is a web-based polyrhythm visualizer that creates mesmerizing patterns and corresponding musical tones using HTML5 Canvas and the Web Audio API. Each "ball" orbits at a different speed on its own elliptical track, and a sound is played every time a ball completes a "round" (half-ellipse).

## Features

* Dynamic Visuals: Multiple balls animating on concentric elliptical tracks.
* Polyrhythmic Sounds: Each ball plays a distinct tone when it completes a cycle, creating complex polyrhythms.
* Interactive Design: Built with vanilla JavaScript, HTML, and CSS (inline for canvas styling).
* Customizable: Easily adjust parameters like number of tracks, speeds, and sound frequencies.

## How it Works

The project consists of three main JavaScript files:

* sound.js: Handles the generation of simple sine wave sounds using the Web Audio API. It includes a `playSound` function that takes a frequency and duration.
* track.js: Defines the `Track` class, which represents an elliptical path. It calculates ball positions along the track.
* ball.js: Defines the `Ball` class, representing each animated orb. It manages the ball's movement, drawing, and triggers sounds based on its position on the track.
* index.html: The main HTML file that sets up the canvas, includes the JavaScript files, and initializes the tracks and balls.

## Setup and Usage

To run this project locally:

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/polyrhythm-visualizer.git](https://github.com/YourUsername/polyrhythm-visualizer.git)
    cd polyrhythm-visualizer
    ```
    (Replace `YourUsername` and `polyrhythm-visualizer` with your actual GitHub username and repository name.)

2.  Open `index.html`:
    Simply open the `index.html` file in your web browser. You should see the animation and hear the sounds.

## Project Structure
├── index.html
├── sound.js
├── track.js
└── ball.js
