# 🍦 ScoopR – Artisan Ice Cream

A React + Vite project for the ScoopR artisan ice cream website.

## Project Structure

```
scoopr/
├── public/
│   └── index.html
├── src/
│   ├── main.jsx              # Entry point
│   ├── App.jsx               # Root component, routing & state
│   ├── index.css             # All global styles & design tokens
│   ├── data/
│   │   └── constants.js      # FLAVORS, SPECIALS, HERO_SLIDES, CATEGORIES
│   ├── hooks/
│   │   └── useScroll.js      # useScrolled, useScrollTop
│   ├── utils/
│   │   └── toast.jsx         # showToast helper + ToastContainer
│   ├── components/
│   │   ├── Navbar.jsx        # Top nav + mobile hamburger menu
│   │   ├── HeroSlider.jsx    # Auto-playing hero carousel
│   │   ├── ProductCard.jsx   # Ice cream product card + StarsRaw
│   │   ├── LoginModal.jsx    # Sign in / Sign up modal
│   │   └── Footer.jsx        # Site footer
│   └── pages/
│       ├── Home.jsx          # Landing page (hero + stats + featured + specials)
│       ├── Menu.jsx          # Full menu with search, filter & sort
│       ├── About.jsx         # About page
│       └── Contact.jsx       # Contact form + info cards
├── package.json
├── vite.config.js
└── .gitignore
```

## Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Start the dev server
```bash
npm run dev
```

### 3. Build for production
```bash
npm run build
```

### 4. Preview production build
```bash
npm run preview
```

## Tech Stack

- **React 18** – UI library
- **Vite 5** – Build tool & dev server
- **Google Fonts** – Fraunces (serif) + DM Sans (sans-serif)
- **Unsplash** – Placeholder images (swap with your own)
