# Floating Eye Animation

## Project Description

Floating Eye is a simple interactive web animation where two eyes follow the user's mouse movement in real time.

The project demonstrates basic DOM manipulation, mouse event handling, CSS styling, and geometric calculations using JavaScript.

When the user moves the mouse, both eyes rotate to face the cursor position.

---

## Features

* Real-time mouse tracking
* Dual animated eyes
* Minimal dark interface
* Lightweight (no external libraries)
* Responsive centered layout

---

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript

---

## Project Structure

```
project-folder/
│
├── index.html
├── style.css
└── script.js
```

---

## File Overview

### index.html

Defines the structure of the page.
It includes a container with two elements representing the eyes.

Referenced file: 

Key structure:

* A centered container
* Two div elements with class "eyes"
* External CSS and JS linked

---

### style.css

Handles layout and visual design.

Referenced file: 

Main styling details:

* Full-screen centered layout
* Black background
* Circular white eyes
* Inner pupil created using ::before pseudo-element
* Subtle shadows for depth

---

### script.js

Handles mouse movement and rotation logic.

Referenced file: 

Core logic:

* Adds a mousemove event listener to the body
* Calculates center position of each eye
* Uses Math.atan2() to determine angle between cursor and eye center
* Rotates the eye element using CSS transform

---

## How It Works

1. The browser detects mouse movement.
2. JavaScript calculates the angle between the mouse position and each eye.
3. Each eye rotates toward the cursor using a transform rotate value.
4. The result is a tracking effect where both eyes follow the pointer.

---

## How to Run

1. Place all three files in the same folder.
2. Open index.html in a web browser.
3. Move your mouse across the screen to see the animation.

No installation or dependencies are required.

---

## Possible Improvements

* Add eyelid animation
* Add blinking effect
* Improve pupil realism
* Add mobile touch support
* Add smooth easing transitions

---

## Preview Description

When opened in a browser:

* The screen background is black.
* Two white circular eyes are centered horizontally and vertically.
* As the user moves the mouse, both eyes rotate to face the cursor.
* The motion feels smooth and responsive.

The project is ideal for beginners learning DOM events, transformations, and interactive animations.
