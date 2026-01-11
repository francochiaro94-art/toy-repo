# toy-repo
Toy Repo to Play Around

## 🎮 Stranger Things Pong

A retro Pong game with Stranger Things-inspired neon aesthetics, synthwave music, floating particle effects, and psychic powers! Battle the computer with special abilities and survive reality-bending instability phases.

### 🚀 Play Now

**[▶️ Click Here to Play](https://francochiaro94-art.github.io/toy-repo/pong.html)**

Or open locally:
```bash
open pong.html
```

### 🎮 Controls

- **Arrow Keys (Up/Down)** or **Mouse**: Control left paddle
- **P Key**: Activate charged power (5 consecutive hits required)
- **E Key**: Activate Telekinesis (11 consecutive hits required)
- **Arrow Keys (during Telekinesis)**: Steer the ball in any direction
- **Space/Enter**: Restart game after game over
- **🔊 Music Button**: Toggle background music on/off

### ⚡ Power Systems

#### Psychic Powers (P Key)
Hit the ball **5 times consecutively** to charge your power bar. Press **P** to activate one of 5 rotating powers:

1. **🌀 Upside Down** - Slow time! Ball moves at 60% speed (4 seconds)
2. **🛡️ Psychic Shield** - Paddle expands 50% taller for easier defense (5 seconds)
3. **🌫️ Mind Fog** - Computer reaction slowed to 40% (5 seconds)
4. **🌊 Portal Jump** - Ball teleports 100px forward at midline (instant)
5. **🧲 Vecna's Pull** - Ball curves toward your paddle (4 seconds)

Powers cycle through in order. Missing the ball resets your charge to 0%!

#### Telekinesis Power (E Key)
Hit the ball **11 times consecutively** to charge the cyan Telekinesis bar. Press **E** to activate:

- **⚡ Telekinetic Control** - For 5 seconds, use arrow keys to steer the ball in any direction!
  - Up/Down: Vertical steering
  - Left/Right: Horizontal steering
  - Ball gains a cyan aura during activation

Both power bars charge in parallel from the same hits!

### 🌪️ Exotic Matter Stability

Reality isn't stable in the Upside Down! Watch the stability bar on the right:

- **Stable Phase** - Stability drains over 10 seconds from 100% → 0%
- **Unstable Phase** - When stability hits 0%, chaos erupts for 5 seconds:
  - 🪨 **Reality Fractures**: Floating debris obstacles appear
  - 📺 **Screen Shake**: CRT glitch effects and camera shake
  - ⚠️ **Collision Risk**: Hit debris and the ball bounces unpredictably
- Cycle repeats: Stable → Unstable → Stable...

### ✨ Features

- 🌟 **Neon Stranger Things Aesthetic**: Red and pink glowing elements with CRT scanline effects
- 🎵 **Synthwave Background Music**: Original 80s-inspired dark minor key composition using Web Audio API
- ✨ **Floating Particles**: Atmospheric embers drifting across the entire screen like ash from the Upside Down
- ⚡ **Dual Power Systems**: 5 psychic powers (P key) + Telekinesis ball steering (E key)
- 🌪️ **Reality Instability**: Cycling stable/unstable phases with obstacles and screen effects
- 🎯 **Smart Controls**: Seamless switching between keyboard and mouse input
- 🏆 **First to 5 Wins!**
- 💪 **Player vs VECNA**: You're HAWKINS defending against the computer opponent

---

> **Note:** To enable the live GitHub Pages link, go to your repository **Settings → Pages → Source → Select "main" branch → Save**
