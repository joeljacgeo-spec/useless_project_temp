# Sablaski 🎯

A browser-based voice-controlled game inspired by the meme energy of Hashir. The project turns microphone input into gameplay: you shout to move a flying character upward, dodge pipes, and explore a playful set of sound-based mini-games.

## Team
### Team Name
Cyberpunkz

### Members
- Team Lead: Joel Jacob - College of Engineering Trivandrum
- Member 2: Aashish David Abraham - College of Engineering Trivandrum

## Project Description
Sablaski is a silly but creative voice-controlled web game built with plain HTML, CSS, and JavaScript. It combines audio input, canvas animation, and browser APIs to create a fun experience where the user's voice acts as the controller.

The project includes:
- a flappy-style game controlled by microphone volume
- a sound challenge with dB tracking and leaderboard entries
- a mood detection section that matches text input to a Hashire-style character image
- ambient game music and sound effects loaded from the assets folder

## The Problem (that doesn't exist)
The world needed another way to turn random noise into a competitive game.

## The Solution (that nobody asked for)
We built a browser game where your voice becomes the input device, making the experience chaotic, funny, and surprisingly playable.

## Features
- Voice-activated flappy gameplay
- Microphone permission handling and calibration
- Real-time sound meter with threshold tuning
- Game audio and death effects
- Scream challenge mode with peak dB score tracking
- Mood-based image generator using text input
- Fully client-side, no backend required

## Tech Stack
### Software
- HTML5
- CSS3
- JavaScript (Vanilla)
- Web Audio API
- Canvas API

### Hardware
- None required for the browser game
- Microphone access is required for the voice-control modes

## Project Structure
```text
.
├── assets/
│   ├── angryhashir.png
│   ├── Athiradi.mp3.mpeg
│   ├── cryinghashir.png
│   ├── cutehashir.png
│   ├── feduphashir.png
│   ├── hungryhashir.png
│   ├── Kazhivundoda.mp3
│   ├── masshashir.png
│   └── Sheblaski.mp3.mpeg
├── index.html
├── main.html
├── README.md
└── .git/
```

> Note: the main gameplay is implemented in `main.html`. `index.html` appears to be a placeholder or empty shell and is not the active app file.

## How It Works
1. The user clicks the microphone button and allows browser audio access.
2. The app calibrates the ambient room noise.
3. The sound meter calculates a dB-like reading after subtracting the background noise.
4. In the Flappy mode, loudness above a threshold gives the bird lift.
5. In the challenge mode, the app records the loudest sound peak over a fixed time.
6. In the mood section, a word or phrase is matched to a Hashire-style character image.

## Installation
No package install is required.

### Option 1: Open directly
- Open `main.html` in a browser.

### Option 2: Use a local static server
```bash
cd "c:\Users\jacge\OneDrive\Documents\GitHub\useless_project_temp"
python -m http.server 8000
```
Then open:
```text
http://localhost:8000/main.html
```

## Usage
- Allow microphone permission when prompted.
- Click the calibration button to set a quiet-room baseline.
- Start the game and make noise to control the character.
- Visit the sound challenge tab to record a peak dB score.
- Use the mood tab to type a feeling and display the corresponding Hashire image.

## Screenshots
### Game screen
![Game screen](https://github.com/user-attachments/assets/8920b256-2ba8-4988-b824-5351134eb4bd)

### Mood panel
The user can type a mood such as happy, angry, hungry, or sad to see a matching Hashire-inspired image.

### Sound meter
The app shows live microphone input, background noise calibration, and threshold-based controls.

## Demo Notes
This project is designed as a playful browser demo rather than a production game engine. It focuses on experimentation, creative audio interaction, and meme-inspired visual design.

## Team Contributions
- Joel Jacob: Project lead, game logic, and project direction
- Aashish David Abraham: Design and supporting development

## Credits
Made with ❤️ at TinkerHub Useless Projects.

![Static Badge](https://img.shields.io/badge/TinkerHub-24?color=%23000000&link=https%3A%2F%2Fwww.tinkerhub.org%2F)
![Static Badge](https://img.shields.io/badge/UselessProjects--26-26?link=https%3A%2F%2Ftinkerhub.org%2Fevents%2F1M8ORET9A1%2Fuseless-projects-3.0)

