# 🚁 Agricultural Drone Simulation

*Experience precision farming from the sky with our interactive 3D drone simulation*

[![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow?style=for-the-badge&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![WebGL](https://img.shields.io/badge/WebGL-2.0-red?style=for-the-badge&logo=webgl)](https://www.khronos.org/webgl/)

## 🌟 Features

### 🎮 **Immersive Flight Control**
- **WASD Navigation**: Intuitive movement controls for natural drone piloting
- **Q/E Altitude Control**: Precision height adjustment from 3 to 30 units
- **Real-time Position Tracking**: Live coordinates display for exact positioning

### 🌾 **Smart Sector Management**
- **4 Distinct Sectors**: Color-coded zones for organized field management
- **Boundary Enforcement**: Automatic out-of-bounds detection with visual alerts
- **Sector-Specific Operations**: Restricted spraying to selected areas only

### 💧 **Advanced Water System**
- **Realistic Particle Physics**: Dynamic water droplet simulation with gravity
- **Visual Ground Impact**: See water spots accumulate on the terrain
- **Moisture Tracking**: Real-time hydration percentage for each sector
- **Dynamic Texture Updates**: Ground color changes based on water saturation

### 🎨 **Stunning Visuals**
- **Photorealistic 3D Environment**: Detailed drone model with spinning rotors
- **Dynamic Lighting**: Ambient and directional lighting for depth
- **Smooth Camera System**: Follows drone movement for optimal viewing
- **Particle Effects**: Beautiful water spray visualization

## 🚀 Quick Start

### Prerequisites
- Modern web browser with WebGL support
- No additional installations required!

### Launch Instructions
1. **Clone or download** the repository
2. **Open** `index.html` in your web browser
3. **Select a sector** using the buttons in the top-right corner
4. **Take flight** with WASD keys
5. **Start spraying** with the spacebar

## 🎯 How to Use

### 🕹️ Controls Reference

| Key | Action |
|-----|--------|
| `W` | Move Forward |
| `A` | Move Left |
| `S` | Move Backward |
| `D` | Move Right |
| `Q` | Raise Drone |
| `E` | Lower Drone |
| `Space` | Toggle Water Spray |

### 📍 Sector Navigation
1. **Choose Your Zone**: Click any sector button (1-4) to begin
2. **Stay in Bounds**: Red "OUT OF BOUNDS!" alert prevents cross-sector contamination
3. **Monitor Progress**: Watch hydration levels increase as you water each area
4. **Visual Feedback**: Ground texture darkens with increased moisture

### 💡 Pro Tips
- **Optimal Height**: Fly at medium altitude for best spray coverage
- **Systematic Patterns**: Use grid patterns for even water distribution
- **Monitor Moisture**: Watch the hydration percentage to avoid over-watering
- **Respect Boundaries**: Spraying automatically stops when leaving assigned sector

## 🛠️ Technical Specifications

### Built With
- **Three.js r128** - 3D graphics rendering
- **WebGL 2.0** - Hardware-accelerated graphics
- **HTML5 Canvas** - Dynamic texture generation
- **Vanilla JavaScript** - No framework dependencies

### Performance Features
- **Optimized Particle System** - Efficient water droplet management
- **Dynamic LOD** - Automatic detail adjustment based on view distance
- **Texture Streaming** - Real-time ground texture updates
- **Memory Management** - Automatic cleanup of expired particles

## 🌐 Browser Compatibility

| Browser | Support |
|---------|---------|
| Chrome 80+ | ✅ Full Support |
| Firefox 75+ | ✅ Full Support |
| Safari 13+ | ✅ Full Support |
| Edge 80+ | ✅ Full Support |

## 📊 System Requirements

- **GPU**: WebGL 2.0 compatible graphics card
- **RAM**: 4GB minimum, 8GB recommended
- **CPU**: Modern multi-core processor
- **Resolution**: 1280x720 minimum, 1920x1080 optimal

## 🎨 Customization Options

The simulation supports various customization parameters:

```javascript
// Movement settings
const moveSpeed = 0.5;        // Drone movement speed
const maxHeight = 30;         // Maximum flight altitude
const minHeight = 3;          // Minimum flight altitude

// Visual settings
const sectorSize = 50;        // Size of each sector
const groundSize = 100;       // Total field size
const textureSize = 512;      // Ground texture resolution
```

## 🔧 Advanced Features

### Dynamic Environment
- **Weather Effects**: Ready for rain and wind simulation
- **Day/Night Cycle**: Adjustable lighting conditions
- **Seasonal Changes**: Modifiable crop appearance

### Data Analytics
- **Coverage Mapping**: Track sprayed vs. unsprayed areas
- **Water Usage**: Monitor consumption per sector
- **Efficiency Metrics**: Calculate optimal flight patterns

## 🤝 Contributing

We welcome contributions! Areas for enhancement:
- Additional drone models and customization
- Weather simulation and environmental effects
- Mission planning and automation features
- Mobile device optimization
- Multiplayer collaborative farming modes

## 📜 License

This project is open source and available under the MIT License.

## 🏆 Achievements

Unlock virtual farming milestones:
- 🎯 **Precision Pilot**: Complete a sector with 100% coverage
- 💧 **Water Warrior**: Achieve optimal hydration across all sectors
- 🚁 **Sky Farmer**: Master all flight controls without boundary violations
- 🌱 **Green Thumb**: Maintain perfect moisture balance

---

**Ready to revolutionize agriculture? Take to the skies and experience the future of farming!** 🚁🌾

*Built with ❤️ for sustainable agriculture and cutting-edge technology*
