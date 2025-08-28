# Fireworks Animation Website

A beautiful, interactive fireworks animation website created with HTML, CSS, and JavaScript.

![Fireworks Animation Website](https://media.istockphoto.com/id/1336937059/video/cartoon-fireworks-explosions-animation-with-alpha-channel.jpg?s=640x640&k=20&c=RBh0JQPI9Z-mPHBNgbfCUz8cN-fkJ9-1vWxqWmPE8WY=)

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Features

- ✨ Realistic fireworks animations
- 🎨 Customizable colors and effects
- 🖱️ Click to create fireworks at specific locations
- 🔄 Automatic fireworks generation
- 📱 Responsive design for all devices
- 🌓 Dark/light mode toggle
- 🔊 Optional sound effects

## Demo

Check out the live demo: [Fireworks Animation Website](https://your-github-username.github.io/fireworks-website/)

## Technologies Used

- HTML5
- CSS3 (with animations and transitions)
- JavaScript (vanilla)
- Canvas API for drawing

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fireworks-website.git
   ```

2. Navigate to the project directory:
   ```bash
   cd fireworks-website
   ```

3. Open `index.html` in your browser or use a live server extension if you're using VS Code.

## Usage

- Simply open the website to enjoy automatic fireworks
- Click anywhere on the screen to launch fireworks from that position
- Use the settings panel to customize colors, size, and effects
- Toggle sound effects on/off
- Switch between dark/light mode

## Project Structure

```
fireworks-website/
│
├── index.html          # Main HTML file
├── css/
│   ├── style.css       # Main styles
│   └── responsive.css  # Responsive design styles
│
├── js/
│   ├── fireworks.js    # Fireworks animation logic
│   ├── particles.js    # Particle system for explosions
│   └── app.js          # Main application file
│
├── assets/
│   ├── sounds/         # Sound effects
│   └── images/         # Images and icons
│
└── README.md           # Project documentation
```

## How It Works

The fireworks animation uses HTML5 Canvas to render particles that simulate fireworks. The animation follows these steps:

1. **Launch Phase**: A "rocket" particle moves upward with a trail
2. **Explosion**: At the peak, the rocket explodes into multiple particles
3. **Falling**: Particles expand outward while falling due to gravity
4. **Fading**: Particles gradually fade out

The animation uses requestAnimationFrame for smooth performance and manages particles through object-oriented JavaScript.

## Customization

You can customize the fireworks by modifying variables in the `fireworks.js` file:

- `particleCount`: Number of particles per explosion
- `particleSize`: Size of each particle
- `explosionRadius`: How far particles travel from explosion
- `colors`: Array of colors for the fireworks
- `gravity`: How quickly particles fall
- `fadeRate`: How quickly particles fade out

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.