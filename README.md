# 🐤 Clubinho Flappy

**Clubinho Flappy** is a simple and engaging Flappy Bird-style game created with HTML5 Canvas and JavaScript. Navigate through pipes, avoid collisions, and aim for the highest score!

## 📜 Features

- 🎮 **Interactive Gameplay**: Click, touch, or press to make the bird jump.
- 🌆 **Dynamic Environment**: Procedurally generated pipes with varying gaps.
- 🔊 **Sound Effects**: Enjoy audio feedback for actions like jumping and scoring.
- 🖼️ **Custom Graphics**: Background, bird, pipes, and other elements for a polished look.
- 🏆 **Victory Mode**: Reach the finish line to win!

## 🚀 Getting Started

### Prerequisites

- A modern web browser with support for HTML5 Canvas.
- Basic knowledge of hosting a local HTML file (e.g., double-click or use a local server).

### Installation

1. Clone or download the repository:
   ```bash
   git clone https://github.com/estivalet/clubinho-flappy/
   ```
2. Place the `assets/` folder alongside the `index.html` file to ensure all images and sounds load correctly.
3. Open `index.html` in your browser.

## 🎮 How to Play

1. **Start**: Click, touch, or press any key to begin the game.
2. **Controls**: 
   - Click or tap anywhere on the screen to make the bird jump.
   - Use keyboard keys (e.g., spacebar) for jumping.
3. **Objective**: Avoid pipes, reach the finish line, and score points by passing through obstacles.

## 🖼️ Assets

The following assets are used in the game:
- **Images**:
  - `bg.png` - Background image.
  - `bird.png` - Bird character.
  - `pipe.png` - Pipe obstacle.
  - `finish.png` - Finish line flag.
  - `win.png` - Winner banner.
- **Audio**:
  - `fly.mp3` - Jump sound effect.
  - `score.mp3` - Scoring sound effect.

Ensure all assets are located in the `assets/images/` and `assets/audios/` directories.

## 🛠️ Customization

- **Game Parameters**:
  - Adjust jump height (`JUMP_AMOUNT`) and gravity (`ACCELERATION`) in the script for a different difficulty level.
  - Modify pipe gaps and placement by tweaking the `addPipes()` function.
- **Graphics**:
  - Replace assets in the `assets/` folder with your own images and sounds.

## 📸 Screenshots

### 🏁 Gameplay
![Gameplay Screenshot](title.png)

### 🎉 Victory Screen
![Victory Screenshot](assets/img/win.png)

## 📜 License

This project is licensed under the [MIT License](LICENSE).

## 🙏 Acknowledgements

- Inspired by the classic Flappy Bird game.
- Thanks to the open-source community for resources and support.

## 🤝 Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request.

