# 🎨 SelfModify - Procedural Geometric Visualization

**Audio-reactive particle system with morphing geometric forms**

## ✨ Features

### 🎯 Procedural Geometric Forms
- **8 distinct shapes**: Spiral, Grid, Circles, Wave, Star, DNA Helix, Polygon, Galaxy
- Each form generated mathematically with unique parameters
- Random position, rotation, and scale for infinite variety
- Form-specific color palettes for instant visual identity

### 🌈 Color System
- Dedicated color palette per geometric form
- Smooth color transitions with variation
- Pure form colors (no genome interference during morphing)
- Audio-reactive color modulation

### 🎵 Audio Reactivity
- Real-time FFT analysis
- BPM detection with phase-locked loop
- Beat-synchronized visual events
- Dynamic latency compensation
- Audio-reactive forces and colors

### ⚡ Performance
- 800 particles for optimal balance
- Smooth morphing (no lag!)
- Progressive force curves (5-20N, no nuclear 80N freeze)
- Efficient Canvas 2D rendering
- Connection lines disabled during morphing for clarity

### 🔄 Constant Evolution
- Forms change every 5 seconds
- WOW moments with clear geometric shapes
- Never repetitive - infinite combinations
- Position randomization (not always centered!)

## 🎮 Controls

- **F** - Force new form generation
- **M** - Mutate color genome mode
- **↑/↓** - Adjust audio latency compensation
- **R** - Reset latency to default
- **Click** - Create particle explosion

## 🚀 Usage

1. Start local server: `python3 -m http.server 8000`
2. Open: `http://localhost:8000/self-modifying-loop.html`
3. Click "START AUDIO" and select audio source:
   - Tab audio (YouTube, Spotify, etc.)
   - Microphone input

## 📁 File Versions

- `self-modifying-loop.html` - **Latest**: Procedural geometric forms system
- `self-modifying-loop-IMAGE-COLOR-v6.html` - Color image system
- `self-modifying-loop-PARTICLE-ASSIGN-v5.html` - 1:1 particle assignment
- `self-modifying-loop-FREEZE-FORCE-v4.html` - Nuclear freeze approach
- `self-modifying-loop-GLITCH-20SEC-v3.html` - 20-second holds + glitch
- `self-modifying-loop-WORKING-SHAPES-v2.html` - Initial shape system
- `self-modifying-loop-SHAPES-v1.html` - First shapes attempt

## 🎨 Geometric Forms

| Form | Description | Color Palette |
|------|-------------|---------------|
| **Spiral** | Archimedean spiral with 3-5 turns | Purple/Violet |
| **Grid** | Regular grid with rotation | Green |
| **Circles** | 5-7 concentric rings | Cyan/Blue |
| **Wave** | Sine wave pattern | Aqua |
| **Star** | 5-7 pointed star | Gold/Yellow |
| **DNA** | Double helix structure | Pink/Magenta |
| **Polygon** | 3-7 sided polygon | Orange/Red |
| **Galaxy** | Spiral arms with scatter | Deep Purple |

## 🛠️ Technical Details

### Architecture
- **Dual-clock sync engine** for precise audio-visual synchronization
- **Form generators** create target positions mathematically
- **1:1 particle assignment** - each particle owns one target
- **Progressive morphing** with smooth force curves
- **Audio analysis** via Web Audio API AnalyserNode

### Key Innovations
- **No image processing** - pure procedural generation
- **No teleportation lag** - smooth attraction forces
- **Form-specific colors** - instant visual recognition
- **Off-center positioning** - dynamic compositions
- **Constant evolution** - never boring

## 🎯 Design Philosophy

> "Une claque chaque 5 secondes" - A wow moment every 5 seconds

The system prioritizes:
1. **Instant recognition** - Clear geometric forms
2. **Infinite variety** - Never the same twice
3. **Zero lag** - Smooth 60 FPS performance
4. **Pure beauty** - Mathematical elegance
5. **Constant evolution** - Always changing

## 🤝 Credits

Created with **Claude Sonnet 4.5** in collaboration with user vision.

## 📜 License

MIT License - Free to use, modify, and distribute
