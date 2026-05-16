# Anime.js Learning Project

A collection of standalone HTML examples for learning anime.js animation library.

## 📚 Examples

### 1. Basic Animation (`examples/basic-animation.html`)
Demonstrates the core `anime()` function with:
- CSS transforms: `translateX`, `opacity`, `rotate`
- Single element animation
- Smooth easing (`easeInOutQuad`)

**What you'll learn**: How to create a simple animation with anime.js using CSS properties and transforms.

### 2. Timeline (`examples/timeline.html`)
Demonstrates `anime.timeline()` for orchestrating multiple animations:
- Sequential animation of 3 elements
- Time offsets for overlapping effects (`-=200`)
- Default parameters for all animations

**What you'll learn**: How to create animation sequences with precise timing control.

### 3. Stagger (`examples/stagger.html`)
Demonstrates `anime.stagger()` for animating multiple elements:
- 5 elements with staggered timing (100ms delay each)
- Scale and fade-in effects
- Wave-like animation pattern

**What you'll learn**: How to create cascading animations across multiple elements.

### 4. Draggable (`examples/draggable.html`)
Demonstrates `anime.createDraggable()` for interactive elements:
- Single draggable element
- Movement area restriction (`container: [0, 0, 500, 500]`)
- Smooth release animation

**What you'll learn**: How to make elements interactive with drag functionality.

## 🚀 How to Run

Simply open any HTML file in your browser:

```bash
# Using file manager
# Double-click any .html file in the examples/ directory

# Using command line (Linux)
xdg-open examples/basic-animation.html

# Using command line (macOS)
open examples/basic-animation.html

# Using command line (Windows)
start examples/basic-animation.html
```

No build tools or server required - all examples use CDN for anime.js.

## 🔗 Resources

- **Official Documentation**: [https://animejs.com/documentation/](https://animejs.com/documentation/)
- **Easing Editor**: [https://animejs.com/easing-editor](https://animejs.com/easing-editor)
- **CodePen Examples**: [https://codepen.io/collection/Poerqa](https://codepen.io/collection/Poerqa)
- **GitHub Repository**: [https://github.com/juliangarnier/anime](https://github.com/juliangarnier/anime)

## 🎯 Learning Objectives

This project helps you learn:
1. Basic anime.js API usage (`anime()`, `timeline()`, `stagger()`, `createDraggable()`)
2. CSS transforms and properties animation
3. Animation timing and sequencing
4. Interactive animations with draggable elements

## 📦 Project Structure

```
Anime/
├── README.md
├── examples/
│   ├── basic-animation.html
│   ├── timeline.html
│   ├── stagger.html
│   └── draggable.html
```

## 💡 Tips

- Each example is standalone - no dependencies between files
- All examples use anime.js v4.0.0 via CDN
- Inline comments explain key API concepts
- Try modifying the values to experiment!

---

**Happy animating!** 🎨