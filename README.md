# Snake-Game
This project implements a classic Snake game using Python and Pygame. The player controls the snake to eat food, causing it to grow in length, while avoiding collisions with itself.

## Features
- Classic Snake Gameplay: Control the snake to eat food and grow longer. Avoid running into the walls or the snake's own body.
- Graphics: Implemented using the Pygame library, providing a visual representation of the snake, food, and game grid.
- Scoring: Displays the current score based on the number of food items eaten.
## Files
- **main.py**: The main driver file responsible for handling user input, game logic, and displaying the game interface.
- **Snake**: Contains the logic for the snake's movement, direction, and growth.
- **Food**: Contains the logic for the food's position and randomization.
- **Grid Drawing**: Manages the drawing of the game grid.
## Installation
1. **Clone the Repository**: 
   ```bash
   git clone <repository-url>
2. **Navigate to the Project Directory:**
     ```bash
       cd snake-game
3.**Install Dependencies:**
     
      pip install pygame
3.Run the Game:
      python main.py
## Usage
1. **Run the Game**: 
   - Execute `main.py` to start the game.
2. **Playing**:
   - Use the arrow keys to control the direction of the snake:
     - Up Arrow: Move up
     - Down Arrow: Move down
     - Left Arrow: Move left
     - Right Arrow: Move right
   - The goal is to eat the food that appears on the grid, which causes the snake to grow in length.
   - Avoid running into the walls or the snake's own body.
   - The game will display the current score at the top left corner.
## Requirements
- Python 3.x
- Pygame Library
## Credits
This project was developed by Mohammed Faraz Kabbo.
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



