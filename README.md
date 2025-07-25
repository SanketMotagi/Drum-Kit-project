# Drum Kit Project

A fun interactive drum kit web application that lets you play drum sounds using either mouse clicks or keyboard keys.

## Overview

This project creates a virtual drum kit with different percussion instruments that can be played through the browser. Each drum is represented by a button on the screen and mapped to a specific keyboard key.

## Features

- 7 different drum sounds (tom drums, snare, crash cymbal, and kick bass)
- Responsive to both mouse clicks and keyboard presses 
- Visual feedback with button animations
- Custom styling and drum kit visuals

## How It Works

### HTML Structure (index.html)
- Creates a drum kit interface with 7 buttons
- Each button has:
  - A unique class (w, a, s, d, j, k, l) for keyboard mapping
  - The "drum" class for shared styling
  - Letter display for visual reference

### CSS Styling (styles.css)
- Custom styling for drum buttons with:
  - Unique background images for each drum type
  - Consistent size and border styling
  - Press animation effects
- Responsive layout with centered alignment
- Custom fonts and color scheme

### JavaScript Logic (index.js)
- Event listeners for:
  - Mouse clicks on drum buttons
  - Keyboard key presses
- Sound playback system using the Audio API
- Button animation for visual feedback
- Key functions:
  - `makeSound()`: Plays the appropriate drum sound
  - `buttonAnimation()`: Adds pressed effect to buttons

## How to Use

1. Click on any drum button or press the corresponding key (w, a, s, d, j, k, l)
2. The drum will play its sound and show a brief animation
3. Combine different drums to create your own beats

## Technical Details

- Uses HTML5 Audio API for sound playback
- CSS animations for visual feedback
- Event delegation for handling multiple drum buttons
- Timeout function for managing animation states

The project demonstrates DOM manipulation, event handling, and audio playback in a fun, interactive way that's suitable for both desktop and mobile use.
