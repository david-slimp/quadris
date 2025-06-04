# Quadris - Minimum Viable Product (MVP)

## 🎯 Core Objective
Create a functional, playable falling blocks game with the absolute minimum set of features required for the core gameplay experience.

## 🎮 MVP Features

### 1. Game Board
- [x] 10x20 grid playing field
- [x] Visible grid lines or borders
- [x] Game over detection when blocks reach the top

### 2. Blocks (Quadrominoes)
- [x] Implement all 7 standard quadromino shapes (I, O, T, L, J, S, Z)
- [x] Different colors for each shape
- [x] Block spawning at the top center

### 3. Basic Controls
- [x] Move left/right
- [x] Rotate clockwise
- [x] Soft drop (faster fall)
- [x] Hard drop (instant drop to bottom)

### 4. Game Mechanics
- [x] Block collision detection
- [x] Line clearing when a row is filled
- [x] Score tracking (basic)
- [x] Progressive difficulty (speed increases with level)

### 5. User Interface
- [x] Score display
- [x] Level display
- [x] Next piece preview
- [x] Game over screen

## 🚫 Out of Scope for MVP
- Sound effects
- High score persistence
- Pause functionality
- Mobile touch controls
- Start screen/menus
- Settings/options
- Animations (beyond basic movement)

## 🧪 Testing Requirements
- [ ] All blocks can be moved left/right until hitting walls or other blocks
- [ ] All blocks can be rotated without clipping issues
- [ ] Blocks stack correctly when landing
- [ ] Lines clear when completely filled
- [ ] Game ends correctly when blocks reach the top
- [ ] Score increases appropriately for line clears
- [ ] Game speed increases with level

## 📦 Technical Requirements
- [x] Single HTML file with embedded CSS/JS
- [x] No external dependencies
- [x] Works in modern browsers (Chrome, Firefox, Safari, Edge)
- [x] Responsive design (minimum 320px width)

## ✅ Success Criteria
The MVP will be considered complete when:
1. A user can play a complete game from start to game over
2. All core mechanics work as expected
3. No critical bugs prevent gameplay
4. Basic scoring and level progression function

## 📝 Notes
- Focus on functionality over polish
- Keep the code simple and maintainable
- Document any known issues or limitations
- Performance should be acceptable but doesn't need to be optimized
