# 🎨 Personal Portfolio Website - Chace Liu

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge&logo=vercel)](https://Chace.codecub.org)
[![GitHub](https://img.shields.io/badge/GitHub-Repository-blue?style=for-the-badge&logo=github)](https://github.com/CodeCubCA/profile-website-Chace-codecub)

An interactive and visually stunning personal portfolio website featuring advanced CSS animations, glassmorphism effects, and dynamic particle systems. Built with pure HTML, CSS, and vanilla JavaScript - no frameworks required!

![Portfolio Preview](img/profile.png)

---

## ✨ Features

### 🏠 Home Page
- **Ultra-Complex Animated Logo** with spinning borders, floating particles, and dynamic color gradients
- **Glassmorphism Design** with backdrop blur effects and translucent layers
- **Responsive Navigation** with smooth hover animations and gradient shifts
- **Conic Gradient Borders** that rotate continuously for a futuristic look
- **Floating Container** with subtle animations for depth

### 👦 About Me Section
- **Personal Information Cards** with animated borders and hover effects
  - Age and School information
  - Expanded bio section with hobby icons
- **My Hobbies** showcase with colorful gradient cards:
  - 🏸 Badminton
  - 💻 Coding
  - 🎮 Gaming
  - 🧱 Lego Building
- **Coding Journey** timeline with milestone cards:
  - When I started coding (2020)
  - Favorite programming languages
  - What I love about coding
  - Future goals and aspirations

### 💻 Projects Portfolio
Showcasing my best work with detailed project cards:

#### 1. **Personal Portfolio Website** (This Site!)
- Interactive portfolio with advanced animations
- Glassmorphism UI with responsive design
- Particle Playground with 5 interactive modes
- **Tech Stack:** HTML5, CSS3, JavaScript, Git, GitHub
- [🚀 Live Demo](https://Chace.codecub.org) | [📂 Repository](https://github.com/CodeCubCA/profile-website-Chace-codecub)

#### 2. **AI Chatbox**
- Intelligent AI-powered chatbot for student learning
- Real-time conversation with context awareness
- Deployed with CI/CD on Streamlit Cloud
- Perfect for homework help and subject explanations
- **Tech Stack:** Python, Streamlit, Groq API, Git, Streamlit Cloud
- [🤖 Try Live](https://ai-chatbox-Chace-codecub.streamlit.app) | [📂 Repository](https://github.com/CodeCubCA/ai-chatbox-Chace-codecub)

### 🎮 Interactive Games & Demos
- **Particle Playground** - An interactive particle effects system with multiple modes:
  - ✨ **Sparkles Mode:** Create magical sparkle effects
  - 🎆 **Fireworks Mode:** Launch colorful firework explosions
  - 🌟 **Trails Mode:** Draw glowing particle trails
  - 🌊 **Waves Mode:** Generate expanding wave ripples
  - 🌀 **Gravity Mode:** Create gravity wells that attract particles
- **Custom Cursor** with visual feedback and animations
- **Particle Counter** for real-time performance monitoring
- **Keyboard Shortcuts** for quick mode switching (1-5, C for clear)
- **Mobile Touch Support** for all interactive features

---

## 🎨 Design Highlights

### Advanced CSS Techniques
- **Conic Gradients** for rotating rainbow borders
- **Backdrop Filters** for glassmorphism blur effects
- **CSS Animations** with multiple keyframe sequences
- **3D Transforms** with perspective and rotation
- **Box Shadow Layers** for depth and glow effects
- **Custom Properties** for dynamic color theming

### Animation Features
- Spinning border animations (8-25 second durations)
- Flowing gradient backgrounds (6-15 second cycles)
- Pulsing glow effects with opacity variations
- Floating elements with translateY transforms
- Hover scale and transform effects
- Smooth transitions with cubic-bezier easing

### Color Schemes
Each section has a unique gradient theme:
- **Home:** Blue spectrum (#0080ff, #0066cc, #004499)
- **About:** Multi-color gradients (Pink, Sky Blue, Green)
- **Projects - Portfolio:** Cyan to purple (#00D4FF, #5B73FF, #9B59B6)
- **Projects - AI Chatbox:** Indigo to pink (#6366F1, #9B59B6, #EC4899)
- **Games:** Rainbow particle effects with dynamic hue rotation

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic structure and accessibility
- **CSS3** - Advanced animations and modern layout
- **JavaScript (ES6+)** - Interactive particle system and event handling

### Design & UI
- **Glassmorphism** - Translucent cards with backdrop blur
- **Gradient Borders** - Conic and linear gradient animations
- **Responsive Design** - Mobile-first approach with media queries
- **Custom Animations** - Keyframe animations for all elements

### Development Tools
- **Git** - Version control
- **GitHub** - Repository hosting
- **VS Code** - Code editor
- **Browser DevTools** - Testing and debugging

---

## 📂 Project Structure

```
portfolio-website/
├── index.html          # Home page with animated logo
├── about.html          # About Me, Hobbies, and Coding Journey
├── projects.html       # Portfolio projects showcase
├── games.html          # Interactive Particle Playground
├── img/
│   ├── profile.png     # Portfolio website screenshot
│   └── AI-Chatbot.png  # AI Chatbox screenshot
└── README.md           # This file
```

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS/JavaScript (for customization)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/CodeCubCA/profile-website-Chace-codecub.git
   cd profile-website-Chace-codecub
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Python 3
     python -m http.server 8000

     # Python 2
     python -m SimpleHTTPServer 8000

     # Node.js (with http-server)
     npx http-server
     ```

3. **View in browser**
   - Navigate to `http://localhost:8000`
   - Enjoy the interactive experience!

---

## 🎯 Key Features Breakdown

### 1. Ultra-Complex Logo Animation
```css
- 5 spinning gradient rings at different speeds
- Central "C" symbol with text gradient animation
- 6 orbiting particles with hue rotation
- 8 floating micro-particles with independent movement
- 6 expanding energy waves
- 5 pulsing rings for depth
- 4 rotating hexagonal geometric patterns
- Radial glow background with color shifts
```

### 2. Particle Playground System
```javascript
- Real-time particle generation on mouse interaction
- 5 different effect modes with unique behaviors
- Gravity well physics simulation
- Automatic particle cleanup system
- Touch support for mobile devices
- Performance-optimized rendering
- Customizable colors and particle properties
```

### 3. Responsive Design
```css
- Desktop (min-width: 769px): Full experience
- Tablet (768px): Adjusted layouts and spacing
- Mobile (480px): Optimized single-column layout
- Touch-friendly buttons and interactive elements
- Accessible keyboard navigation
```

---

## 🌟 Animation Performance

### Optimization Techniques
- **CSS Animations** over JavaScript for better performance
- **Transform** and **opacity** changes (GPU-accelerated)
- **RequestAnimationFrame** for smooth particle motion
- **Automatic cleanup** to prevent memory leaks
- **Reduced motion support** for accessibility
- **Efficient DOM manipulation** with minimal reflows

---

## 📱 Browser Compatibility

| Browser | Version | Support |
|---------|---------|---------|
| Chrome  | 90+     | ✅ Full |
| Firefox | 88+     | ✅ Full |
| Safari  | 14+     | ✅ Full |
| Edge    | 90+     | ✅ Full |
| Opera   | 76+     | ✅ Full |

---

## 🎨 Customization Guide

### Changing Colors
Edit the color variables in the `<style>` section of each HTML file:
```css
/* Example: Change primary blue */
background: linear-gradient(135deg, #YOUR_COLOR_1, #YOUR_COLOR_2);
```

### Adding New Projects
1. Open `projects.html`
2. Copy an existing project card
3. Update the content, images, and links
4. Add custom tech badges with gradient colors

### Modifying Animations
Adjust animation durations and easing:
```css
animation: animationName 8s ease-in-out infinite;
```

---

## 📸 Screenshots

### Home Page
![Home Page](img/profile.png)

### Projects Portfolio
Features two complete projects with live demos and GitHub repositories.

### Particle Playground
Interactive particle system with 5 unique effect modes.

---

## 🤝 Contributing

This is a personal portfolio project, but feedback and suggestions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available for educational purposes. Feel free to use it as inspiration for your own portfolio!

---

## 👨‍💻 About Me

Hi! I'm **Chace Liu**, an 11-year-old coding enthusiast with a passion for creating interactive web experiences. I started my coding journey in 2020 and love working with HTML, CSS, JavaScript, and Python.

### My Coding Journey
- 🎯 **Started:** 2020
- ❤️ **Favorite Languages:** HTML and Python
- 💡 **What I Love:** The complexity of coding and solving challenging problems
- 🚀 **Goal:** Build my own popular website that inspires others

### Hobbies
- 🏸 Badminton - Fast-paced action and precision
- 💻 Coding - Building amazing projects
- 🎮 Gaming - Exploring virtual worlds
- 🧱 Lego Building - Creating structures and bringing imagination to life

---

## 📬 Contact & Links

- **Website:** [https://Chace.codecub.org](https://Chace.codecub.org)
- **GitHub:** [CodeCubCA](https://github.com/CodeCubCA)
- **AI Chatbox Project:** [Try Live](https://ai-chatbox-Chace-codecub.streamlit.app)

---

## 🙏 Acknowledgments

- Inspired by modern glassmorphism design trends
- Built with passion and dedication to web development
- Special thanks to the CodeCub coding community

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

**Made with ❤️ by Chace Liu**

[🏠 Visit Website](https://Chace.codecub.org) • [📧 Contact](https://github.com/CodeCubCA)

</div>
