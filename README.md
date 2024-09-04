# Air Dash

Air Dash is a simple 2D side-scrolling game built with Pygame. The player controls a plane, navigating through obstacles and collecting stars to increase their score.

## Game Features

- Side-scrolling gameplay with a continuously moving background
- Player-controlled plane that can fly up when the left mouse button is clicked or held
- Obstacles (rocks) that appear from both top and bottom of the screen
- Collectable stars that increase the player's score
- Score display
- Game over screen when the plane collides with rocks or the ground

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Ensure you have Python installed on your system.
2. Install Pygame by running:
   ```
   pip install pygame
   ```
3. Download the game files, including the Python script and all image/sound assets.

## File Structure

Ensure you have the following file structure:

```
air_dash/
│
├── air_dash.py
├── background.wav
│
├── images/
│   ├── background.png
│   ├── groundGrass.png
│   ├── rockGrass.png
│   ├── rockGrassDown.png
│   ├── starGold.png
│   ├── plane.png
│   ├── number0.png
│   ├── number1.png
│   └── ... (number2.png to number9.png)
│   └── textGameOver.png
```

## How to Play

1. Run the `air_dash.py` script:
   ```
   python air_dash.py
   ```
2. The game window will open, and the plane will start moving.
3. Click and hold the left mouse button to make the plane fly upwards.
4. Release the mouse button to let the plane descend.
5. Avoid colliding with rocks and the ground.
6. Collect stars to increase your score.
7. The game ends when the plane collides with an obstacle or the ground.

## Controls

- Left Mouse Button: Make the plane fly upwards

## Customization

You can easily customize various aspects of the game by modifying the variables at the beginning of the script:

- `game_width` and `game_height`: Change the size of the game window
- `fps`: Adjust the frame rate
- Image files: Replace the image files in the `images/` directory to change the game's appearance

## Credits

This game uses the following assets:
- Background music: "background.wav"
- Various image assets located in the `images/` directory

Make sure you have the rights to use these assets if you plan to distribute the game.

## License

[Include appropriate license information here]

## Contributing

[Include information about how others can contribute to the project, if applicable]

## Support

If you encounter any issues or have questions, please [provide contact information or links to where users can get support].
