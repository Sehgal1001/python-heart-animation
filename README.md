# ❤️ Python Heart Animation

A beautiful red heart animation created using **Python Turtle Graphics** and mathematical equations. This project uses Python's `turtle` module to draw a heart-shaped curve with a black background and vibrant red color.

A simple yet creative Python project that demonstrates the combination of mathematics, programming, and graphics.

## ✨ Features

- ❤️ Beautiful mathematical heart shape.
- 🔴 Attractive red-colored heart.
- 🖤 Black background for a clean visual effect.
- 🐢 Built using Python Turtle Graphics.
- 📐 Uses sine and cosine mathematical functions.
- ⚡ Smooth drawing animation.
- 💻 Simple and beginner-friendly Python code.

## 🛠️ Technologies Used

- **Python 3** – Programming language.
- **Turtle Graphics** – Drawing and animation.
- **Math Module** – Mathematical calculations using sine and cosine functions.

## 📂 Project Structure

```text
python-heart-animation/
│
├── redheart.py
└── README.md
```

## 🚀 Getting Started

Follow these steps to run this project on your computer.

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/python-heart-animation.git
```

### 2. Navigate to the Project Folder

```bash
cd python-heart-animation
```

### 3. Run the Python File

```bash
python redheart.py
```

The Turtle Graphics window will open and display the animated red heart.

## 📦 Requirements

- Python 3.x
- Turtle module (included with standard Python installations)
- Math module (built into Python)

No additional external libraries are required.

## 🧠 How It Works

The project uses mathematical equations to generate the coordinates of a heart shape.

### Heart X-coordinate

```python
def hearta(k):
    return 15 * math.sin(k) ** 3
```

### Heart Y-coordinate

```python
def heartb(k):
    return (12 * math.cos(k)
            - 5 * math.cos(2*k)
            - 2 * math.cos(3*k)
            - math.cos(4*k))
```

These equations calculate the X and Y coordinates required to create a heart-shaped curve.

The Turtle module moves through these coordinates and draws the heart using red color on a black background.

## 🎯 Learning Outcomes

Through this project, I explored:

- Python functions and loops.
- Mathematical functions using the math module.
- Turtle Graphics and screen customization.
- Coordinate systems and geometric shapes.
- Basic animation concepts.
- Combining mathematics with programming.

## 🔮 Future Improvements

Some features that could be added in future versions:

- Animated heart beating effect.
- Customizable heart colors.
- Background music.
- Personalized text inside the heart.
- Interactive graphical interface.
- Adjustable animation speed.

## 👨‍💻 Author

**Aniket Sahgal**

- GitHub: [@Sehgal1001](https://github.com/Sehgal1001)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/aniket-sahgal-297a67276)

## ⭐ Support

If you like this project, please consider giving it a ⭐ on GitHub.

Your support motivates me to build more creative projects!

---

**Made with ❤️ using Python**
