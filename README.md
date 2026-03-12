# Typing Pulse Visualizer

## Overview

Typing Pulse Visualizer is a small experimental web project that turns a user’s typing activity into a live animated pattern on the screen. As the user types, the system measures the typing rhythm and generates a colorful spiral animation that reacts to the speed and frequency of keystrokes.

The goal of this project is to explore how simple human interactions (like typing) can be converted into dynamic visual patterns. Instead of just displaying text, the application visualizes typing energy as motion and color.

## Idea Behind the Project

Every person has a unique typing rhythm. Some people type slowly and steadily, while others type very fast. This project captures that rhythm and translates it into a visual pulse.

The faster the user types:

* the animation moves faster
* the colors change dynamically
* the visual pattern becomes more energetic

In this way, typing behavior becomes a form of digital art.

## Features

* Real-time spiral animation that reacts to typing
* Color-changing visual patterns
* Key press counter
* Typing speed estimation (Words Per Minute)
* Simple typing style classification
* Light sound feedback for each key press

## Technologies Used

* **HTML** – page structure
* **CSS** – basic styling and layout
* **JavaScript** – animation, typing detection, and interaction
* **HTML Canvas API** – used to draw the animated spiral pattern

## How It Works

1. The program listens for keyboard input.
2. Each time a key is pressed:

   * the key counter increases
   * typing speed is calculated
   * animation energy increases.
3. The animation loop continuously redraws the spiral pattern using the Canvas API.
4. The spiral rotates faster when typing activity increases.

## How to Run the Project

1. Download or clone the project files.
2. Open the `index.html` file in any modern web browser.
3. Start typing on the keyboard.
4. Watch how the spiral visualization reacts to your typing rhythm.

No installation or server setup is required.

## Possible Future Improvements

* Add more visual patterns besides the spiral
* Store typing sessions and compare patterns
* Add different sound styles for different typing speeds
* Allow users to export their typing visualization as an image or GIF

## Author

Created as a creative experiment to visualize human typing patterns in an interactive way.
