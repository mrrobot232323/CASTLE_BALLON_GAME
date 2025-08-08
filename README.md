# Epic Castle Scene - Three.js + TypeScript

A beautiful, interactive 3D castle scene built with Three.js and TypeScript, featuring animated characters, interactive minigames, and cinematic camera movements.

## Features

### 🏰 Epic Castle Scene
- **Elaborate Castle Design**: Multi-tower castle with walls, gates, and detailed architecture
- **Mountain Peak Setting**: Castle perched on a mountain with beautiful terrain
- **Atmospheric Effects**: Light fog, clouds, and dynamic lighting
- **Animated Elements**: 
  - Patrol guards walking the walls
  - Cannons firing periodically
  - Horses moving in the courtyard
  - Characters bustling inside the castle

### 🎮 Interactive Minigame
- **Balloon Popper**: Click to shoot projectiles and pop colorful balloons
- **Sound Effects**: Audio feedback when hitting balloons
- **Score System**: Track your score and remaining balloons
- **Visual Effects**: Particle effects and projectile animations

### 💬 Dialogue System
- **Character Interactions**: Click on characters to start conversations
- **Multiple Characters**: King, Wizard, Knight, Princess, and Merchant
- **Unique Dialogues**: Each character has their own personality and stories
- **Visual Feedback**: Characters highlight when selected

### 🎥 Camera Controls
- **Cinematic Intro**: Beautiful camera pan when the scene loads
- **Interactive Exploration**: Click and drag to rotate, scroll to zoom
- **Smooth Controls**: Responsive camera movement with touch support
- **Auto-rotation**: Subtle camera drift for cinematic effect

## Controls

- **Mouse/Touch**: Click and drag to rotate the camera
- **Scroll/Pinch**: Zoom in and out
- **Click Characters**: Start dialogue with castle inhabitants
- **Click Balloons**: Pop them in the minigame
- **Escape Key**: Close dialogue boxes

## Installation & Running

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start Development Server**:
   ```bash
   npm run dev
   ```

3. **Open Browser**:
   Navigate to `http://localhost:3000`

## Build for Production

```bash
npm run build
```

## Technology Stack

- **Three.js**: 3D graphics and rendering
- **TypeScript**: Type-safe JavaScript development
- **Vite**: Fast development server and build tool
- **Web Audio API**: Sound effects for the minigame

## Project Structure

```
src/
├── main.ts              # Main application entry point
├── CastleScene.ts       # 3D castle scene and animations
├── BalloonGame.ts       # Balloon popping minigame
├── DialogueSystem.ts    # Character interaction system
└── CameraController.ts  # Camera movement and controls
```

## Features in Detail

### Castle Architecture
- Main central tower with flag
- Four corner towers with conical roofs
- Defensive walls with patrol paths
- Multiple cannons positioned around the perimeter
- Detailed windows and lighting effects

### Character System
- **King**: Golden character with royal dialogue
- **Wizard**: Purple character with magical dialogue
- **Knight**: Green character with warrior dialogue
- **Princess**: Pink character with friendly dialogue
- **Merchant**: Brown character with trade dialogue

### Minigame Mechanics
- 10 colorful balloons spawn randomly
- Click anywhere to shoot projectiles
- Balloons pop with particle effects and sound
- Score tracking and game completion screen

### Atmospheric Effects
- Dynamic cloud system
- Fog particles for depth
- Multiple light sources (ambient, directional, point lights)
- Shadow mapping for realistic lighting

## Browser Compatibility

- Modern browsers with WebGL support
- Chrome, Firefox, Safari, Edge
- Mobile browsers with touch support

## Performance

- Optimized 3D rendering with efficient geometry
- Responsive design that works on various screen sizes
- Smooth 60fps animations
- Efficient memory management

Enjoy exploring the epic castle scene! 🏰✨
