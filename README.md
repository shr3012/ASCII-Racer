
# ASCII Racer 🚗💨

A retro, console-based car racing game built entirely with C++! Navigate your car using simple ASCII visuals, avoid obstacles, and test your reaction skills in this fast-paced game.


## Key Features 🚀

- Console Game Development: Created a fun, nostalgic game environment using C++ and Windows API. 
- Real-Time Input Handling: Smooth left/right car movement controlled by dynamic keystrokes (A for left, D for right)
- Collision Detection: Detects car collisions with enemies to deliver an immediate game-over experience.
- Random Enemy Generation: Unpredictable enemy positions make each game challenging and engaging.
- Score Tracking: Earn points for every enemy avoided, with live score updates.
- Retro ASCII Design: Cars and obstacles are rendered using minimalistic ASCII characters for a nostalgic feel.
- Optimized Performance: Efficient screen rendering and game mechanics ensure seamless gameplay without lag.


## How to Play 🎮

- Start the Game: Select "Start Game" from the menu.
- Control Your Car: Use the A key to move left, and the D key to move right.
- Avoid Obstacles: Dodge enemy cars as they approach to increase your score.
- Game Over: If you hit an enemy, the game will end.


## Lessons Learned

This project taught me the fundamentals of **console game development** using C++ and Windows API, focusing on **real-time input handling** for smooth car movement and **collision detection** for game logic. I implemented **randomization** to generate unpredictable enemy positions and used **efficient rendering** techniques like `gotoxy()` to manage dynamic visuals. Additionally, I optimized the game's performance and integrated **score tracking** for a seamless user experience.


## Tech Stack
- **Language:** C++
- **API:** Windows API for console control (e.g., gotoxy(), SetConsoleCursorPosition)
- **Libraries:** <windows.h>, <conio.h>, <time.h>
- **IDE/Compiler:** Any C++ environment supporting Windows-based development (e.g., Dev-C++, Code::Blocks, Visual Studio)


## Deployment

To deploy this project run

```bash
  git clone https://github.com/yourusername/ascii-racer.git
```

Compile and run the code in a C++ environment with Windows API support.