# Project: Mohammed Ameen Portfolio

This project is a personal portfolio website for **Mohammed Ameen Naimuddin**, an ML Engineer based in Hyderabad, India. It is a high-performance, single-page application (SPA) style portfolio with a "dark/cyberpunk" aesthetic.

## Project Overview

- **Owner:** Mohammed Ameen Naimuddin
- **Role:** ML Engineer / AI Researcher
- **Location:** Hyderabad, India
- **Tech Stack:** 
  - **Frontend:** Vanilla HTML5, CSS3 (Modern features like Grid, Flexbox, Custom Properties), Vanilla JavaScript.
  - **Fonts:** Rajdhani, Poppins, Share Tech Mono (Google Fonts).
  - **Features:** Custom particle canvas background, interactive cursor, typing effects, scroll-triggered animations (Intersection Observer), and responsive design.

## Key Files

- `ameen_portfolio_final (1).html`: The main entry point. Contains all HTML, inline CSS, and JavaScript for the portfolio.
- `Ameen_ML_Engineer.pdf`: The professional resume/CV of Mohammed Ameen.
- `my pic.png`: Profile image used in the portfolio.
- `refernce pic.webp`: Reference image/asset used for design or content.
- `GEMINI.md`: Project-level instructions and context (this file).

## Development and Usage

### Viewing the Portfolio
Simply open `ameen_portfolio_final (1).html` in any modern web browser.

### Updating Content
- **Bio/Text:** Locate the relevant sections in the HTML (e.g., `.hero-desc`, `.about-text`).
- **Skills:** Update the `data-w` attributes in the `.skill-bar-fill` elements to change percentage levels.
- **Projects/Experience:** Add or modify items within the `.experience-grid` and `.projects-grid` sections.
- **Contact Info:** Update the `href` and text in the `.contact-links` section.

### Aesthetic Conventions
- **Theme:** Dark/Cyberpunk (`#060608` background with `#c0392b` red accents).
- **Interactivity:** Maintain the custom cursor and particle effects as they are core to the visual identity.
- **Performance:** Keep the logic within the single file unless the project grows significantly, as it currently provides a zero-dependency, fast-loading experience.

## TODOs / Future Enhancements
- [ ] Refactor inline CSS and JS into separate files if the project complexity increases.
- [ ] Add a formal `projects/` directory for hosting source code of highlighted ML projects.
- [ ] Implement a CI/CD pipeline for automated deployment (e.g., GitHub Pages).
