# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Initialize Project and Tailwind CSS**
  Initialize a new React + Vite project. Install and configure Tailwind CSS. Set up the basic folder structure (components, db, hooks, pages). Verify the build pipeline works.

- [ ] ⏳ **Setup Dexie.js Database Schema**
  Install `dexie`. Create a `db.ts` file to define the database schema. We need a table for `expenses` with fields: `id` (auto-increment), `title` (string), `amount` (number), `category` (string), `date` (date object/string). Export the db instance.

- [ ] ⏳ **Create Application Layout Shell**
  Create a responsive Layout component containing a Header (with app title) and a Main content area. Implement a simple footer. Ensure the layout works on mobile and desktop.

## Phase 2

- [ ] ⏳ **Implement Add Expense Form**
  Create a form component to add a new expense. Inputs: Title, Amount, Date, Category (select dropdown). On submit, validate inputs and save to Dexie DB. Clear form on success.

- [ ] ⏳ **Implement Expense List View**
  Create a component to list recent expenses. Use `useLiveQuery` from Dexie-React (or standard useEffect) to fetch data. Display date, title, category, and amount formatted as currency. Sort by date descending.

- [ ] ⏳ **Add Delete and Edit Functionality**
  Add a delete button to each list item that removes the entry from the DB. Add an edit mode (or modal) to update existing entries. Ensure the UI updates immediately after these actions.

## Phase 3

- [ ] ⏳ **Implement Dashboard Statistics Logic**
  Create utility functions to calculate: Total Balance (or Total Spent), Spending by Category, and Spending this Month vs Last Month. Prepare this data for the UI.

- [ ] ⏳ **Visualize Data with Charts**
  Install `recharts`. Create a Pie Chart component to show spending distribution by category. Integrate the stats logic to feed data into the chart. Place this at the top of the dashboard.

## Phase 4

- [ ] ⏳ **UI Polish and Empty States**
  Add empty states (e.g., 'No expenses yet, add one!') when the list is empty. Improve styling of the cards and form elements. Add simple transitions/animations for adding/deleting items.

## Phase 5

- [ ] ⏳ **Add Demo Data Capability**
  Create a 'Load Demo Data' button in the settings or footer that populates the DB with realistic sample data for testing purposes. This helps users see the value of the charts immediately.

---

_Last updated by dev0 automation_
