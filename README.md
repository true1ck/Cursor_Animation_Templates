# 🎨 Cursor Animation Gallery

A unified web interface showcasing beautiful cursor animations in one seamless experience. Features a modern hamburger menu to switch between different animation effects dynamically.

## 🌟 NEW: Unified Gallery Interface

**Primary File:** `index.html` - **Main gallery interface with hamburger menu navigation**

### Features:
- 🍔 **Hamburger Menu**: Modern slide-out navigation on the left
- 🔄 **Dynamic Loading**: Switch between animations seamlessly
- 📱 **Responsive Design**: Works perfectly on desktop and mobile
- ⚡ **Performance Optimized**: Animations load on-demand
- ℹ️ **Animation Info**: Each effect includes description overlay
- 🎯 **Clean Interface**: Minimal UI focused on the animation experience

### How to Use the Gallery:
1. Open `index.html` in your web browser
2. Click the hamburger menu (☰) in the top-left corner
3. Select any animation to view it instantly
4. Switch between animations using the menu
5. Each animation includes an info panel with details

---

## 📂 Individual Animation Files

*Note: Each animation is also available as a standalone file, but we recommend using the unified gallery above.*

## 🚀 Quick Start

Simply download any HTML file and open it in your browser to see the animation in action. Each template is standalone and doesn't require external dependencies.

## 📂 Available Animations

### 1. 🌊 Fluid Particles Animation
**File:** `fluid_particles_animation.html`

**Description:**
- **Visual Effect:** Colorful, dynamic particles that follow cursor movement with fluid dynamics
- **Colors:** Vibrant blue, coral, turquoise, mint, peach, purple, cyan, and pink particles
- **Behavior:** 
  - Particles spawn when cursor moves
  - Smooth fluid-like movement with physics
  - Gradual fade-out effect
  - Responsive design for all screen sizes
- **Best For:** Landing pages, portfolios, creative websites
- **Performance:** Optimized with particle count limits (max 80 particles)

**Features:**
- ✨ 8 vibrant color palette
- 🎯 Mouse-responsive particle generation
- 💫 Smooth physics simulation
- 📱 Mobile-responsive design
- 🎨 Glass-morphism UI elements

---

### 2. ✨ Sparkle Trail Animation
**File:** `sparkle_trail_animation.html`

**Description:**
- **Visual Effect:** White sparkle particles with connecting lines creating a constellation effect
- **Colors:** Primarily white/transparent with dynamic HSL color shifting
- **Behavior:**
  - Trail of sparkles follows cursor movement
  - Particles connect with lines when nearby
  - Smooth fade-out with size reduction
  - Background text overlay support
- **Best For:** Personal portfolios, name displays, elegant presentations
- **Performance:** Lightweight with efficient particle management

**Features:**
- ⭐ White sparkle trail effect
- 🔗 Dynamic particle connections
- 🎭 Background text overlay
- 🌈 Subtle color shifting
- 📱 Responsive design

---

### 3. ❄️ Ice Crystal Animation
**File:** `ice_crystal_complete.html`

**Description:**
- **Visual Effect:** Magical ice crystals that follow your cursor with realistic winter physics
- **Colors:** Cool blues, whites, and crystalline effects with shimmer
- **Behavior:**
  - Realistic snowflake shapes with multiple arms and branches
  - Ice crystals attracted to cursor movement
  - Shimmering and rotating effects
  - Click to create ice explosions
  - Adjustable crystal count, size, and attraction strength
- **Best For:** Winter themes, fantasy websites, elegant presentations
- **Performance:** Advanced physics with optimized crystal rendering

**Features:**
- ❄️ Realistic ice crystal shapes
- ✨ Shimmer and glow effects
- 🎮 Interactive controls panel
- 💥 Click explosion effects
- 🌌 Beautiful winter background
- 🔄 Smooth physics simulation

---

### 4. 🔥 Fire Trail Animation
**File:** `fire_trail_animation.html`

**Description:**
- **Visual Effect:** Subtle, realistic fire particles with gentle flame physics and consistent warm colors
- **Colors:** Soft orange-red to golden yellow palette (easy on the eyes)
- **Behavior:**
  - Gentle fire particles that rise and flicker naturally
  - Velocity-responsive intensity (faster movement = more particles)
  - Realistic heat-based physics with subtle turbulence
  - Occasional floating embers for atmosphere
  - Custom fire-themed cursor
- **Best For:** Creative portfolios, cozy websites, autumn themes, gaming interfaces
- **Performance:** Optimized with 200 particle limit and efficient rendering

**Features:**
- 🔥 Realistic but subtle fire physics
- 🎨 Consistent warm color palette
- 👁️ Easy on the eyes with reduced opacity
- 🌪️ Gentle turbulence and wind effects
- ✨ Floating ember particles
- 🖱️ Custom fire cursor
- 📱 Mobile-responsive design

## 🛠️ How to Use

### Method 1: Direct Download
1. Click on any animation file in the repository
2. Click "Raw" button
3. Right-click and "Save as..." to download
4. Open the HTML file in any modern browser

### Method 2: Clone Repository
```bash
git clone https://github.com/true1ck/Cursor_Animation_Templates.git
cd Cursor_Animation_Templates
# Open any HTML file in your browser
```

### Method 3: Integration into Your Project
Copy the CSS and JavaScript code from any template and integrate it into your existing project.

## 🎯 Browser Support

All animations are built with modern web standards and support:
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## ⚡ Performance Tips

- All animations use `requestAnimationFrame` for smooth 60fps performance
- Particle counts are automatically limited to prevent performance issues
- Animations pause when cursor is inactive
- Mobile-optimized with reduced particle counts on smaller screens

## 🎨 Customization

Each animation can be easily customized:

### Colors
Look for color arrays in the JavaScript section:
```javascript
const colors = [
    { r: 64, g: 156, b: 255 },    // Blue
    { r: 255, g: 107, b: 107 },   // Coral
    // Add your own colors here
];
```

### Particle Count
Adjust the maximum particle limit:
```javascript
if (this.particles.length > 80) { // Change this number
    this.particles = this.particles.slice(-80);
}
```

### Animation Speed
Modify decay rates and movement speeds:
```javascript
this.decay = Math.random() * 0.012 + 0.006; // Faster decay = shorter life
```

## 🔮 Coming Soon

This repository will be expanded with more cursor animations:

- 🔥 Fire Trail Animation
- ❄️ Ice Crystal Effects  
- 🌟 Shooting Stars
- 🌈 Rainbow Ripples
- 🎆 Firework Explosions
- 🌙 Lunar Orbit Effects
- 🌸 Falling Petals
- ⚡ Lightning Bolts
- 🌊 Wave Distortions
- 🕸️ Spider Web Connections

## 📸 Screenshots

*Note: Screenshots will be added soon. For now, please run the HTML files locally to see the animations in action.*

## 🤝 Contributing

Have a cool cursor animation idea? Feel free to contribute!

1. Fork this repository
2. Create a new HTML file with your animation
3. Follow the naming convention: `[effect_name]_animation.html`
4. Update this README with your animation description
5. Submit a pull request

## 📄 License

These templates are free to use in personal and commercial projects. Attribution is appreciated but not required.

## 🐛 Issues & Support

If you encounter any bugs or have feature requests:
1. Open an issue in this repository
2. Provide browser information and steps to reproduce
3. Include screenshots if possible

## 📧 Contact

Created by [true1ck](https://github.com/true1ck)

---

⭐ **Star this repository if you find these animations useful!**

*Happy coding! 🚀*
