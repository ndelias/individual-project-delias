# Misunderstood — Debunking Animal Myths

A web project that reframes the world's "most hated" animals through science-backed facts, transforming fear and stigma into understanding and appreciation.

## 🎯 Project Overview

**Working Title:** Misunderstood — Debunking Animal Myths

This project challenges common misconceptions about animals that are often feared or misunderstood. Instead of perpetuating myths, we present ecological benefits, scientific facts, and clear myth-busting information through an accessible, educational web experience.

### Featured Animals
- Sharks
- Bats  
- Spiders
- Vultures
- Hyenas
- Wolves
- Opossums
- Snakes
- Rats
- Coyotes

## 🎯 Goals & Audience

**Target Audience:** Learners age 12+ (students, parents, curious readers)

**Primary Objectives:**
1. **Debunk persistent myths** about commonly feared animals
2. **Teach credible interpretation** of wildlife facts and sources
3. **Model responsible source attribution** and fact-checking

## 🏗️ Technical Approach

**Philosophy:** Small, fast, and accessible
- **Semantic HTML5** for proper document structure
- **Responsive CSS** using Grid and Flexbox
- **Lightweight vanilla JavaScript** with local JSON data
- **Accessibility-first** design with ARIA support
- **Performance-optimized** for quick loading

## 📱 Site Structure

### Core Pages
1. **Home** - Introduction and featured content
2. **Browse** - Filter animals by myth category:
   - Dangerous
   - Dirty/Diseased  
   - Useless/Nuisance
3. **Species Detail** - Individual animal profiles with myth-busting accordions
4. **Quiz** - 5-question "Myth or Fact?" interactive quiz
5. **About/Sources** - Project information and source attribution
6. **404** - Custom error page for invalid routes

### Key Features
- **Myth→Fact Accordions** - Interactive myth-busting with proper ARIA support
- **Category Filtering** - Browse by myth type with deep-linking support
- **Persistent Quiz Scoring** - Track best performance with localStorage
- **Responsive Design** - Mobile-first approach with progressive enhancement
- **Accessibility** - Full keyboard navigation and screen reader support

## 📅 Development Timeline

**Duration:** 1 Week (October 25–31, 2025)

### Day 1 — Plan & Scaffold
- Finalize scope (10 species, 3 myth categories)
- Create GitHub repository and project structure
- Set up GitHub Pages deployment
- Draft data schemas for `animals.json` and `quiz.json`

### Day 2 — Wireframes → HTML Shells
- Translate wireframes to mobile-first HTML
- Build semantic landmarks (header, nav, footer)
- Create page templates: `index.html`, `browse.html`, `detail.html`, `quiz.html`, `about.html`, `404.html`

### Day 3 — Global Styles & Components
- Implement design tokens, type scale, and spacing system
- Build responsive card grid and category segmented controls
- Create reusable components (chips, cards, badges)
- Establish visual hierarchy and typography

### Day 4 — Data + Browse Logic
- Populate `animals.json` with 10 species data
- Add placeholder images and source citations
- Build browse functionality with category filtering
- Implement deep-linking via URL parameters (`?cat=`)

### Day 5 — Detail Page & Myth Accordion
- Create species detail page with dynamic content loading
- Build Myth→Fact accordion with proper ARIA attributes
- Implement quick facts display and impact badges
- Add source attribution and citation system

### Day 6 — Quiz & Polish
- Create `quiz.json` with 5 myth/fact statements
- Build interactive quiz flow (answer → feedback → progress)
- Implement localStorage for persistent best score tracking
- Add 404 redirect handling and favicon

### Day 7 — A11y, Performance & Submit
- Conduct keyboard accessibility audit (tab order, focus states)
- Perform color contrast verification
- Optimize images and implement lazy loading
- Minify assets and target Lighthouse score ≥90/95
- Update documentation and deploy to GitHub Pages

## 🛠️ Technical Stack

- **HTML5** - Semantic markup with proper landmarks
- **CSS3** - Grid, Flexbox, custom properties, responsive design
- **Vanilla JavaScript** - ES6+ features, localStorage, fetch API
- **JSON** - Local data storage for animals and quiz content
- **GitHub Pages** - Static site hosting and deployment

## 🎨 Design Principles

- **Mobile-First** - Responsive design starting from smallest screens
- **Accessibility** - WCAG 2.1 AA compliance with proper ARIA support
- **Performance** - Fast loading with optimized assets and lazy loading
- **Usability** - Intuitive navigation and clear information hierarchy
- **Educational** - Clear myth-busting with credible source attribution

## 📊 Success Metrics

- **Performance:** Lighthouse score ≥90/95
- **Accessibility:** Full keyboard navigation and screen reader compatibility
- **Usability:** Clear myth-busting with engaging interactive elements
- **Educational Impact:** Effective myth debunking with credible sources

## 🚀 Getting Started

1. Clone the repository
2. Open `index.html` in a modern web browser
3. Explore the different sections and interactive features
4. Take the quiz to test your knowledge!

## 📝 License

This project is created for educational purposes as part of an individual web development project.

---

*Transforming fear into understanding, one myth at a time.*
