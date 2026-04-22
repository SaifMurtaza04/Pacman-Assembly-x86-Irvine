# 👾 Pac-Man (x86 Assembly / Irvine32)

A recreation of the classic **Pac-Man game** built entirely in **x86 Assembly language** using the **Irvine32 library**.
This project demonstrates low-level programming concepts including memory management, keyboard input handling, and sound integration.

---

## 🎮 Features

* 👾 Classic Pac-Man gameplay mechanics
* ⌨️ Real-time keyboard input handling
* 🔊 Sound effects integration:

  * Game start sound
  * Pacman movement & chomp
  * Death sound
  * Game over sound
* 🧱 Maze-based movement system
* 💀 Collision detection (walls, enemies)
* 🎯 Score tracking system

---

## 📁 Project Structure

```id="a1kz7x"
.
├── test.asm              # Main assembly source code
├── *.wav                 # Sound effect files
│   ├── pacman_beginning.wav
│   ├── pacman_chomp.wav
│   ├── pacman_death.wav
│   ├── gamewon.wav
│   ├── losing.wav
│   └── ...
├── COAL Lab2.vcxproj     # Visual Studio project file
├── COAL Lab2.vcxproj.filters
├── COAL Lab2.vcxproj.user
├── Debug/                # Build files
├── x64/                  # Build files
```

---

## 🛠️ Technologies Used

* **x86 Assembly Language**
* **Irvine32 Library**
* **MASM (Microsoft Assembler)**
* **Visual Studio**

---

## ⚙️ Setup & Installation

### 🪟 Requirements (Windows Only)

* Visual Studio
* MASM (Microsoft Macro Assembler)
* Irvine32 Library

---

### 🔧 Steps to Run

1. Install **Irvine32 library** and configure it with Visual Studio
2. Open the project file:

```id="p9q2ls"
COAL Lab2.vcxproj
```

3. Build the project (Ctrl + Shift + B)
4. Run the program (F5)

---

## 🎯 Controls

| Key        | Action       |
| ---------- | ------------ |
| Arrow Keys | Move Pac-Man |
| ESC        | Exit Game    |

---

## 🧠 Concepts Demonstrated

* Low-level memory manipulation
* Register-based computations
* Interrupts and system calls
* Real-time input handling
* Sound playback in Assembly
* Game loop implementation without high-level abstractions

---

## 🔊 Sound System

The game uses `.wav` files for immersive feedback:

* Game start
* Eating (chomp)
* Death
* Winning / Losing

---

## 🚧 Limitations

* Platform dependent (Windows only)
* Limited graphics (console-based rendering)
* Hardcoded game logic and layout

---

## 🚀 Future Improvements

* Add ghost AI behavior 👻
* Implement levels and difficulty scaling
* Improve rendering (colors, smoother movement)
* Add score persistence
* Optimize assembly routines

---

## 👨‍💻 Author

**Muhammad Saif Murtaza**
FAST-NUCES

---

## 📜 License

This project is open-source and available under the MIT License.
