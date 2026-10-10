# MindCare Cognitive Companion — Prototype

This prototype is based on the uploaded project documents and notebook.

## Implemented interactive features
- Caregiver dashboard and patient profile
- Caregiver memory-loss observation form
- Personalized Memory Vault with family-photo upload
- Photo Jigsaw Puzzle with 3x3 / 4x4 / 5x5 difficulty, moves and timer
- House-map upload and caregiver room marking (Washroom, Bedroom, Kitchen, Living Room, Dining Room, Main Door, etc.)
- Patient House Wayfinding challenge
- Daily care reminders
- Browser voice assistant for hydration/medicine intents
- LocalStorage offline persistence
- Adaptive difficulty/session feedback UI
- Caregiver alert/analytics UI
- React/Vite shell
- Node/Express/MongoDB API
- ML integration folder aligned to Isolation Forest notebook
- Uploaded dementia dataset preserved as data/dementia_dataset.csv

## Fastest way to see the prototype
Open `frontend/prototype.html` directly in Chrome/Edge. No Node or MongoDB is required for this interactive demo.

## Full-stack
Backend:
    cd backend
    npm install
    cp .env.example .env
    npm run dev

Frontend:
    cd frontend
    npm install
    npm run dev

Then open the Vite URL shown in the terminal.

## Demo flow
1. Patient Profile
2. Memory Loss Data -> record observations
3. Memory Vault -> upload family photo
4. Photo Jigsaw -> solve photo puzzle
5. House Maze -> upload house map and mark rooms
6. Start patient challenge -> find the requested room
7. Reminders -> mark care tasks
8. Voice Assistant -> speak hydration/medicine request
9. Dashboard -> review trends and alerts

## Clinical note
This is a software prototype for cognitive engagement and caregiver observation. It should not be treated as a diagnostic instrument.
