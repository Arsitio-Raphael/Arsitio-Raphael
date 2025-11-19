# Qualification Portfolio — React + Framer Motion + React Bits

Live demo (after you deploy):
https://Arsitio-Raphael.github.io/qualification-portfolio

Overview
--------
This is a multi-section academic qualification portfolio built with:
- React (Create React App)
- Framer Motion (page transitions + scroll-based animations)
- React Bits (pre-styled UI components)
- React Router v6 (single page app navigation)
- Responsive layout, mobile friendly
- GitHub Pages ready (gh-pages)

This scaffold provides pages/sections required for Phase 1 of a qualification portfolio:
- Home / Hero (parallax + animated text)
- About Me
- Life Vision / Mission
- Educational Background
- Strengths & Weaknesses (Big Five + Learning Style Inventory reflections)
- Values / Life Philosophy
- Gallery / Future Works
- Contact Page

It includes placeholder content you should replace with your own narratives, images, and reflections.

Repository & deployment
-----------------------
This project is prepared for deployment to GitHub Pages. The package.json `homepage` is set to:
https://Arsitio-Raphael.github.io/qualification-portfolio

To deploy:
1. Create a GitHub repo (owner: Arsitio-Raphael recommended) named `qualification-portfolio`.
2. Push this project to that repo.
3. Configure a GitHub Pages deploy by running:
   - npm install
   - npm run build
   - npm run deploy
(see scripts in package.json)

Files & structure
-----------------
- public/
  - index.html
- src/
  - index.js
  - App.jsx
  - styles.css
  - components/
    - Layout.jsx (responsive nav + footer)
    - ParallaxHero.jsx
    - AnimatedCard.jsx
  - pages/
    - Home.jsx
    - About.jsx
    - Vision.jsx
    - Education.jsx
    - Strengths.jsx
    - Values.jsx
    - Gallery.jsx
    - Contact.jsx

Design & animation notes
------------------------
- Page transitions are implemented with Framer Motion AnimatePresence and motion elements in App.jsx.
- The Hero uses viewport scroll for a parallax effect.
- Individual sections use simple scroll-triggered motion effects (fade / slide).
- React Bits components are used for consistent UI (swap with your preferred component primitives if needed).

Placeholder summaries (replace with your real content)
-----------------------------------------------------
1) Big Five summary (sample placeholder)
- Openness to Experience: 3.70 (moderate-high) — curious, enjoys new ideas, creative tendencies.
- Conscientiousness: 3.11 (moderate) — somewhat organized and responsible; room for growth in planning.
- Extraversion: 4.13 (high) — sociable, energetic in group contexts.
- Agreeableness: 3.89 (moderate-high) — cooperative, empathetic, prefers harmony.
- Neuroticism/Negative Emotionality: 2.13 (low) — generally calm and resilient.

Reflection (instructor-required)
- What I learned from this result: My Big Five profile suggests I learn well in collaborative and creative contexts. Low neuroticism helps manage stress during coursework, while moderate conscientiousness indicates I can improve structure and time management. I will use these insights to organize study schedules, set weekly goals, and seek peer critique to enhance accountability.

2) Learning Style Inventory — Visual preference (sample placeholder)
- Visual learners learn best through images, diagrams, charts, and spatial organization.
- Characteristics:
  - Strong visualization skills and ability to recall images.
  - Prefer notes with diagrams, color-coding, and spatial cues.
  - Benefit from videos, slides, maps, and flashcards.

Learning strategies I will use:
- Create colored mind maps and annotated diagrams for key topics.
- Turn reading notes into flowcharts and use short screencast summaries.
- Use a two-column note layout: concepts on left, visual examples/diagrams on right.

Reflection (instructor-required)
- Having a visual preference influenced how I approach projects and revision. I will intentionally create visuals before writing final reports and use screenshots or sketched workflows to explain technical concepts in my portfolio.

3) Instructor-required reflection sections (placeholders)
- "How these results helped me understand myself": The combination of my Big Five and learning style explains why I enjoy project-based, collaborative tasks and prefer explaining ideas visually. I will pick project deliverables with prototype or visual artifacts to demonstrate competency.
- "Action plan": Build a weekly plan template, set milestones for the portfolio project, adopt a color-coded study system, and ask a peer or instructor for accountability checks twice per month.
- "Evidence to include in portfolio": Screenshots of study notes (mind maps), a short reflective video (1–2 mins), project thumbnails with a one-paragraph explanation connecting them to my Big Five strengths and learning style.

Getting started (development)
-----------------------------
1. Clone the repo
   git clone https://github.com/Arsitio-Raphael/qualification-portfolio.git
2. Install
   npm install
3. Run locally
   npm start
4. Build
   npm run build
5. Deploy to GitHub Pages (first time)
   npm run deploy

Notes and next steps
--------------------
- Replace placeholder text & images in src/pages/* with your own content.
- Add real photos to /public/assets and update the Gallery.jsx image sources.
- If React Bits API differs from your installed package, replace imported components with your project's UI primitives (Box, Button, Card, etc.).
- Consider adding analytics, accessibility checks, and more rigorous SEO meta tags before final submission.

License
-------
MIT

Contact
-------
If you need help adapting this scaffold to your content or deployment, send me a message in the repo issues.