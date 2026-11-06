<div align="center">

# 🚀 AirCraft
### 🌌 3D Galaxy Gesture Intelligence Platform 🌌
**Touchless Air-Canvas & Real-Time Celestial Particle Synthesizer**  
*Powered by Google MediaPipe Computer Vision, HTML5 3D Canvas & Procedural Web Audio*

---

[![Status](https://img.shields.io/badge/Status-Active%20%26%20Optimized-00ffcc?style=for-the-badge&logo=satellite&logoColor=black)](#)
[![Tech](https://img.shields.io/badge/Engine-Vanilla%20JS%20%7C%20Canvas2D-7928CA?style=for-the-badge&logo=javascript&logoColor=white)](#)
[![Vision](https://img.shields.io/badge/AI%20Vision-Google%20MediaPipe-ff007f?style=for-the-badge&logo=google&logoColor=white)](#)
[![Audio](https://img.shields.io/badge/Sound-Procedural%20Web%20Audio-00d4ff?style=for-the-badge&logo=soundcharts&logoColor=black)](#)
[![License](https://img.shields.io/badge/License-MIT-gold?style=for-the-badge)](#)

</div>

---

## 🌌 Overview

**AirCraft** turns your ordinary webcam into an interactive, 3D deep-space gesture console. By tracking 21 3D hand landmarks in real time with sub-millisecond precision, AirCraft lets you command cosmic particle storms, paint glowing starlight calligraphy in mid-air, and trigger cinematic visual magic without ever touching your keyboard or mouse.

Built with pure vanilla web technologies, AirCraft requires **zero installation**, **zero npm build steps**, and runs completely client-side inside a single lightweight file.

---

## 💫 Core Features

- 🌌 **Hyperdrive 3D Starfield Warp Engine**: Over 120 depth-projected stars streak through your field of view, accelerating dynamically based on your hand gestures.
- 🎆 **Cinematic Full-Screen FX**: Experience full-screen multi-stage Diwali fireworks bursts, blooming multi-quadrant floral gardens, and cascading heart showers.
- ✍️ **Starlight Air-Canvas**: Draw fluid, glowing neon ribbons directly in the air with index-finger tracking and pinch-to-lift mechanisms.
- 🔊 **Procedural Web Audio Synthesizer**: 100% synthesized sound effects — cosmic crackles, harmonic bells, thunder rumbles, and laser pulses generated mathematically on the fly (no external audio files!).
- ⚡ **Ultra-Lightweight & Smooth (60 FPS)**: Optimized MediaPipe AI pipeline with frame drop guards for silky-smooth performance on any laptop.
- 🛡️ **100% Private & Offline Capable**: Your webcam stream never leaves your browser. All AI inference runs locally in memory.

---

## 🪄 Visual Gestures & Cosmic Magic

AirCraft features an orientation-invariant gesture engine that instantly recognizes natural hand poses:

| Gesture | Magic Name | Cosmic Effect on Screen | Procedural Audio |
| :--- | :--- | :--- | :--- |
| 👏 **Clap** | **Diwali Pataakha** | Multi-point sky fireworks bursting across the screen with colorful sparks, flash & trailing smoke | Crackling burst & boom |
| 💖 **Love Sign** (`🤟` / `🫶`) | **Cosmic Heart Rain** | Cascading shower of floating ruby red, glowing pink, and white neon hearts | Ethereal harp chimes |
| 🌸 **Lotus Mudra** (Wrists together, fingers open) | **Blooming Garden** | Vibrant multi-colored flowers blooming organically across different parts of the screen | Soft blossom harmony |
| 👍 **Thumbs Up** | **Star Confetti** | Radiant shower of spinning golden stars & shimmering stardust | Sparkle glissando |
| ✌ **Peace Sign** | **Aurora Wave** | Flowing iridescent rainbow auroral ribbons undulating through deep space | Ambient solar resonance |
| ✊✊ **Double Fists** | **Cosmic Thunderstorm** | Piercing electric lightning bolts cutting through the void with screen flashes | Deep sub-bass thunder |
| 🙏 **Namaste** | **Divine Sunburst** | Brilliant sacred geometry sunburst emitting radiant golden aura rings | Cathedral resonance |
| ☝ **Point Index** | **Starlight AirCanvas** | Draw luminous neon calligraphy lines floating in space | Smooth brush frequency |
| 🤏 **Pinch** (Thumb + Index) | **Pen Lift / Pulse** | Lifts the drawing pen or casts a cosmic starlight pulse wave | Harmonic snap |
| 🤚 **Shake Open Palm** | **Black Hole Purge** | Radial space gauge charges up to instantly wipe and refresh the AirCanvas | Cosmic vacuum sweep |

---

## 🛠️ Architecture & Tech Stack

```
   [ Webcam Video Stream ] (640x480 Optimized)
              │
              ▼
   [ Google MediaPipe Hands ML ] ─── Model Complexity: 0 (Ultra Fast)
              │
              ▼
   [ Gesture Recognition Engine ] ── Invariant Angle & Distance Math
              │
       ┌──────┴────────────────────────┐
       ▼                               ▼
[ 3-Layer Canvas Renderer ]     [ Web Audio API Synth ]
 ├─ Layer 1: 3D Starfield Warp   ├─ Explosive Noise Buffers (Fireworks)
 ├─ Layer 2: Cosmic Particle FX  ├─ Sine/FM Harmonic Bells (Love/Lotus)
 └─ Layer 3: Neon AirCanvas Paint └─ Low-Pass Filtered Bass (Thunder)
```

- **Frontend Core**: Vanilla HTML5, CSS3 Glassmorphism, Modern ES6+ JavaScript.
- **Computer Vision**: Google MediaPipe Hands (`@mediapipe/camera_utils`, `@mediapipe/hands`).
- **Graphics Pipeline**: Multi-layered HTML5 2D Canvas with sub-pixel interpolation and dynamic composite blending (`destination-over`, `lighter`).
- **Sound Generation**: Web Audio API with dynamically shaped GainNodes, BiquadFilters, and custom audio buffer noise generators.

---

## 🚀 Quick Start Guide

You don't need Node.js, Python, or Docker. It works right out of the box!

### 1. Clone the Repository
```bash
git clone https://github.com/Sahina-coder/AirCraft.git
cd AirCraft
```

### 2. Launch the Application
Simply double-click **`aircraft.html`** to open it in your browser, or serve it locally:

```bash
# Using Python (Optional):
python -m http.server 8000

# Using Node (Optional):
npx serve .
```

### 3. Setup Your Space
1. Allow webcam permissions when prompted by your browser.
2. Sit approximately **1.5 to 2.5 feet (0.5 - 0.8 meters)** away from the camera in a reasonably lit room.
3. Bring your hands into view and watch the magic unfold!

---

## 🎮 Controls & Sci-Fi HUD

| Element | Description |
| :--- | :--- |
| **Mode Selector** | Toggle between **Draw Mode** (neon air calligraphy), **Orbit Mode** (celestial particle control), and **Zen Mode**. |
| **Color Palette** | Select your neon ink: Cyan Nebula, Solar Gold, Plasma Pink, Emerald Aurora, or Radiant White. |
| **Sound Toggle (`🔊`)** | Enable or mute real-time procedural audio synthesis. |
| **Save Button (`💾`)** | Download your mid-air artwork as a crisp, transparent high-res PNG. |
| **Guide Modal (`❓`)** | Bring up the interactive visual gesture cheat-sheet at any moment. |
| **Clear Canvas (`🧹`)** | Instant manual canvas wipe (or simply shake your open hand). |

---

## 🌟 Pro-Tips for the Best Experience

> [!TIP]
> - **Lighting**: Neutral, diffuse lighting produces the most reliable tracking accuracy.
> - **Clap Gesture**: Bring both hands together firmly in front of the camera to trigger the grand **Diwali Fireworks**.
> - **Lotus Mudra**: Touch your wrists together and fan out all 10 fingers to awaken the **Blooming Flower Garden**.
> - **Love Sign**: Form the classic ILY (`🤟`) sign or hand heart (`🫶`) to summon the **Full-Screen Heart Shower**.

---

## 🤝 Contributing

Contributions, feature ideas, and cosmic enhancements are warmly welcomed!

1. Fork the Project (`https://github.com/Sahina-coder/AirCraft/fork`)
2. Create your Feature Branch (`git checkout -b feature/CosmicFeature`)
3. Commit your Changes (`git commit -m 'Add some CosmicFeature'`)
4. Push to the Branch (`git push origin feature/CosmicFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<div align="center">

Crafted with 💖 and cosmic energy by **[Sahina-coder](https://github.com/Sahina-coder)**

**[⭐ Star this repository on GitHub](https://github.com/Sahina-coder/AirCraft)** if you enjoyed playing with it!

</div>
