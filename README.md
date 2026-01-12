# Cosmic Hand Control

An interactive 3D space scene with gesture-controlled floating blocks using **MediaPipe** hand tracking and **Three.js** for immersive 3D visualization.

## 🚀 Features

- **Hand Gesture Recognition**: Uses MediaPipe Vision AI to detect and track hand movements in real-time
- **3D Interactive Environment**: Built with React Three Fiber for smooth 3D rendering
- **Gesture-Based Controls**:
  - 🖐️ **Open Palm**: Highlight and select the nearest block
  - ✊ **Closed Fist**: Grab and move selected blocks
  - 👉 **Pinch**: Rotate blocks in 3D space
  - 🔄 **Swipe**: Reset the scene and reorganize blocks
- **Particle Effects**: Dynamic particle system for visual polish
- **Responsive Design**: Adapts to different screen sizes with Tailwind CSS

## 📋 Tech Stack

- **Frontend Framework**: React 19 with TypeScript
- **3D Graphics**: Three.js with React Three Fiber
- **Hand Tracking**: MediaPipe Tasks Vision
- **State Management**: Zustand
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with PostCSS
- **Icons**: Lucide React

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/lINNkHANTkYAW/Cosmic-Hand-Control.git
   cd cosmic-hand-control
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start development server**:
   ```bash
   npm run dev
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

5. **Preview production build**:
   ```bash
   npm run preview
   ```

## 🎮 Usage

1. **Allow Camera Access**: Grant the application permission to access your webcam
2. **Position Hands**: Ensure your hands are clearly visible to the camera
3. **Use Gestures**: Interact with the floating blocks using the gesture controls listed above
4. **View Instructions**: Click the info button for detailed gesture instructions in-app

## 📁 Project Structure

```
cosmic-hand-control/
├── src/
│   ├── App.tsx                    # Main application component
│   ├── index.tsx                  # React entry point
│   ├── store.ts                   # Zustand state management
│   ├── metadata.json              # Project metadata
│   ├── index.html                 # HTML template
│   └── components/
│       ├── Scene3D.tsx            # 3D scene and floating blocks
│       ├── HandController.tsx     # Hand tracking logic
│       ├── Particles.tsx          # Particle system component
│       └── FloatingBlock.tsx      # Individual block component
├── vite.config.ts                 # Vite configuration
├── tsconfig.json                  # TypeScript configuration
├── postcss.config.mjs             # PostCSS configuration
└── package.json                   # Project dependencies
```

## 🎯 Key Components

### Scene3D.tsx
Renders the 3D environment with Three.js and manages floating blocks with lighting and effects.

### HandController.tsx
Implements MediaPipe hand tracking, gesture recognition, and state updates for block manipulation.

### Particles.tsx
Creates dynamic particle effects that enhance the visual experience.

### FloatingBlock.tsx
Individual 3D block component with materials and animations.

## 🔧 Configuration

- **Tailwind CSS**: Configured for rapid UI development
- **TypeScript**: Strict type checking enabled for reliability
- **Vite**: Fast HMR and optimized builds

## 📦 Dependencies

Key dependencies:
- `three@^0.182.0` - 3D graphics library
- `@react-three/fiber@^9.4.2` - React renderer for Three.js
- `@react-three/drei@^10.7.7` - Useful React Three Fiber helpers
- `@mediapipe/tasks-vision@^0.10.22` - Hand tracking AI
- `zustand@^5.0.9` - State management
- `react@^19.2.3` - UI framework

## 🌐 Browser Support

This application requires:
- A modern browser with WebGL support
- Webcam/camera access
- JavaScript enabled

## 📄 License

This project is provided as-is for educational purposes.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests with improvements!

## 📧 Contact

For questions or feedback, please open an issue on the GitHub repository.

---

**Status**: Active development | **Latest Build**: January 2026
