# shli0386_9103_Tut01
My first repository for IDEA9103

# 🎨 IDEA9103 Quiz 8 – Design Research for Major Project  
**Student Name**: Shixuan Li  
**Unikey**: shli0386 
**Commit Label**: `Quiz 8`

---

## Part 1: Imaging Technique Inspiration

### 🖼️ Artwork: *Wheels of Fortune* by Pacita Abad (2000)

![Wheels of Fortune – Pacita Abad](https://d32dm0rphc51dk.cloudfront.net/RpcGV_JpGZ-w6wxDK5i5sQ/normalized.jpg)

![Pacita Abad - One Fine Day](https://assets.phillips.com/auctions/NY010125/214626_001.jpg)

In *Wheels of Fortune*, I’m inspired by the use of **vibrant concentric circles**, each with its own patterns and direction. I would like to simulate this through **independent circular objects that rotate individually** to reflect the chaotic, playful, and dynamic feeling of the artwork. This structure allows for modular animation with strong visual rhythm, aligning with the project’s emphasis on object-oriented coding and visual abstraction.

---

## Part 2: Coding Technique Exploration

### 🧠 Technique: Independent object rotation with mouse hover interaction in p5.js

![Rotating Circle Demo](https://cdn.pixabay.com/photo/2021/05/13/12/10/background-6250721_1280.jpg)

**Example Link**:  
[Rotating Shapes with Classes and Hover Interaction – OpenProcessing](https://editor.p5js.org/lliu29/sketches/NeGyR6QJ)

This technique uses `rotate()` combined with `push()`/`pop()` and object-oriented structures to rotate multiple objects on the canvas. Each “wheel” or circle is programmed as a separate class instance. Using `dist()` to detect proximity to the mouse, we can trigger different behaviors such as **pausing** or **speeding up** when hovering over a circle. This creates playful interactivity while preserving modular and scalable code for the full animation project.