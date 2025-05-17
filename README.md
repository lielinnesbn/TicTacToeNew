Tic Tac Toe – Unity Project
Description:
This project is a classic Tic Tac Toe game developed in Unity using C# and the Unity UI system. The player competes against a simple AI opponent in a 3x3 grid. The game includes logic to handle player input, determine game outcomes (win, loss, draw), and reset the board.
Controls:
• Mouse Click – Select a square to place your mark (“X”)
 • Restart Button (optional) – Clears the board to start a new game
Game Logic & AI Behavior:
Player:
 • Plays as “X”
 • Can select any unoccupied square on their turn
AI:
 • Plays as “O”
 • Chooses a random empty square when it’s its turn
 • Reacts immediately after the player’s move unless the game is over
Project Duration:
Approximate Time: ~1 week
 • Days 1–2: UI setup (buttons, text, grid layout) and implementation of core game logic, including player input handling and win condition checks
 • Day 3–4: AI behavior and game state tracking
 • Day 5–7: Debugging, polish, and optional UI improvements
Challenges Faced:
• NullReferenceException Errors: Initial setup required careful assignment of buttons and TextMeshPro components in the Unity Inspector to avoid null errors.
 • UI Debugging: Ensuring that the player’s and AI’s marks were properly displayed involved diagnosing issues in the PlayerMove and MarkSquare logic.
 • WebGL Compatibility: Additional testing was needed to ensure UI responsiveness when running the game in a browser build.
