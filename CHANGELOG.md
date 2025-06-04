# Changelog

## [0.0.2] - 2024-09-20
### Gameplay and Code Improvements

### Added
- Hard drop functionality (spacebar)
- Counter-rotation (Z key)
- Pause functionality (P key)
- Debug panel with game state information
- Pause screen with instructions
- Smoother piece movement and animations
- Better next piece preview

### Changed
- Refactored game state management into a `gameState` object
- Improved scoring system with better level progression
- Optimized rendering and game loop using delta time
- Enhanced collision detection
- Improved piece rotation logic
- Better game over handling

### Fixed
- Line clearing logic improvements
- Fixed edge cases in piece placement
- Improved performance with optimized rendering


## [0.0.1] - 2024-09-17
### Initial Game Implementation

### Added
- Basic Quadris (falling blocks) game implementation
- Game features:
  - All standard Quadromino pieces (I, O, T, L, J, S, Z)
  - Score tracking
  - Level progression
  - Next piece preview
  - Basic controls (left, right, rotate, drop)
  - Line clearing mechanics
  - Basic sound effects placeholder
- Responsive game canvas with scoreboard
- Color-coded quadromino pieces
- Game over detection

### Technical Details
- Built with vanilla JavaScript and HTML5 Canvas
- No external dependencies
- Modular code structure with separate functions for game logic
- Placeholder for sound effects (base64 encoded)

### Known Issues
- Sound effects need to be implemented
- No high score system
- No pause functionality
- No game start screen
- No mobile touch controls

### Added
- Default .gitignore
- LICENSE-MIT.txt
- Default README.md

### Changed
- CHANGELOG.md

### Known Issues
- Need to create PRD.md, MVP.md and dev_notes.txt

