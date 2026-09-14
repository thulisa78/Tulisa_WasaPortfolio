# Tulisa Wasa — Portfolio

A modern, dark-themed front-end developer portfolio built with React.

## Features
- Animated fluid canvas hero background
- Real photo with green/cyan glow effect blended to the colour theme
- Animated skill bars with IntersectionObserver
- Full CV data: 4 work roles, education, certifications
- Downloadable PDF CV (embedded in-app)
- Contact form
- Fully responsive (mobile-friendly)

## Project Structure
```
tulisa-portfolio/
├── public/
│   ├── index.html
│   └── Tulisa_Wasa_CV.pdf
├── src/
│   ├── index.js
│   └── App.jsx          ← entire portfolio (all-in-one component)
├── package.json
└── README.md
```

## Getting Started

### Prerequisites
- Node.js 16+ installed ([nodejs.org](https://nodejs.org))

### Install & Run
```bash
# 1. Enter the folder
cd tulisa-portfolio

# 2. Install dependencies
npm install

# 3. Start development server
npm start
```
The app opens at **http://localhost:3000**

### Build for Production
```bash
npm run build
```
Output goes to the `build/` folder — deploy that to Vercel, Netlify, or any static host.

## Deploy to Vercel (Recommended)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import repo
3. Framework: **Create React App** (auto-detected)
4. Click Deploy — done ✅

## Customisation
All content lives in `src/App.jsx`:
- `PROJECTS` array — add/edit projects
- `STACK` array — update skill percentages
- `EXPERIENCE` array — update work history
- `EDUCATION` / `CERTIFICATIONS` arrays
- `PHOTO` & `PDF_DATA` constants — the photo and CV are base64-embedded

## Tech Stack
React 18 · CSS-in-JS (style tag) · HTML5 Canvas · IntersectionObserver API · Google Fonts (Share Tech Mono + Inter)
