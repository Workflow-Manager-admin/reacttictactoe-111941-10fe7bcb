build # Lightweight React Template for KAVIA

This project provides a minimal React template with a clean, modern UI and minimal dependencies.

---

# Tic Tac Toe Main App (ReactTicTacToe)

## Features Implemented

- **Minimalistic, modern UI**: Clean, light-theme layout and three-color scheme.
- **Real-time updates**: Frontend connects to backend using websocket for game events.
- **Game logic processing**: Backend validates moves, stores state, and checks win/draw.
- **User management**: Users can join as player X or O, or spectate.

## Color Scheme

- Primary: #4CAF50 (used for buttons/board X)
- Secondary: #FFC107 (used for current user, turn indication, alerts)
- Accent: #2196F3 (used for board O, highlights)

## Development

The frontend React app is in `reacttic_tac_toe/`. 

A minimal FastAPI backend for game logic and websocket communication will be added under `backend/` (structure to be generated).

---

## How to Run

1. Start the backend: See `backend/README.md` (to be created)
2. Start the frontend:
    ```
    cd reacttic_tac_toe
    npm install
    npm start
    ```

---

## Customization

To change colors, update the variables at top of `src/App.css`.
