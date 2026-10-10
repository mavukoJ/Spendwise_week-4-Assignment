
# SpendWise Dashboard Shell

## Project Overview

SpendWise is a responsive personal finance dashboard designed to help users view their budgets, expenses, savings, and recent transactions in one place.

This project is the Week 4 layout foundation for my Personal Budget & Expense Tracker capstone project. It uses realistic sample financial information and does not yet include interactive financial functionality.

## Project Files

- `index.html` — Defines the dashboard structure, sidebar navigation, header, financial summaries, six expense category cards, budget panel, and recent transactions.
- `style.css` — Defines the color theme, typography, CSS Grid and Flexbox layouts, responsive behavior, progress bars, card interactions, and optional dark theme.
- `README.md` — Documents the project, its features, and the technologies used.

## Features

1. Sidebar navigation menu.
2. Dashboard header with a monthly overview.
3. Three financial summary cards.
4. Six category cards: Food & Groceries, Transport, Rent & Housing, Entertainment, Savings, and Utilities.
5. Monthly budget and recent transaction panels.
6. CSS Grid for the overall dashboard and card layouts.
7. Flexbox for the header, navigation, sidebar, and card contents.
8. CSS custom properties defined on `:root` for consistent colors.
9. Responsive single-column layout below 768px.
10. Hover and keyboard-focus effects using CSS transitions of 200ms.
11. Optional dark theme using `prefers-color-scheme: dark`.
12. Semantic HTML and keyboard-accessible category cards.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS custom properties
- Media queries
- CSS transitions

## How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a web browser.
4. Resize the browser window or use DevTools Device Toolbar to test responsiveness.

## Responsive Testing

The dashboard uses a CSS media query at `max-width: 767px`. Below 768px, the sidebar and main content become a single-column page, and the summary cards, category cards, and lower panels stack vertically.

## Sample Data Notice

All displayed financial amounts and transactions are fictional sample data for demonstrating the dashboard layout. No actual financial account is connected.

## Future Improvements

- Add expense entry forms.
- Calculate balances and expenses dynamically.
- Add category budgets and spending summaries.
- Save transactions using browser storage or a database.
- Add interactive charts and reports.

## Author

Created as part of my Personal Budget & Expense Tracker learning project.
