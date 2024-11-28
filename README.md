# Snake Game 🎮

A simple and classic Snake Game built in **C++**! This project demonstrates fundamental game programming techniques using console-based graphics and keyboard inputs.

---

## 📖 Overview
The Snake Game is a fun retro game where the player controls a snake to eat randomly placed fruits on the grid. The snake grows longer with each fruit it eats, and the player earns points. The game ends when the snake collides with itself or the wall.

This project is a lightweight, console-based implementation, perfect for beginners learning C++ programming or game development.

---

## 🎮 Features
- **Console-based gameplay:** Lightweight and runs directly in the terminal.
- **Keyboard controls:** Use `W`, `A`, `S`, and `D` to navigate.
- **Dynamic scoring:** Earn 10 points for each fruit eaten.
- **Adjustable speed:** Slow down or speed up the snake by modifying the code.
- **Random fruit placement:** The fruit spawns at random locations each time.
- Remove the comment in the code to get experince of another mode.
---

## 🕹️ How to Play
1. Use the following keys to control the snake:
   - **W:** Move Up
   - **A:** Move Left
   - **S:** Move Down
   - **D:** Move Right
   - **X:** Exit the game
2. The snake moves automatically in the current direction.
3. Collect fruits (`F`) to score points and grow longer.
4. Avoid hitting the walls or the snake's body—doing so ends the game.

---

## 💻 Setup Instructions

### 1. Clone the Repository
Clone the project to your local machine:

```bash
   git clone https://github.com/SupunPrabodha/Simple-Snake-Game.git
   cd SnakeGame
```

### 2. Compile the Code
Use a C++ compiler to build the program. For example:

- With g++ (Linux/Windows):
```bash
   g++ SnakeGame.cpp -o SnakeGame
   ./SnakeGame
```

- Using Visual Studio:
1. Open Visual Studio and create a new Console Application.
2. Replace the auto-generated main.cpp file with SnakeGame.cpp.
3. Build the project and run it (F5 or Ctrl + F5).

### 3. Run the Game
Enjoy playing the Snake Game in your terminal or console!

## 📷 Screenshot

![image](https://github.com/user-attachments/assets/a3c5e54c-029b-4210-ad1f-3d973bf0e530)

![image](https://github.com/user-attachments/assets/b4ba5a20-2ad9-4796-8b3b-0f5324748ce1)

![image](https://github.com/user-attachments/assets/85b1b6a4-5ddf-4721-a54b-e58575482e92)


## 🔧 Customization

1. Change Speed:
Adjust the delay in the game loop by modifying the **Sleep(milliseconds)** function in the **main()** loop. For example:

```bash
Sleep(100); // Slows down the snake (100ms delay)
```

Lower values make the game faster, while higher values slow it down.

## 🛠️ Requirements
- A C++ compiler (e.g., **g++, Visual Studio, or Dev-C++**).
- Windows OS (due to the use of `Sleep()` and `conio.h`).
- Terminal or console to run the program.

## 🤝 Contributing
Contributions are welcome! Feel free to:

- Open issues for bugs or enhancements.
- Submit pull requests with your improvements or ideas.

## 📄 License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the license terms.

## ✨ Author

Developed by `SupunPrabodha`.
Feel free to reach out for collaboration or feedback!
