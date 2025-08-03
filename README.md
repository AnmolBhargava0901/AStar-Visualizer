
# 🌟 AStar Visualizer - Interactive Pathfinding Algorithm Demo

**AStar Visualizer** is an intuitive and educational tool that demonstrates the **A\*** (A-Star) pathfinding algorithm in real time. Built using **Python** and **Pygame**, this app visualizes how smart algorithms find the shortest route in complex environments. Perfect for students, teachers, and developers.

---

## 📸 Demo Preview

<!-- 🚧 Add a screenshot or GIF below -->
![Screenshot Placeholder]![test pic](https://github.com/user-attachments/assets/38fee9f0-d813-4186-944f-4a0393996218)


<!-- Optionally add more media -->
<!-- ![Screenshot2](assets/screenshot2.png) -->

---

## 🚀 Features

- 🧠 **Implements the A\*** (A-Star) algorithm
- 🧱 Real-time grid-based visual simulation
- 🖱️ Mouse interactions to add barriers, start/end nodes
- ⌨️ Keyboard shortcuts to control execution
- 🎯 Displays visited, open, and final path cells
- 🧩 Modular and beginner-friendly code
- 🪄 Lightweight and fast — perfect for learning!

---

## ⚙️ How It Works

The A\* algorithm uses:

- **G(n)**: Cost from start to current node
- **H(n)**: Heuristic — estimated cost from current node to goal (Manhattan Distance)
- **F(n) = G(n) + H(n)**: Total estimated cost

The algorithm:
1. Starts from the `Start Node`
2. Explores neighboring nodes with the lowest F score
3. Updates scores dynamically and tracks visited paths
4. Stops when it reaches the `End Node`
5. Backtracks to form the shortest path

---

## 🎮 How to Use

### ▶️ Run the Script

```bash
python astar_visualizer.py
````

### 🕹️ Controls

| Action                 | Key / Mouse |
| ---------------------- | ----------- |
| Add Start / End / Wall | Left Click  |
| Erase Cell             | Right Click |
| Start A\* Algorithm    | Spacebar    |
| Clear Grid             | `C` Key     |

---

## 🎨 Grid Color Key

| Color     | Meaning      |
| --------- | ------------ |
| 🟧 Orange | Start Node   |
| 🔵 Blue   | End Node     |
| ⬛ Black   | Barrier/Wall |
| 🔴 Red    | Closed Set   |
| 🟢 Green  | Open Set     |
| 🟣 Purple | Final Path   |

---

## 🧰 Requirements

* Python 3.7 or later
* Pygame

Install dependencies:

```bash
pip install pygame
```

---

## 📁 Project Structure

```
AStarVisualizer/
├── astar_visualizer.py    # Main script
├── assets/                # (Optional) Image/GIFs
├── README.md              # Documentation
```

---

## 💡 Use Cases

* 🏫 **Education**: Teach how A\* and heuristic search work.
* 🧪 **Experimentation**: Try different grid sizes and heuristics.
* 🎮 **Game Dev**: Prototype AI pathfinding for grid-based games.
* 🔍 **Visualization**: Great tool for presentations and learning algorithms interactively.

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-new`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-new`)
5. Open a Pull Request

---


## ⭐️ Show Your Support

If you liked the project:

* Give it a ⭐ on GitHub
* Share it with friends or classmates
* Use it in your next project or teaching session!

