 Budget Tracker

A simple personal budget and expense tracker built with HTML and CSS.

 What I built

- An expense table showing name, amount, category, and date for five sample entries
- An "Add Expense" form with a dropdown for category, wrapped in a proper `<form>` element
- A logo image next to the main heading, inside a `<header>` card
- An embedded YouTube video with a budgeting tip
- A collapsible "How to use this tracker" section
- Styled table with alternating row colors and hover effects
- Advanced CSS selectors:
  - Descendant selector — styles inputs/select inside `.add-expense-section`
  - Direct child selector — targets `tr` elements that are direct children of `tbody`
  - `:not()` — keeps the Amount column styled differently from the rest
  - `:focus` — highlights form fields when active

 Week 3: Visual Design

This week's focus was styling only — no new HTML structure or functionality was added
except a small `<header>` wrapper around the main heading and intro text, so it could
be styled as its own card.

- Color palette: deep teal (`#1f3a3d`) for headings and the table header, warm
  off-white (`#f4f1ea`) for the page background, white for cards, and warm orange
  (`#e8873d`) for buttons, accents, and focus states.
- Typography: Poppins for headings, buttons, and labels; Inter for body text,
  table content, and form fields — loaded from Google Fonts via `@import` in `style.css`.
- Table and form styling: padded cells, a colored table header row, alternating
  row stripes, a hover highlight, and consistently styled rounded inputs and buttons.
- CSS Box Model: the page heading, the Add Expense form, and the expense table
  each appear as a separate rounded "card" using margin, padding, borders, and
  border-radius, so the page reads as clearly organized sections.

 Notes

The "Add Expense" button doesn't save data yet — that functionality will be added in Week 6 with JavaScript.