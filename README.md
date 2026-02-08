# Control Loop Tuner

An interactive web-based tool for designing and tuning PID controllers with real-time visualization of system behavior.

## Features

- **PID Tuning Interface**: Adjust proportional, integral, and derivative gains in real-time
- **Multiple Response Types**:
  - Step response simulation and visualization
  - Impulse response analysis
  - Bode plots for frequency domain analysis
- **System Simulation**: Mass-spring-damper dynamics for realistic control scenarios
- **3D Visualization**: Three-dimensional system state visualization using Three.js
- **Control Modes**:
  - SISO (Single-Input Single-Output) for basic control
  - MIMO (Multiple-Input Multiple-Output) for complex systems
- **Real-time Updates**: Instantaneous plot updates as you adjust tuning parameters
- **Interactive Plots**: Zoom, pan, and explore response characteristics

## Tech Stack

- **HTML5** - Semantic markup
- **JavaScript** - Core application logic and numerical computations
- **Three.js** - 3D visualization engine
- **Canvas** - 2D plot rendering
- **PWA** - Progressive Web App capabilities

## Getting Started

### Online Demo
Visit the live application: [https://arnoutzw.github.io/control-tuner-app/](https://arnoutzw.github.io/control-tuner-app/)

### Local Installation
Simply open `index.html` in a modern web browser. No build tools or dependencies required.

### Usage
1. Open the application in your browser
2. Adjust PID gains (Kp, Ki, Kd) using the control sliders
3. View real-time response plots update as you tune parameters
4. Switch between SISO and MIMO modes for different control scenarios
5. Analyze step, impulse, and frequency responses to validate your tuning

## Browser Support

Requires a modern browser with Canvas and WebGL support (Chrome, Firefox, Edge, Safari)

## License

MIT License - See LICENSE file for details
