# Biomed Board

A shared task board for the biomed office.

- **Display monitor:** `index.html#display` – the big green card shows the task that's on now (or a big clock), with today's upcoming tasks in blue and completed ones in a grey panel. A full-screen alert flashes 5 minutes before each task until someone clicks **Got it**.
- **Add tasks:** `index.html#add` – add, edit and delete tasks from any computer or phone. The scheduled-task list is behind a PIN.

Tasks are stored in Firebase Realtime Database (project `foodfair-meat`, under `biomedBoard/tasks`) so every screen sees the same board.
Anyone with the link can add tasks, so don't put patient information in task names or notes.

## Links

- Add tasks: https://biomedboard.vercel.app/#add
- Display monitor: https://biomedboard.vercel.app/#display
