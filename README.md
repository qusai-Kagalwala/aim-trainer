# 🎯 Aim Trainer

A fun and challenging aim training game built with Python and Pygame! Test your reflexes and improve your clicking accuracy with animated targets.

## 🎮 Features

- 🎯 **Dynamic Targets**: Targets appear randomly and grow/shrink with smooth animations
- ⏱️ **Real-time Stats**: Track your time, speed, hits, and remaining lives
- 🎨 **Bullseye Design**: Beautiful concentric circle targets with red and white rings
- 📊 **Performance Metrics**: Detailed end-game statistics including accuracy percentage
- 💀 **Lives System**: 3 lives to keep the challenge exciting
- 🌊 **Smooth Animation**: Targets pulse with growing and shrinking effects

## 🚀 Quick Start

### Prerequisites
Make sure you have Python installed, then install Pygame:
```bash
pip install pygame
```

### Installation & Run
1. 📥 Clone this repository:
   ```bash
   git clone https://github.com/qusai-Kagalwala/aim-trainer.git
   cd aim-trainer
   ```

2. ▶️ Run the game:
   ```bash
   python aim_trainer.py
   ```

## 🕹️ How to Play

1. 🖱️ **Click the targets** as they appear on screen
2. 🎯 **Hit the bullseye** before targets disappear to score points
3. ⏰ **Be quick!** Targets shrink and vanish if you're too slow
4. 💔 **Watch your lives** - miss 3 targets and it's game over!
5. 📈 **Improve your stats** - aim for higher speed and accuracy

## 📊 Game Stats

The game tracks several metrics to help you improve:
- **Time**: How long you've been playing
- **Speed**: Targets hit per second
- **Hits**: Total successful target clicks
- **Lives**: Remaining chances (starts with 3)
- **Accuracy**: Percentage of successful clicks

## ⚙️ Game Mechanics

- **Target Spawn**: New targets appear every 400ms
- **Target Size**: Starts small, grows to max size, then shrinks
- **Target Lifespan**: Targets disappear when they shrink to zero
- **Window Size**: 800x600 pixels
- **Frame Rate**: 60 FPS for smooth gameplay

## 🎨 Customization

Want to modify the game? Here are some key variables you can adjust in `aim_trainer.py`:

```python
# Timing
TARGET_INCREMENT = 400      # Time between new targets (ms)

# Difficulty
LIVES = 3                   # Number of lives
TARGET_PADDING = 30         # Safe zone from edges

# Visuals
WIDTH, HEIGHT = 800, 600    # Window dimensions
BG_COLOR = (0, 25, 40)     # Background color

# Target settings
MAX_SIZE = 30              # Maximum target radius
GROWTH_RATE = 0.2          # How fast targets grow/shrink
```

## 🎯 Tips for Better Aim

- 🎯 **Aim for the center** - you don't need pixel-perfect accuracy
- ⚡ **Click quickly** - targets don't stay at full size for long
- 👀 **Keep your eyes moving** - new targets can appear anywhere
- 🧘 **Stay calm** - rushing leads to misclicks and wasted lives
- 📈 **Practice regularly** - muscle memory improves over time

## 🛠️ Technical Details

- **Language**: Python 3.x
- **Framework**: Pygame
- **Architecture**: Object-oriented design with Target class
- **Graphics**: 2D circle rendering with layered colors
- **Input**: Mouse click detection with collision calculations

## 🤝 Contributing

Feel free to fork this project and submit pull requests! Some ideas for improvements:
- 🎵 Sound effects for hits/misses
- 🎮 Different game modes (speed mode, precision mode)
- 🏆 High score system with file persistence
- 🎨 Different target shapes and colors
- 📱 Mobile touch support

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Qusai Kagalwala**
- GitHub: [@qusai-Kagalwala](https://github.com/qusai-Kagalwala)

---

🎯 **Ready to test your aim? Clone and start training!** 🎯
