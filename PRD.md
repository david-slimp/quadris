Product Requirements Document (PRD): "Quadris" – Online Web-Based Falling Block Puzzle Game
Product Name: Quadris
Platform: Web (HTML5, CSS, JavaScript)
Target Devices: Desktop, Tablet, Mobile (responsive design)
Release Version: 0.1.0 (MVP)
Date: June 3, 2025

1. Purpose and Scope
Quadris is a modern, browser-based puzzle game inspired by classic falling block mechanics. Players manipulate falling geometric shapes, rotating and positioning them to complete horizontal rows. Completed rows are cleared, earning points and making room for more blocks. The game becomes progressively more challenging as the speed of falling blocks gradually increases with each cleared row.

2. Target Audience
- Casual gamers seeking quick, engaging gameplay
- Fans of puzzle and skill-based games
- All ages (suitable for children and adults)
- Desktop and mobile web users

3. Gameplay Overview
- Blocks of various shapes fall from the top of the grid.
- Players can move and rotate blocks as they descend.
- Completing a full horizontal row clears that row and awards points.
- Cleared rows increase the drop speed of subsequent blocks.
- The game ends when the stack of blocks reaches the top of the grid.

4. Core Features
4.1. Game Mechanics
Falling Blocks:
- Blocks fall from the top at a constant initial speed.
- Speed increases incrementally as more rows are cleared.

Block Control:
- Move left/right
- Rotate clockwise/counterclockwise
- Soft drop (increase fall speed temporarily)
- Hard drop (instantly place the block)

Row Completion:
- When a row is completely filled with blocks, it is cleared.
- Multiple rows can be cleared simultaneously for bonus points.

Scoring System:
- Points awarded per cleared row, with bonuses for clearing multiple rows at once.
- Display current score and high score.

Game Over Condition:
- Game ends when new blocks cannot enter the grid due to stacked blocks reaching the top.

4.2. User Interface
Main Menu:
- Start Game
- View High Scores
- Instructions/How to Play
- Settings (sound, controls)

In-Game UI:
- Game grid (visible playfield)
- Next block preview
- Score and level display
- Pause/Resume button

Game Over Screen:
- Final score
- Option to restart or return to main menu

4.3. Controls
Desktop:
- Arrow keys or WASD for movement and rotation
- Spacebar for hard drop
- P or Esc to pause

Mobile/Tablet:
- On-screen buttons for movement, rotation, and drop
- Touch gestures (optional)

Accessibility:
- Option to remap keys
- Colorblind-friendly mode

4.4. Progression and Difficulty
Levels:
- Each set number of cleared rows increases the level.
- Each level increases the block fall speed.

Difficulty Curve:
- Gradual speed increase to maintain challenge and engagement.

4.5. Visuals and Audio
Graphics:
- Clean, modern, colorful block designs.
- Simple background with high contrast for visibility.

Animations:
- Smooth block movement and rotation
- Row-clearing effects

Sound:
- Background music (toggleable)
- Sound effects for movement, rotation, row clear, and game over (toggleable)

5. Technical Requirements
Technology Stack:
- HTML5 Canvas for rendering
- CSS3 for styling and responsive layout
- JavaScript (ES6+) for game logic and interactivity

Performance:
- Optimized for smooth gameplay at 60 FPS on modern browsers
- Responsive design for all screen sizes

Browser Compatibility:
- Chrome, Firefox, Safari, Edge, and mobile browsers

6. Non-Functional Requirements
Accessibility:
- Keyboard and touch support
- Colorblind mode

Localization:
- English (v0.1.0), with future support for other languages

Data Storage:
- Local storage for high scores and settings

Security:
- No user authentication required
- Secure handling of local data

7. Future Enhancements (Post-Launch)
- Multiplayer mode (head-to-head or cooperative)
- Achievements and missions
- Online leaderboards
- Additional block shapes and themes
- Customizable controls and appearance
- Cloud sync for high scores

8. Success Metrics
- User retention and session length
- Number of games played per user
- High score submissions
- Positive user feedback and ratings

9. Out of Scope
- No downloadable app (web-only for v1.0)
- No real-money transactions or in-app purchases
- No user accounts or social media integration at launch

10. References and Inspiration
- Falling Blocks Puzzle games
- Modern web-based puzzle game best practices

Appendix: Sample Game Flow
- User opens Quadris in browser.
- Main menu appears with options to start, view scores, or read instructions.
- User starts a new game; blocks begin to fall.
- User manipulates blocks to complete rows.
- Score increases as rows are cleared; fall speed increases.
- Game ends when blocks reach the top.
- Game Over screen displays score and options to restart or return to menu.

Quadris aims to deliver a familiar yet fresh falling block puzzle experience, optimized for modern web play and accessible to a broad audience.

