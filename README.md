# Haven — Hotel Management System

A responsive hotel management dashboard built with React and Vite. This is a frontend demo project with sample data stored in React state.

## Features

- Dashboard with revenue, occupancy, booking and room statistics
- Reservations list with search and status filtering
- Add reservation form with guest, room, dates and amount
- Update reservation status (confirmed, pending, checked in, checked out)
- Room overview with availability and housekeeping states
- Guest directory
- Housekeeping task list
- Payment summary
- Responsive sidebar and layout for mobile screens

## Run locally

1. Install [Node.js](https://nodejs.org/) (LTS version recommended).
2. Download or clone this repository.
3. Open a terminal in the project folder.
4. Install dependencies:

   ```bash
   npm install
   ```

5. Start the development server:

   ```bash
   npm run dev
   ```

6. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Build for production

```bash
npm run build
```

The production website is generated in the `dist` folder.

## Publish on GitHub

1. Create a new repository on GitHub.
2. Upload the project files (the contents of this folder) or push them using Git.
3. To publish it with GitHub Pages, configure the repository's Pages settings to use GitHub Actions or a suitable Vite deployment workflow.

## Important note

This is a frontend-only demonstration. Reservations and status changes are held in browser memory and reset when the page is refreshed. It does not yet include a backend, database, authentication, real payment processing, or live room availability. Add a backend and database before using it for real hotel operations.
