# 🎮 Shadow Puzzle (Tangram) – CSS Only Game

**Shadow Puzzle** is an interactive game inspired by the classic **Tangram** puzzle, built entirely using **HTML** and **CSS** — no JavaScript involved!

👉 [Play the game on CodePen](https://codepen.io/smirosljevic/pen/gbOBMqm)

## 🧩 About the Game

The goal of the game is to arrange shapes so they match the shadow of the target figure. Each figure is made up of several geometric pieces that can be rotated and dragged into position.

This game is:

- 📐 **100% CSS** – no JavaScript!
- ⚡ Lightweight and fast – great for learning or showcasing CSS skills.
- 📱 **Responsive** – works well on both desktop and mobile devices.
- 🧠 Designed to train logical thinking and spatial orientation.

## 🚀 Technologies

- HTML5
- CSS3 (Grid, Flexbox, Transforms, Custom Properties)
- CSS Variables for dynamic styling
- Media queries for responsive behavior

## 📸 Screenshot

![Shadow Puzzle Screenshot](/screenshot_tanagram.png)

# 🧠 Tutorial: How This Works

This game demonstrates how far CSS can go when creatively used. Here's how the main logic is built:

### 🎯 Game Mechanics (CSS Only!)

- The **shadow** is a silhouette image (pseudo-element or low-opacity layer).
- Each puzzle **piece** is styled with `clip-path`, `transform`, and `position`.
- **CSS `:checked` or `:focus-within`** states enable interactivity and simulate selection.
- **Rotation** and movement are controlled with buttons, labels, and sibling selectors.
- Everything is **semantic HTML**: no div soup!

### ♻️ Reusable Logic with SCSS

Using SCSS mixins and variables, the game becomes modular and maintainable.

- `@mixin rotate($angle)`: easily applies rotation to pieces
- `@mixin piece($shape, $color)`: generates the clip-path and styles

# 🧩 Tangram Puzzle – CSS Architecture Diagram

This diagram represents the internal structure and SCSS architecture behind the **Tangram Puzzle** game built entirely with HTML and CSS (no JavaScript!).

![Tangram CSS Diagram](tanagram.drawio.svg)

---

## The diagram highlights:

- Modular SCSS structure
- Mixins for shapes and logic
- Separation of layers (interactive pieces vs. shadow background)

## 🛠️ How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/sladjanasto/shadow-puzzle
   cd shadow-puzzle
   ```
