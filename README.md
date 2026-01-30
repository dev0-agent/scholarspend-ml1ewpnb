# ScholarSpend

> Smart, privacy-first budget tracking for students.

ScholarSpend is a lightweight, offline-first expense tracker designed to help students manage their finances without the bloat. It runs entirely in your browser using a local database, ensuring your financial data stays private.

## Tech Stack

*   **Framework:** React + Vite
*   **Styling:** Tailwind CSS
*   **Database:** Dexie.js (IndexedDB wrapper)
*   **Visualization:** Recharts
*   **Icons:** Lucide React

## Features

*   **Local Persistence:** Data is saved to your browser's IndexedDB. No servers, no accounts.
*   **Visual Dashboard:** See exactly where your money goes with category breakdowns.
*   **Quick Logging:** Add expenses in seconds.
*   **Edit/Delete:** Full control over your transaction history.
*   **Responsive:** Works great on mobile and desktop.

## Getting Started

1.  **Clone the repository**
    ```bash
    git clone <repository-url>
    cd scholar-spend
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Start the development server**
    ```bash
    npm run dev
    ```

4.  Open `http://localhost:5173` in your browser.

## Project Structure

*   `/src/components` - Reusable UI components
*   `/src/db` - Database configuration and schema (Dexie)
*   `/src/hooks` - Custom React hooks
*   `/src/pages` - Main application views

## Documentation

*   [Task List](./TASKLIST.md) - Progress tracking
*   [Learnings](./LEARNINGS.md) - Dev log and architectural decisions
*   [Rules](./.dev0/RULES.md) - Coding standards