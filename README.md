# Flappy Bird Project

Simple Flappy Bird clone built with Pygame.

## Files
- `flappy bird.py` - Main game script
- `main.py` - Separate OpenCV face-detection script (not the game)
- `gallery/` - sprites and audio assets
- `.venv/` - local Python virtual environment

## Setup
1. Open terminal in project folder.
2. Create venv (if not already):
   - `python -m venv .venv`
3. Activate the venv:
   - Windows: `.venv\Scripts\activate`
4. Install dependencies:
   - `pip install pygame`

## Run
- `python "flappy bird.py"`

## Controls
- `Space` or `Up` to flap
- `Esc` or window close button to exit

## Notes
- This project also contains a small OpenCV face detection script in `main.py`.
- Game resources are under `gallery/sprites/` and `gallery/audio/`.
