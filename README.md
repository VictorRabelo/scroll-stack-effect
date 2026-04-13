# Scroll Stack Effect 🗂️

A modern, high-performance UI component featuring a vertical stacking card effect, built exclusively with **Pure HTML and CSS**. This project demonstrates how to achieve complex scroll animations without the overhead of JavaScript, leveraging native browser capabilities.

## 🚀 Overview

The **Scroll Stack Effect** creates an immersive experience where cards stack on top of each other as the user scrolls. By using `position: sticky` and CSS variables, the project maintains high frame rates (60fps) and a smooth feel, ideal for landing pages and portfolios.

## ✨ Key Features

- **Zero JavaScript:** Powered entirely by CSS for maximum performance and security.
- **Fluid Responsiveness:** Utilizes `clamp()` and CSS Grid to ensure a perfect look from mobile to ultra-wide monitors.
- **Glassmorphism & Depth:** Advanced styling with `backdrop-filter`, gradients, and dynamic scaling.
- **Clean Architecture:** Semantic HTML5 and modular CSS using custom properties (variables) for easy customization.
- **Accessible:** Structured with screen readers and keyboard navigation in mind.

## 🛠️ Built With

* **HTML5** - Semantic structure.
* **CSS3** - Custom Properties, Sticky Positioning, and Flexbox/Grid.
* **Google Fonts** - "Inter" typeface for modern typography.

## 📖 How it Works

The effect relies on two core CSS concepts:
1.  **`position: sticky`**: Keeps the cards "locked" at the top of the viewport during the scroll.
2.  **`calc()` + CSS Variables**: Each card uses its `--index` variable to calculate its specific `top` offset and `scale` reduction, creating the visual depth of a real stack.

## 📥 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VictorRabelo/scroll-stack-effect.git

2. Open index.html in your favorite browser.

👨‍💻 Author
Victor Gabriel
Full-stack Web Developer

LinkedIn [https://www.linkedin.com/in/victor-rabelo-2a11ba204/](https://www.linkedin.com/in/victor-rabelo-2a11ba204/)

Portfolio [https://victor-rabelo-showcase.vercel.app/](https://victor-rabelo-showcase.vercel.app/)

Developed with focus on Clean Code and Frontend Performance.