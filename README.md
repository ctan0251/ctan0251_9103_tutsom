# Quiz 8: Design Research

## Part 1: Imaging Technique Inspiration

**What I found inspiring:**
For my major assignment, I am deeply inspired by generative geometry, specifically the concept of **Truchet Tiles** combined with organic motion. The aspect I want to incorporate is the ability to create complex, infinite maze-like patterns from extremely simple geometric rules. Instead of using static images, I plan to use native p5.js coding (`arc()` and `line()`) to draw the tiles procedurally. I believe this is a beneficial technique because it directly addresses the course's focus on algorithmic logic, and it allows for much deeper interaction—such as using Perlin noise to dynamically control the rotation of the tiles, creating a fluid, living pattern.

**Visual Examples:**
![Truchet Tile Concept](assets/truchet.jpg)
![Organic Flow Inspiration](assets/noise.jpg)

---

## Part 2: Coding Technique Exploration

**How this technique helps:**
To achieve the organic flow in my visual work, I will use **Perlin Noise** as my primary coding technique. Unlike standard `random()`, the `noise()` function generates smooth, continuous sequences of numbers. As shown in the "Noise 1D" example, this allows for the creation of natural, fluid movements. By applying this to the rotation angles of my tiles, I can make the static grid feel like it is breathing or flowing like an ocean current, which perfectly fits the "Perlin noise and randomness" mechanic for our team project.

![Perlin Noise Example](https://p5js.org/assets/img/get-started/noise.png)

**Useful Links:**
* [Truchet Tiles Tutorial & Inspiration](https://happycoding.io/tutorials/p5js/images/truchet-tiles)
* [Example Implementation: p5.js Noise 1D](https://p5js.org/reference/p5/noise/)