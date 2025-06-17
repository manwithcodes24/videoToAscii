## 🎥📜 Video to ASCII – p5.js Style!

Turn your **camera feed into a living ASCII art stream** using the power of **p5.js**!  
This project is a fun exploration of computer vision, character mapping, maths and creative coding.

![image](https://github.com/user-attachments/assets/2d03a61c-bdca-4cc0-b02e-87742bf62a41)

---

## ✨ What It Does

- Captures **live webcam feed** 🧑‍💻
- Converts each pixel's brightness to a **corresponding ASCII character**
- Displays an animated, real-time **ASCII video stream**
- Fully browser-based using **p5.js**

---

## 🌟 Live Demo

> video-to-ascii-six.vercel.app
---

## 🛠 Tech Stack

- 🎨 **[p5.js](https://p5js.org)** for rendering & camera input
- 🧮 Brightness mapping algorithm
- 🔠 ASCII character set for visual conversion

---

## 📷 How It Works

1. Accesses your webcam using `createCapture(VIDEO)`
2. Shrinks the video resolution to optimize performance
3. For each pixel:
   - Calculates grayscale brightness
   - Maps brightness to an ASCII character (`@`, `#`, `S`, `+`, `.`, ` `)
4. Displays the ASCII stream using p5’s `text()` function on a canvas

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/video-to-ascii-p5js.git
cd video-to-ascii-p5js
