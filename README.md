# Immersive Fractal Visualizer

An interactive, full-screen fractal visualization experience with PS5-inspired UI design. This project creates mathematically accurate representations of famous fractals using pure CSS animations and gradients, delivering an immersive visual experience without requiring complex mathematical computations.

## 🎯 Project Overview

This visualizer demonstrates how mathematical beauty can be recreated using web technologies, transforming complex fractal mathematics into accessible visual art. Unlike computational approaches, this project uses CSS animations to approximate fractal patterns, making it lightweight and performant across all devices.

## ✨ Featured Fractals

### 1. **Julia Set**
- **Mathematical basis**: Complex iteration z² + c with fixed parameter c
- **Visualization**: Multi-layered radial gradients simulating the fractal boundary
- **Animation**: Zoom and translation effects showing different regions of the set

### 2. **Mandelbrot Set** 
- **Mathematical basis**: The famous z² + c iteration where c varies across the complex plane
- **Visualization**: Cardioid main body with secondary bulbs and fine boundary details
- **Animation**: Progressive zoom into the fractal boundary with color cycling

### 3. **Dragon Curve**
- **Mathematical basis**: Recursive L-system with 90° rotations at each iteration
- **Visualization**: Linear gradients approximating the recursive folding pattern
- **Animation**: Multiple iteration levels showing the curve's self-similar structure

### 4. **Barnsley Fern**
- **Mathematical basis**: Iterated Function System (IFS) with four affine transformations
- **Visualization**: Organic shapes using elliptical gradients mimicking fern fronds
- **Animation**: Growth and swaying motion simulating natural plant movement

### 5. **Lorenz Attractor**
- **Mathematical basis**: Chaotic dynamical system (σ=10, ρ=28, β=8/3)
- **Visualization**: Dual-lobe structure with connecting trajectories
- **Animation**: Orbital motion representing the strange attractor's behavior

### 6. **Sierpinski Carpet**
- **Mathematical basis**: Recursive square subdivision removing center squares
- **Visualization**: Grid patterns at multiple scales showing self-similarity
- **Animation**: Infinite zoom effect revealing fractal detail at all scales

### 7. **Koch Curve**
- **Mathematical basis**: Recursive line replacement with triangular protrusions
- **Visualization**: Angular gradients approximating the curve's geometric structure
- **Animation**: Multi-scale iteration showing fractal boundary development

## 🎮 User Interface

### PS5-Inspired Design
- **Transparent navigation bar** with subtle glassmorphism effects
- **Central play/pause control** with radial blur backgrounds
- **Minimal, floating UI elements** that don't distract from the fractals
- **Smooth transitions** using cubic-bezier easing functions
- **Auto-hiding cursor** for immersive full-screen experience

### Navigation Controls
- **Mouse navigation**: Click buttons to switch between fractals
- **Keyboard shortcuts**: 
  - `0` - Home screen
  - `1-7` - Switch to specific fractals
  - `Space` - Play/pause animations
- **Central control**: Play/pause button for animation control

## 🚀 Getting Started

### Prerequisites
- Modern web browser with CSS animation support
- No additional dependencies or installations required

### Installation & Usage
1. Download `index.html`
2. Open in any modern web browser
3. Use navigation controls to explore different fractals
4. Press spacebar or click center button to pause/resume animations

### Live Demo
🌐 **[View Live Demo](https://bxant.github.io/immersive-fractal-gallery/)**

### Performance
- **Pure CSS animations** - no JavaScript computation overhead
- **Hardware accelerated** - utilizes GPU for smooth 60fps animations
- **Responsive design** - adapts to any screen size
- **Lightweight** - single HTML file under 15KB

## 🎨 Technical Implementation

### CSS Animation Architecture
```css
/* Multi-layer approach for mathematical accuracy */
.fractal-layer:nth-child(1) { /* Base structure */ }
.fractal-layer:nth-child(2) { /* Fine details */ }
.fractal-layer:nth-child(3) { /* Boundary effects */ }
