# TechVerse — Hardware Advisor (Static Website) [file:9]

TechVerse is a multi-page static website that helps users explore laptops, PC builds, and brand options with a clean UI. [file:9][file:3]

## Features [file:9]
- Brand pages (HP, Dell, ASUS, Lenovo, Apple) with outbound official links (where provided). [file:9][file:8]
- PC Builds page with sample build tiers and estimated prices (Gaming / Workstation / Office-Student). [file:5]
- “AI PC Advisor” UI (HTML/CSS demo) to select primary use + budget. [file:10]
- Login page UI demo (HTML/CSS only). [file:4]

## Tech Stack
- HTML5 [file:9]
- CSS3 [file:3]

## Project Structure
- `index.html` — Home page + navigation [file:9]
- `laptops.html` — Laptops section (page) [file:12]
- `pcs.html` — PC builds / recommendations [file:5]
- `ai.html` — AI Advisor UI demo [file:10]
- `login.html` — Login UI demo [file:4]
- `contact.html` — Contact page [file:6]
- `style.css` — Global styling [file:3]
- Brand pages: `hp.html`, `dell.html`, `asus.html`, `lenvo.html`, `apple.html` [file:9]

## How to Run Locally
1. Download/clone the repository.
2. Open `index.html` in your browser. [file:9]

## Notes / Known Issue
- There is a filename/link mismatch: `index.html` links to `lenvo.html`, while `pcs.html` links to `lenovo.html`. Rename one and update links to match. [file:9][file:5]

## Future Improvements
- Make the AI Advisor interactive using JavaScript (real recommendations). [file:10]
- Add responsiveness (mobile layout) and accessibility improvements. [file:3]

## License
MIT (recommended for student projects).
