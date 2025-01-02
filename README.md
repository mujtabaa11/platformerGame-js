# Platformer Game

This is a simple platformer game where the player controls a character that can move left, right, and jump. The goal is to reach checkpoints placed along the platforms. The game includes basic gravity, platform interactions, and checkpoint detection.

## Features

- **Player Movement**:
  - Use the **Arrow Keys** (Left and Right) to move the player character.
  - Use the **Arrow Up** key or **Spacebar** to make the player jump.
  - Gravity affects the player's vertical position, pulling them down after a jump.
  
- **Platforms**:
  - Platforms are placed at various heights. The player can land on them to avoid falling.
  - If the player falls below the visible area, the game can be restarted.

- **Checkpoints**:
  - The player can reach and claim checkpoints.
  - Once a checkpoint is reached, it "disappears," and the player can continue from there.
  - A message appears when a checkpoint is reached.

- **Collision Detection**:
  - The game detects when the player collides with platforms and checkpoints.
  - The player cannot fall through platforms or move off the screen.

## How to Play

1. Click the **Start** button to begin the game.
2. Use the **Left Arrow** and **Right Arrow** keys to move the player horizontally.
3. Use the **Up Arrow** key or **Spacebar** to jump.
4. Land on the platforms and avoid falling off the screen.
5. Reach the checkpoints to save your progress.

### Controls

- **Arrow Left**: Move left
- **Arrow Right**: Move right
- **Arrow Up / Spacebar**: Jump

## Technologies Used

- **HTML5 Canvas**: Used for rendering the game world and objects.
- **JavaScript**: Used for game logic, player movement, collision detection, and animation.
- **CSS**: Used for styling the game interface and screens.

## Future Enhancements

- **Animation**: Add animations for the player (walking, jumping, etc.).
- **Sound Effects**: Integrate sound effects for actions like jumping, landing, and reaching checkpoints.
- **Score System**: Implement a score that increases as the player reaches checkpoints or completes levels.
- **Obstacles and Enemies**: Add obstacles or enemies that the player must avoid or defeat.

## License

This training project is licensed under the MIT License.
