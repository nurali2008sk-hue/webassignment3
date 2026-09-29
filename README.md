# Assignment #3: Responsive Web Design
 
##  Project Overview
This project demonstrates responsive web design techniques using **CSS Media Queries** and the **Bootstrap 5 Grid system**. The webpage seamlessly adapts across Mobile (< 768px), Tablet (768px – 991px), and Desktop (≥ 992px) screens.

---

##  Features & Tasks Breakdown

### Part 1. Media Queries (Pure CSS)
* **Task 0: Responsive Typography** — Implemented fluid typography where font sizes dynamically adjust depending on the viewport width using pure CSS `@media` rules[cite: 2, 3].
* **Task 1: Responsive Layout** — Created a 3-box container using CSS Flexbox:
  * **Desktop:** All 3 boxes side-by-side[cite: 1, 3].
  * **Tablet:** 2 boxes in the first row, 1 box in the second row[cite: 2, 3].
  * **Mobile:** Stacked vertically in a single column[cite: 2, 3].

### Part 2. Bootstrap Grid System
* **Task 2: Bootstrap Responsive Columns** — Built a layout using Bootstrap's 12-column grid system (`col-12`, `col-md-6` / `col-md-12`, `col-lg-4`)[cite: 1, 3].
* **Task 3: Bootstrap Navigation Bar** — Added a responsive Bootstrap navbar with a brand title, navigation links, and a collapsible hamburger menu for smaller screens[cite: 1, 3].

### Part 3. Combined Project
* **Task 4: Responsive Portfolio Page** — Developed a portfolio layout combining Bootstrap Grid and custom Media Queries[cite: 1, 3]:
  * **Navbar & Hero Section:** Welcoming header with dynamic text scaling.
  * **Projects Grid:** Project cards with images, limited text descriptions, and interactive hover effects[cite: 1, 2].
  * **Sidebar:** Personal information and contact details[cite: 1, 3].
  * **Footer:** Clean footer styled across the bottom[cite: 1, 3].

---

## File Structure
```text
├── index.html   # Main HTML markup with Bootstrap 5 & semantic tags
└── style.css    # Custom styles, transitions, and media queries