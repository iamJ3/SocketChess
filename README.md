# Real-Time Chess Game

A real-time chess game clone inspired by Chess.com. Players can compete against each other with live move updates and synchronized game states.
![image](https://github.com/user-attachments/assets/8cbb84ae-7fff-4ff4-a01f-dbb9df42eca8)


## Features
- **Real-Time Gameplay:** Moves are updated live for all players.
- **Drag-and-Drop Interface:** Easy piece movement with drag-and-drop functionality.
- **Player Roles:** Automatically assigns and restricts roles (white or black) to players.
- **Board Synchronization:** Consistent game state across all clients.

## Technologies
- **Backend:** Node.js, Express.js, Socket.IO
- **Frontend:** HTML, CSS (Tailwind CSS), JavaScript
- **Chess Logic:** `chess.js`

## Setup
1. Clone the repository:
    ```bash
    git clone https://github.com/iamJ3/SocketChess
    cd SocketChess
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the server:
    ```bash
    npm start
    ```

4. Open `http://localhost:3000` in your browser to play the game.

## License
This project is licensed under the MIT License.
