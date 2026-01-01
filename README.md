# 🕹️ 2D Platformer Game

A feature-rich 2D side-scroller platformer where gameplay meets creativity. This game delivers tight controls, visually layered environments, enemy interactions, and progressive unlockable abilities – all developed in Unity using a modular, scalable design approach.

---

## 🎮 Game Overview

In this game, players embark on a journey through layered pixel worlds filled with traps, platforms, and hostile enemies. Players can run, jump, dash, and later unlock advanced abilities like wall-jumping or fireball attacks. The game is structured in levels and offers the flexibility to expand with new scenes and worlds.

---

## 🌈 Key Features

- 👟 **Responsive Movement:** Smooth WASD-based movement with jump buffering and coyote time for polished platforming feel.
- ⚔️ **Enemy AI:** Patrolling, chasing, and attacking enemies with basic hit-detection and health logic.
- 🔓 **Unlockable Abilities:** Dash, wall-jump, and fire attack can be unlocked level-by-level or by collectibles.
- 🎨 **Level Design:** Designed using Unity's Tilemap system and Palette Brushes for efficient modular environment creation.
- 🧠 **Modular Scripts:** Organized code architecture for Player, Enemy, UI, Effects, and World Management.
- 🎥 **Camera System:** Dynamic camera behavior using Cinemachine for smooth following and zoom during key events.
- 🌌 **Parallax Backgrounds:** Multi-layered visual depth through parallax scrolling backgrounds.
- 🔊 **Audio Integration:** Background music and FX for actions like jumping, dashing, enemy hits, etc.

---

## 🛠️ Technologies Used

| Tool        | Purpose                           |
|-------------|-----------------------------------|
| Unity       | Game engine & level design        |
| C#          | Scripting language                |
| Tilemap     | Environment layout & map logic    |
| Animator    | Player & enemy animations         |
| Cinemachine | Smooth camera transitions         |
| DOTween     | (Optional) UI / FX animations     |

---

## 🧩 Project Structure
Assets/
├── Animations/
├── Audio/
├── Materials/
├── Prefabs/
├── Scenes/
│ └── MainScene.unity
├── Scripts/
│ ├── Player/
│ ├── Enemies/
│ ├── Abilities/
│ ├── UI/
│ └── GameManager/
├── Sprites/
├── Tiles/
└── Resources/


> 📦 The project is intentionally kept modular to easily allow new enemies, abilities, or map expansions without rewriting core logic.

---

## 🗺️ Level Design Notes

- 🎮 All levels are created using Unity’s **Tile Palette**, enabling quick placement and reuse of environmental tiles.
- 🧱 Environment interactions (like breaking platforms, hazards, or hidden passages) are implemented using **composite colliders** and layer-based physics rules.
- ✨ Optional custom tiles like bounce-pads, moving platforms, and checkpoints are included for more dynamic level design.

---

## 🚀 Getting Started

### Prerequisites

- [Unity Hub](https://unity.com/download) (Recommended version: **2022.3 LTS** or later)
- Git (or simply download as ZIP)

### Installation

```bash
git clone https://github.com/your-username/2d-platformer-game.git

