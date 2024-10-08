Eye-Following Cursor Animation
This project demonstrates an interactive eye-following effect, where two animated eyes track the position of the mouse cursor as it moves across the screen. The pupils move dynamically based on the mouse's position, creating a fun and engaging visual effect.

Features
Interactive Eyes: The pupils of the eyes follow the mouse cursor as it moves across the screen.
Smooth Animation: The movement of the pupils is subtle and responsive to the mouse movement, creating a natural and smooth tracking effect.
Simple and Lightweight: Built using only HTML, CSS, and JavaScript, with no external libraries or frameworks.
How It Works
HTML Structure:
The structure consists of two "eye" elements, each containing an "eyeball" and a "pupil". The onmousemove event triggers a JavaScript function to move the pupils as the cursor moves.
CSS Styling:
The eyes and pupils are styled with border-radius to make them circular.
The .eye is the outer white part, and the .pupil is the black center that moves based on the cursor's position.
JavaScript:
The move(event) function calculates the relative position of the mouse cursor to the center of each eyeball and updates the transform property of the pupil, moving it accordingly.
The amount of movement is scaled down to create a subtle effect (/10), ensuring the pupils don’t move too far out of the eyeballs.
