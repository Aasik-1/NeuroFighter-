# ⚡ NEUROFIGHTER — Think Smart. Fight Hard.

A fully browser-based educational fighting game where **you** are the hero.

---

## 🎮 FEATURES

### Avatar System
- Upload your real face photo → becomes your in-game fighter
- Customize armor color (10 colors), accessories (8 options), hairstyle (4 options)
- Save your profile with your name

### Gameplay — 20 Levels
| Levels | Topic | Environments |
|--------|-------|-------------|
| 1–5 | Basic Arithmetic | Neon City, Cyber Alley, Fire Arena, Ice Cavern, Shadow Lair |
| 6–10 | Fractions & % | Jungle Ruins, Sky Platform, Deep Ocean, Lava Fields, Void Realm |
| 11–15 | Algebra Basics | Storm Summit, Crystal Maze, Toxic Swamp, Neon Matrix, Cyber Fortress |
| 16–20 | Logic & Probability | Space Station, Quantum Core, Time Rift, Singularity, Final Nexus |

### Combat System
| Action | PC Key | Mobile |
|--------|--------|--------|
| Move | WASD / Arrow Keys | D-Pad |
| Punch | Z | PUNCH button |
| Kick | X | KICK button |
| Special Attack | C | SPECIAL button |
| RAGE MODE | V | RAGE button |
| Pause | ESC | PAUSE button |

### Education System
- Beat each level → take a Math Quiz
- Pass the quiz → unlock next level
- Fail → retry the battle
- Progressive difficulty: Arithmetic → Fractions → Algebra → Logic

### Rewards
- Earn coins per level
- Buy upgrades, accessories, and power boosts in the Shop
- Combo multipliers for chaining hits

### Boss Fights
Boss battles at **Levels 5, 10, 15, and 20** — harder enemies, higher stakes!

---

## 📁 PROJECT STRUCTURE

```
neurofighter/
├── index.html        ← Complete game (self-contained)
├── README.md         ← This file
└── assets/           ← (optional) for custom sounds/images
```

---

## 🚀 GITHUB PAGES HOSTING

### Step 1 — Create Repository
```bash
# On GitHub.com, create a new repo named: neurofighter
# Or use CLI:
gh repo create neurofighter --public
```

### Step 2 — Upload Files
```bash
git clone https://github.com/YOUR_USERNAME/neurofighter.git
cd neurofighter
cp /path/to/index.html .
cp README.md .
git add .
git commit -m "🚀 Launch NeuroFighter v1.0"
git push origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Settings → Pages
3. Source: **Deploy from a branch**
4. Branch: **main** / **(root)**
5. Click **Save**
6. Wait ~2 minutes
7. Your game is live at: `https://YOUR_USERNAME.github.io/neurofighter`

---

## 🎨 CUSTOMIZATION

### Adding Real Sound Effects
Add to `<head>` section and create Audio objects:
```javascript
const sounds = {
  punch: new Audio('assets/punch.mp3'),
  kick: new Audio('assets/kick.mp3'),
  bgm: new Audio('assets/bgm_neon.mp3'),
};
```

Free sounds from: https://freesound.org (search: punch, kick, game bgm)

### Suggested Assets Folder
```
assets/
├── sounds/
│   ├── punch.mp3
│   ├── kick.mp3
│   ├── special.mp3
│   ├── rage.mp3
│   ├── victory.mp3
│   └── bgm/
│       ├── neon.mp3
│       ├── fire.mp3
│       └── space.mp3
└── icons/
    └── favicon.ico
```

---

## 🧠 EDUCATIONAL CONTENT BREAKDOWN

| Level | Topic | Example Question |
|-------|-------|-----------------|
| 1 | Addition | 7 + 5 = ? |
| 2 | Subtraction | 15 - 8 = ? |
| 3 | Multiplication | 6 × 4 = ? |
| 4 | Division | 36 ÷ 9 = ? |
| 5 | BODMAS | 3 + 4 × 2 = ? |
| 6 | Fractions | ½ of 20 = ? |
| 7 | Adding Fractions | 1/4 + 2/4 = ? |
| 8 | Percentages | 25% of 80 = ? |
| 9 | Percentage Calc | 30 is __% of 50 |
| 10 | Decimals | 3/4 as decimal = ? |
| 11 | Algebra | x + 5 = 12 |
| 12 | Algebra | 3x = 18 |
| 13 | Like Terms | 2x + 3x = ? |
| 14 | Linear Equations | 2x - 4 = 10 |
| 15 | Identify Equation | Which is linear? |
| 16 | Patterns | 2,4,8,16,__ |
| 17 | Logic | Syllogism |
| 18 | Sets | A∩B = ? |
| 19 | Probability | P(rolling 3) |
| 20 | Mixed | 2³ + √16 = ? |

---

## 💡 TECH STACK
- **Pure HTML5 / CSS3 / JavaScript** — no frameworks needed
- **Canvas 2D API** — game rendering
- **LocalStorage** — save/load player progress
- **CSS Animations** — UI effects, particles
- **FileReader API** — face photo upload

---

Built with ❤️ for NeuroChat AI ecosystem | University of Moratuwa
