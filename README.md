Mafia - A Real-Time Social Deduction Game

This project is a web-based, real-time implementation of the classic social deduction game, Mafia. It allows groups of friends to play together online through a simple, intuitive interface. The application is built as a single-page application and leverages a real-time database to keep all players in sync.

The user interface is designed with a thematic, 1930s-inspired aesthetic to create an immersive experience for all players.
Features

    Real-Time Gameplay: All game state changes, including player actions and phase transitions, are reflected instantly for all clients without needing to refresh the page.

    Game Lobbies: Players can create a new game lobby or join an existing one using a unique 4-digit code.

    Dynamic Role Assignment: Roles (Mafia, Sheriff, Doctor, Townsperson) are automatically and secretly assigned to players when the host starts the game.

    Interactive Day/Night Cycle: The application automatically cycles through night and day phases, providing prompts for roles with night actions and facilitating a voting process during the day.

    Thematic UI/UX: A carefully designed interface with custom fonts, a vintage color palette, and narrative storytelling to enhance immersion.

    Integrated Rulebook: An easily accessible in-game modal explains the objectives and abilities for each role.

    Secure Backend: Firestore Security Rules are used to ensure that only authenticated players who are part of a specific game can make changes to that game's state.

Technology Stack

    Frontend: HTML5, Tailwind CSS for styling, and modern JavaScript (ESM) for client-side logic.

    Backend: Google Firebase

        Firestore: Used as a real-time NoSQL database to store and sync all game and player data.

        Firebase Authentication: Used for anonymous user authentication to provide a unique and stable identity for each player session.

License

This project is licensed under the MIT License.
