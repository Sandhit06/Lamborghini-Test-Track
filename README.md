<h1 align="center"><b>🏎️ Lamborghini Drift & Stunt Simulator 🏁</b></h1>

<p align="center">
Experience the thrill of high-speed racing and precision drifting in a stunning <b>Unity</b>-powered Lamborghini driving simulator backed by <b>.NET</b> for scalable game logic.
</p>

![Gameplay Screenshot](https://global.discourse-cdn.com/forza/original/4X/2/0/d/20d8eecfd34afc270a754d39ac5fb05485caf4b3.webp)

---

## 🚀 Features

- [x] 🏎️ **Realistic Lamborghini Driving Physics**
- [x] 🔁 **360° Looping Track** — Full vertical circular track for wild stunts!
- [x] 🌀 **Inclined Planes & Ramps** — Physics-based slope handling.
- [x] 💨 **Nitro Boost System** — Temporary speed surge with effects.
- [x] 🛞 **Advanced Drifting Mechanics** — Drift like a pro using tuned wheel physics.
- [x] 🌍 **Test Track Environment** — Designed for testing top speed, control, and jumps.
- [x] 💥 **Crash Effects & Skidmarks** — Immersive visual feedback.
- [x] 🎮 **Gamepad + Keyboard Input Support**

---

## 🧱 High-Level Architecture

- **Frontend**: Unity (C#) used to build the interactive environment, car physics, and animations.
- **Backend**: .NET handles race logic, scoring, timing, and persistence for future leaderboard expansion.
- **Physics System**: Unity’s Rigidbody + custom wheel collider tuning for smooth vehicle dynamics.
- **Effects**: Trail renderers, particle systems, and shaders for nitro & drift visuals.

---

## 🔩 Core Components

- **CarController**: Manages acceleration, steering, braking, and nitro boost logic.
- **DriftSystem**: Calculates slip angles and triggers drift animations and scoring.
- **NitroManager**: Handles boost refill, usage cooldown, and VFX.
- **TrackManager**: Spawns and maintains the 360° loop and inclined ramps.
- **ScoreSystem**: Tracks time, stunt bonuses, and drift score.
- **CameraSystem**: Dynamic chase cam with cinematic drift zooms.
- **UIManager**: Displays speedometer, boost meter, drift score, and pause menu.

---

## 🎮 Gameplay Flow

### 1. Start Engine
- Choose your Lambo and start from the test track.

### 2. Drive, Drift, Boost!
- Use arrow/WASD or gamepad to navigate.
- Tap `Shift` or a gamepad button to activate **Nitro Boost**.
- Trigger drifts on corners for score bonuses.

### 3. Conquer the Stunt Track
- Attempt loops, steep ramps, and physics-defying 360° flips.

### 4. Score & Replay
- Check your drift stats and stunt performance post-run.
- Restart or change camera modes for cinematic replay.

---

## 🛠️ Optimizations

- **Object Pooling**: Reuse boost and drift effects for performance.
- **FixedUpdate Physics**: Ensures consistent behavior across platforms.
- **LOD & Culling**: Performance scaling on mobile/WebGL builds.
- **Touch Input Ready**: Mobile-friendly controls included.

---

## 🧪 Setup & Run Locally

1. Clone this repository:
```bash
git clone https://github.com/Sandhit06/Lamborghini-Test-Track.git
```
2. Open the project in Unity (Recommended: Unity 2021.3+ LTS)
3. Press ▶️ to play in the editor or build for your desired platform.

## Build Targets
- ✅ Unity Editor (PC/macOS)

- ✅ Windows Executable (.exe)

- ✅ Android APK
  
- ✅ WebGL (in-browser experience)

## Demo

https://github.com/user-attachments/assets/09cf8807-2926-4aa4-aa73-b747dc651860

## Still need help?
Open an issue on our GitHub repository, and we will help you as soon as possible.

Enjoy exploring and extending this project! Feel free to contribute and suggest improvements.

## Contact

If you want to contact me you can reach me at [Twitter](https://x.com/SandhitK).

## Developer
<table>
    <tr align="center">
        <td>
        Sandhit Karmakar
        <p align="center">
            <img src = "https://avatars.githubusercontent.com/u/90787826?v=4" width="150" height="150" alt="Dhruv Shah">
        </p>
            <p align="center">
                <a href = "https://github.com/Sandhit06">
                    <img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/>
                </a>
                <a href = "https://www.linkedin.com/in/sandhit-karmakar/" target="_blank">
                    <img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
                </a>
                <a href = "mailto:sandhitkarmakar@gmail.com" target="_blank">
                    <img src = "https://www.iconninja.com/files/312/807/734/share-send-email-chat-circle-message-mail-icon.svg" width="36" height="36" alt="Email"/>
                </a>
            </p>
        </td>
    </tr>
</table>

<p align="center">
    Made with ❤️ by <a href="https://github.com/Sandhit06">Sandhit Karmakar</a>
</p>
