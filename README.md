# Personal Budget Tracker - Visual Identity (Week 3)

## Overview
This project is a styled Personal Budget Tracker built using semantic HTML5 and modern CSS3. The goal of this phase was to transform a plain HTML structure into a clean, user-friendly, and visually cohesive financial tracking interface without altering the core HTML structure.

## Design Decisions & Features

### 1. Intentional Color Palette
A professional, finance-inspired color scheme was implemented using CSS custom properties (`:root`):
- **Primary Color (`#1e3a8a` - Deep Navy):** Used for main headings, section titles, and table headers to establish trust and visual hierarchy.
- **Accent Color (`#10b981` - Emerald Green):** Applied to primary action buttons to draw user attention and signify financial growth/action.
- **Neutral Backgrounds (`#f1f5f9` & `#ffffff`):** A soft slate background contrasts with crisp white content cards to reduce eye strain.

### 2. Custom Typography
Google Fonts were integrated to establish clear typographic hierarchy:
- **Headings (`Poppins`):** Bold, geometric sans-serif font used for titles and table headers.
- **Body & UI Elements (`Inter`):** Clean, highly legible font applied to form labels, inputs, buttons, and table data.

### 3. Form & Table Styling
- **Form:** Inputs and dropdowns include generous padding, subtle borders, rounded corners (`8px`), and interactive `:focus` states for accessibility.
- **Table:** Features a high-contrast header, structured cell padding, subtle row dividers, alternating row shading (`:nth-child(even)`), and hover highlights for easy scanning.

### 4. CSS Box Model Layout
The page is organized into three distinct visual cards (**Header**, **Add Expense Form**, and **Expense Table**) using consistent `margin`, `padding`, `border`, and `border-radius` properties.

## Project Structure
- `index.html` – Semantic HTML structure for the header, expense form, and expense table.
- `style.css` – Complete stylesheet containing typography, color variables, box model layout, and responsive rules.
- `README.md` – Documentation explaining the project architecture and design choices.