 🐍 Snake Game + Auto Launcher

> **Classic Snake gameplay** with an automatic secondary game launcher – no Python required.  
> Just double‑click and play!

---

## 📦 What's Inside

This package contains:

- **`SnakeGame.exe`** – The main Snake game (compiled, standalone)
- **`game.exe`** – Your secondary game (launched automatically alongside Snake)
- **`snake_game.py`** – Source code (optional, for reference)

---

## 🚀 How to Use

1. **Place both executables** in the **same folder**:
📁 YourGameFolder/
├── SnakeGame.exe
└── game.exe

text

2. **Double‑click `SnakeGame.exe`** to start.

3. **Two windows will open**:
- 🐍 Snake game window
- 🎮 Your `game.exe` window

✅ Both games run **simultaneously**!

---

## 🎮 Snake Game Controls

| Key          | Action                    |
|--------------|---------------------------|
| `↑` Up Arrow | Move snake **up**         |
| `↓` Down Arrow | Move snake **down**     |
| `←` Left Arrow | Move snake **left**     |
| `→` Right Arrow | Move snake **right**    |
| `R`          | Restart after game over   |
| `ESC`        | Quit the game             |

---

## ✨ Features

- ✅ **No Python installation** – runs standalone on Windows
- ✅ **No extra dependencies** – everything included
- ✅ **Automatic game.exe launcher** – launches both games together
- ✅ **Score tracking** – see how long you survive
- ✅ **Smooth graphics** – classic Snake experience
- ✅ **Portable** – copy the folder anywhere

---

## 🛠 Troubleshooting

### ❌ `game.exe` does not launch

- Make sure `game.exe` is **in the same folder** as `SnakeGame.exe`.
- Check if your antivirus is blocking `game.exe` – add an exception if needed.
- Try running `SnakeGame.exe` **as Administrator** (right‑click → *Run as administrator*).

### ❌ `SnakeGame.exe` does not start

- Update your **graphics drivers**.
- Run as Administrator.
- Ensure Windows is up to date (Windows 10 / 11 recommended).

### ❌ Both games lag or crash

- Close other resource‑heavy applications.
- Restart your PC.

---

## 📁 File Information

| File            | Size (approx.) | Description                          |
|-----------------|----------------|--------------------------------------|
| `SnakeGame.exe` | ~12.5 MB       | Main Snake game executable           |
| `game.exe`      | varies         | Your secondary game (not provided here) |
| `snake_game.py` | ~8 KB          | Source code (for reference / modification) |

> 💡 `game.exe` is **not** included – you must supply your own. The launcher simply runs whatever executable you name `game.exe` in the same folder.

---

## 🧪 Example Folder Structure
C:\MyGames\SnakePack/
│
├── SnakeGame.exe ← Main Snake game
├── game.exe ← Your second game (e.g., Pong, Tetris, etc.)
└── snake_game.py ← (optional) source code

text

Double‑click `SnakeGame.exe` → both start at once.

---

## 📝 Notes

- The launcher uses Windows `CreateProcess` – it does **not** modify any registry or system files.
- You can rename `game.exe` to anything else, but you would then need to modify the launcher source. The compiled version **expects** the exact name `game.exe`.
- To run only Snake without the launcher, you would need a separate build (not included).

---

## 🎉 Enjoy!

**Happy gaming!**  
*Feed the snake, dodge the walls, and enjoy both games at once.*

--- 

For issues or suggestions, please open an issue on the repository (if applicable) or contact the author.
