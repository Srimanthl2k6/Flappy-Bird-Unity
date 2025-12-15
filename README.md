#  Flappy Bird With Unity 

![Gameplay](gameplay.gif)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Mac%20%7C%20Android-blue?style=for-the-badge)

> A high-speed endless runner where reflexes are your only survival tool.

![Gameplay Demo](gameplay.gif)

## 🎮 About The Game

**[Your Game Name]** is a fast-paced arcade survival game built in Unity. The goal is simple: navigate through an endless obstacle course without crashing. 

This project demonstrates the implementation of 2D physics, procedural generation, and game state management in Unity.

### ✨ Key Features

* **Infinite Procedural Levels:** No two runs are ever the same.
* **Physics-Based Movement:** Smooth and responsive flight mechanics.
* **Dynamic Difficulty:** The game tests your precision as you progress.
* **High Score System:** Challenge yourself to beat your personal best.

---

## 🕹️ Controls

| Action | Input |
| :--- | :--- |
| **Jump / Fly** | `Spacebar` or `Left Mouse Click` |
| **Pause** | `Esc` |

---

## 🛠️ Installation & Setup

Want to modify the game or run it locally? Follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
    ```

2.  **Open in Unity**
    * Launch Unity Hub.
    * Click **Add** and select the cloned folder.
    * Open the project (Recommended Version: Unity 2019.4 or later).

3.  **Play**
    * Open the scene: `Assets/Scenes/Game.unity`.
    * Press the ▶️ **Play** button at the top of the editor.

---

## 📂 Project Structure

Here is a quick overview of the main scripts to help you navigate the code:

```csharp
Assets/
├── BirdScript.cs        // Handles physics and user input
├── PipeSpawnerScript.cs // Manages procedural obstacle generation
├── LogicScript.cs       // Controls score, game over state, and UI
└── MainMenu.cs          // Handles scene transitions
