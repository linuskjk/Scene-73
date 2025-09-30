# The Great Frozen Wall

An interactive web experience featuring a frozen wall that can be cracked open to reveal a sophisticated cooling system underneath. This project combines engaging visual effects, ambient audio, and interactive elements to create an immersive experience.

## 🎮 How to Play

1. **Crack the Ice**: Click on the frozen wall multiple times (3-5 clicks required) to create crack effects
2. **Pick up the Lighter**: After enough clicks, a lighter will appear - click it to pick it up
3. **Melt the Wall**: Hover the lighter over the wall for about 2 seconds to completely melt through
4. **Explore the Cooling System**: Interact with various components once revealed

## 🔧 Features

### Interactive Elements
- **Dynamic Crack Effects**: Each click creates expanding crack animations with realistic visual effects
- **Lighter Mechanics**: Pick up and use a flame-enabled lighter to melt through the ice
- **Heat Spot Tracking**: Visual heat indicator follows the lighter when hovering over the wall
- **Sound Effects**: Ice breaking and lighter ignition sounds (can be toggled)

### Cooling System Components
Once the wall is melted, you'll discover a complete cooling system with:

- **Radiator with Fan**: Click to boost fan speed and enhance cooling performance
- **Coolant Pump**: Animated impeller with LED status indicator
- **Pressure & Temperature Gauges**: Real-time animated readings with oscillating values
- **Coolant Reservoir**: Animated fluid levels with dynamic bubbles and ripple effects
- **Flow Valve**: Toggle to control pressure amplitude (click to open/close)
- **Pipe Network**: Animated coolant flow with directional indicators
- **Control Display**: Monitor temperature (-20°C to -30°C), pressure (1.1-1.4 bar), and system settings

### Special Effects
- **Steam Animation**: Realistic steam puffs when the system is revealed
- **Frost Burst Mode**: Temporary deep-freeze visual effect
- **Dye System**: Toggle between cyan and cyberpunk color schemes
- **Ambient Audio**: Subtle airflow sounds with Web Audio API
- **Responsive Animations**: Smooth transitions and hover effects

## 🎨 Visual Design

- **Ice-themed Color Palette**: Blues, cyans, and whites create an authentic frozen atmosphere
- **CSS Grid Layout**: Organized component placement in the cooling system
- **Particle Effects**: Crack patterns, steam puffs, and bubble animations
- **Glow Effects**: Neon-style lighting with box-shadows and text-shadows
- **Accessibility**: Proper ARIA labels, keyboard navigation support, and reduced motion options

## 🔊 Audio Features

- **Ice Breaking Sound**: Realistic cracking audio when clicking the wall
- **Lighter Sound**: Authentic lighter ignition effect
- **Ambient Noise**: Subtle cooling system background audio
- **Audio Controls**: Toggle sound on/off with visual feedback

## 🌐 Navigation

The project includes links to connected scenes:
- **Scene 74**: Spanky's (dice rolling game)
- **Scene 45**: Node 45
- **Scene 79**: Ancient Insult Trading Post

## 📁 File Structure

```
/73/
├── index.html          # Main HTML structure
├── script.js           # Interactive functionality and animations
├── style.css           # Visual styling and animations
├── lighter.png         # Lighter sprite image
├── ice-break-14765.mp3 # Ice cracking sound effect
├── lighter.mp3         # Lighter ignition sound effect
└── README.md           # This documentation
```

## 🚀 Technical Implementation

### JavaScript Features
- **Event Handling**: Click, hover, and keyboard interactions
- **Animation Systems**: RequestAnimationFrame loops for smooth performance
- **Web Audio API**: Real-time audio processing with gain nodes and filters
- **Dynamic DOM Manipulation**: Runtime creation of visual effects
- **State Management**: Tracking user progress and system states

### CSS Techniques
- **CSS Grid & Flexbox**: Responsive layout systems
- **CSS Animations**: Keyframe animations for continuous effects
- **CSS Gradients**: Radial and linear gradients for realistic textures
- **CSS Filters**: Blur, drop-shadow, and brightness effects
- **CSS Variables**: Consistent theming and easy customization

### Accessibility
- **ARIA Labels**: Screen reader support for interactive elements
- **Keyboard Navigation**: Tab and Enter key support
- **Focus Management**: Visible focus indicators
- **Reduced Motion**: Respects user motion preferences
- **Live Regions**: Dynamic content announcements

## 🎯 Browser Compatibility

- Modern browsers with ES6+ support
- Web Audio API support required for sound features
- CSS Grid and Flexbox support recommended
- Touch device compatible

## 🔧 Setup & Usage

1. Ensure all files are in the same directory
2. Serve from a web server (required for audio files to load properly)
3. Open `index.html` in a modern web browser
4. Click on the wall to begin the interactive experience

## 💡 Tips for Developers

- The crack effect is randomly generated (3-5 clicks required)
- Hover timer for melting is set to 1.8 seconds
- Temperature oscillates between -23°C to -30°C
- Pressure ranges from 1.1 to 1.4 bar
- Steam effects spawn every 900ms when active
- All animations use CSS transforms for optimal performance

---

*Part of an interactive web experience series. Visit the connected scenes for more adventures!*
