# tanveer_payments  

A lightweight, HTML‑based portal that aggregates monthly payment reports for Tanveer. The repository stores the monthly payment documents (DOCX) and a single `index.html` page that provides quick navigation and preview links.

---  

## Overview  

`tanveer_payments` is a simple, static web interface that centralises all of Tanveer’s monthly payment statements. The site lists each month’s DOCX file, allowing users to download or view the reports directly from the browser. No backend or database is required—just open the HTML file and start navigating.

---  

## Features  

- **Monthly report index** – All payment statements are listed chronologically with clear month labels.  
- **One‑click download** – Click a link to download the corresponding `.docx` file.  
- **Responsive layout** – Basic CSS ensures the page looks good on desktop and mobile browsers.  
- **Zero‑dependency** – Pure HTML/CSS/JS; no server or external libraries needed.  

---  

## Tech Stack  

| Layer | Technology |
|-------|------------|
| Front‑end | HTML5, CSS3, vanilla JavaScript |
| Documents | Microsoft Word (`.docx`) |
| Hosting | Any static‑file server (GitHub Pages, Netlify, local file system) |

---  

## Installation  

1. **Clone the repository**  

   ```bash
   git clone https://github.com/your-username/tanveer_payments.git
   cd tanveer_payments
   ```

2. **Open the site**  

   - Double‑click `index.html` to launch it locally, **or**  
   - Serve the folder with any static file server (e.g., `python -m http.server`)  

   ```bash
   python -m http.server 8000
   # then open http://localhost:8000 in your browser
   ```

---  

## Usage  

1. Open `index.html` in a web browser.  
2. Browse the list of months; each entry displays the month name and year.  
3. Click the **Download** button next to a month to retrieve the corresponding `.docx` file.  

The page is self‑explanatory; no additional configuration is required.

---  

## License  

This project is licensed under the **MIT License**. See the `LICENSE` file for details.  

---  

### Quick Links  

- **Repository**: https://github.com/your-username/tanveer_payments  
- **Live Demo (GitHub Pages)**: https://your-username.github.io/tanveer_payments/  

---  

*If you wish to customize the page (e.g., add branding or additional months), simply edit `index.html` and the accompanying CSS.*