# Assignment-2: Personal Portfolio (with Interactive Features)

## Project Description
Super Shahad Portfolio is a retro, Mario-inspired personal portfolio website.  
It showcases projects, skills, and contact information in a fun 8-bit style with interactive and dynamic features.

---

## Features
- **Retro Design** — pixel font, Mario-style blocks, and themed assets.
- **Interactive Skill Blocks** — reveal skills on click with coin sound and glow animation.
- **Coin Sound Effect** — plays when interacting with the page.
- **Theme Toggle** — light/dark theme with persistence using LocalStorage.
- **Projects Gallery**
  - Live search, filter by tag, and sort (by date/title).
  - Dynamic rendering + “No projects found” empty state.
- **Contact Form** — retro-style design with inline error/success feedback.
- **Animations** — smooth fade-in on scroll and hover transitions.

---

## Setup Instructions (How to Run Locally)

### Option A — Quick Open
1. Download or clone this repository.  
2. Open `index.html` directly in your browser.

### Option B — Live Server (recommended)
1. Open the folder in **VS Code**.  
2. Install the **Live Server** extension (if not already).  
3. Right-click `index.html` → **Open with Live Server**.

---

## Folder Structure
assignment-2/
├── README.md
├── index.html
├── css/
│ └── styles.css
├── js/
│ └── script.js
├── assets/
│ ├── images/
│ │ ├── mario.jpeg
│ │ ├── star.png
│ │ ├── block_svg.jpeg
│ │ ├── to-doList.png
│ │ └── timer.png
│ └── sounds/
│ └── mario_coin_sound.mp3
├── docs/
│ ├── ai-usage-report.md
│ └── technical-documentation.md
└── .gitignore



## How It Meets Assignment-2 Requirements
- **Dynamic Content**: personalized greeting, dynamic projects (search/filter/sort), interactive skill blocks.
- **Data Handling**: LocalStorage (theme + username + revealed skills).
- **Animations & Transitions**: fade-in on scroll, block glow, button hover.
- **Error Handling & User Feedback**:
  - Form inline errors + success messages.
  - Projects empty state (e.g., “No projects found”).
- **AI Enhancement**:
  - Used AI for drafting helper tips, refining copy, and code suggestions (documented below and in `docs/ai-usage-report.md`).

## AI Usage Summary
- Design Inspiration: Generating ideas for retro/pixel-style UI.
- Code Assistance.
- Interactive Features: Adding coin sound effects, hover animations, and skill reveal interactions.
- Documentation Support: Helping draft this README and setup instructions.
