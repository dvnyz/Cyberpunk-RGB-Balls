# RGB Balls That Follow Your Mouse Across Multiple Browsers
This project demonstrates an interactive web application where three RGB-colored balls (Red, Green, Blue) dynamically follow the mouse pointer. The movement of the balls is synchronized across multiple browser windows using the BroadcastChannel API, enabling real-time communication between tabs. Additionally, in a secondary browser window, the balls move in the opposite direction, creating a visually engaging and interactive experience.

## Features:
  Mouse Tracking: The three balls follow the mouse pointer in real-time.

- Multi-Browser Synchronization: Using BroadcastChannel, mouse movements are shared across browser windows.

- Reverse Movement: In secondary browser windows, the balls move in the opposite direction of the primary window's movement.

- Interactive Design: Smooth animations and vibrant RGB colors enhance user experience.

## Technologies Used:
- HTML & CSS: For structuring and styling the webpage.

- JavaScript: For implementing mouse tracking and inter-browser communication.

- BroadcastChannel API: To synchronize movements across multiple browser windows.

## How It Works:
  1. The primary browser window captures mouse movements using the mousemove event.
  2. The positions of the balls are updated dynamically based on the cursor's location.
  3. The BroadcastChannel API sends these coordinates to other browser windows.
  4. Secondary browser windows receive the data and animate the balls in reverse directions.
