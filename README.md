# DOOM-style-Game-main

# Doom-Style Game in Python

Welcome to the **Doom-Style Game** project! This is a Python-based game inspired by classic first-person shooters like Doom. This README file provides an overview of the project, its features, usage, and contribution guidelines.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Contributing](#contributing)
6. [License](#license)
7. [Acknowledgements](#acknowledgements)

## Project Overview

The **Doom-Style Game** is a 3D first-person shooter built using Python. It showcases various aspects of game development, including real-time rendering, basic AI, and interactive environments. The game features:

- **First-Person Perspective**: Navigate through a 3D environment with a classic FPS control scheme.
- **Level Design**: Explore intricately designed levels with obstacles and enemies.
- **Combat System**: Engage in combat with various enemies using a range of weapons.
- **Rendering Engine**: Implements a basic 3D rendering engine for displaying game environments.

## Features

- **3D Graphics**: Utilizes Python libraries for rendering 3D graphics.
- **Real-Time Movement**: Supports smooth real-time player movement and camera controls.
- **Enemy AI**: Basic enemy AI to challenge players.
- **Weapon System**: Multiple weapons with unique characteristics.
- **Sound Effects**: Dynamic sound effects for enhanced immersion.
- **Level Progression**: Complete levels with increasing difficulty.

## Usage

To run the game, execute the main Python script:

```bash
python main.py
```

The game window will open, and you can start playing by using the keyboard and mouse controls. Refer to the in-game instructions for control details.

### Controls

- **W, A, S, D**: Move forward, left, backward, and right.
- **Mouse Movement**: Look around.
- **Left Click**: Shoot.
- **R**: Reload weapon.
- **Esc**: Pause/Menu.

## Configuration

You can customize game settings by editing the `config.json` file located in the root directory. This file includes options for:

- **Resolution**: Set the game window resolution.
- **Controls**: Customize key bindings.
- **Audio**: Adjust volume levels.

Example `config.json`:

```json
{
  "resolution": {
    "width": 800,
    "height": 600
  },
  "controls": {
    "move_forward": "W",
    "move_backward": "S",
    "turn_left": "A",
    "turn_right": "D"
  },
  "audio": {
    "volume": 0.8
  }
}
```

## Contributing

We welcome contributions to improve the **Doom-Style Game**! To contribute:

1. **Fork the Repository** and create a new branch.
2. **Make Your Changes** and test thoroughly.
3. **Submit a Pull Request** with a detailed description of your changes.

Please ensure your code adheres to the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- **[Pygame](https://www.pygame.org/)**: Used for handling game graphics and input.
- **[PyOpenGL](http://pyopengl.sourceforge.net/)**: Utilized for 3D rendering.
- **Inspiration from Classic FPS Games**: For the overall design and mechanics.

Thank you for checking out the **Doom-Style Game** project! We hope you enjoy playing it as much as we enjoyed creating it. If you have any questions or feedback, feel free to reach out through the issues section of this repository.

---

Feel free to adjust any specifics or add more details as needed!
