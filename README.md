# 🌸 An Infinite Garden for Her

A romantic interactive web experience built as a heartfelt digital gift for your loved one.

The website combines a living flower garden with a scrapbook-style photo collage, allowing visitors to plant beautiful flowers anywhere on the screen while being surrounded by cherished memories.

---

## ✨ Features

### 📸 Memory Polaroid Frame
- Randomly rotated polaroid photographs
- Responsive layout across different screen sizes
- Dedicated:
  - Top photo row
  - Left photo columns
  - Right photo columns
- Layered depth effect using z-index stacking
- Soft blur and opacity adjustments for a dreamy aesthetic

### 🌹 Interactive Flower Garden
- Click anywhere on the screen to plant a flower
- Multiple flower varieties:
  - Lily
  - Rose
  - Sunflower
  - Tulip
  - Generic decorative flower
- Smooth stem growth animation
- Natural leaf generation
- Flower blooming effect
- Collision avoidance to reduce flower overlap

### ✨ Atmospheric Effects
- Twinkling stars
- Floating sparkles
- Dark romantic night-sky background
- Soft glow effects
- Smooth animations

### 💌 Personalized Message Area
- Large center title
- Dedicated heartfelt message section
- Protected layout zone preventing photos from covering the message

---

## 📂 Project Structure

```
Flower Website/
│
├── index.html
│
└── images/
    ├── us1.jpeg
    ├── us2.jpeg
    ├── us3.jpeg
    ├── ...
    └── us15.jpeg
```

---

## 🚀 How to Run

### Option 1: Open Directly

Simply open:

```
index.html
```

in your browser.

### Option 2: Local Server (Recommended)

Using VS Code Live Server:

1. Install the Live Server extension.
2. Right-click `index.html`
3. Select:

```
Open with Live Server
```

---

## 🖼 Adding More Photos

Place additional images inside:

```
images/
```

Then update the photo array:

```javascript
const photos = [
  'images/us1.jpeg',
  'images/us2.jpeg',
  ...
];
```

The layout automatically adjusts based on the number of photos.

---

## 🎨 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- HTML Canvas API

No external frameworks are required.

---

## 🌙 Design Philosophy

The project was designed to feel like:

- A romantic scrapbook
- A memory wall
- A midnight flower garden

The goal is to create a space where memories and emotions coexist:

- Photos represent shared moments.
- Flowers represent love that continues to grow.
- The night sky represents timelessness.

Every click plants a new flower, symbolizing the idea that love keeps growing indefinitely.

---

## ❤️ Dedication

Created with love for someone special.

*"An infinite garden, because some feelings never stop growing."*