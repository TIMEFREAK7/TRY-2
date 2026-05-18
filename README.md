# Aditya Abhyankar - Professional Portfolio v3 (PepsiCo Theme)

A modern, interactive 5-page portfolio website with PepsiCo brand colors, dark mode, pop-up modals, Chart.js dashboards, and wide experience cards.

## Color Scheme – PepsiCo Brand

| Element | Color | Hex |
|---------|-------|-----|
| Primary (Buttons, Accents) | PepsiCo Blue | `#004B93` |
| Secondary (Gradients, Dark) | Dark Blue | `#00205B` |
| Highlight/Alert | PepsiCo Red | `#E31837` |
| Soft Backgrounds | Light Blue | `#E6F0FA` |
| Glow Effects | Blue Glow | `rgba(0, 75, 147, 0.15)` |
| Page Background | Very Light Gray | `#F5F7FA` |

## What's Included

- **PepsiCo Brand Colors** – Professional blue palette throughout
- **Wide Experience Cards** – 1100px timeline, 260px images, 2.5rem padding
- **Dark Mode Toggle** – Moon/sun icon, persists via localStorage
- **Click-to-Expand Modals** – Every card opens detailed popup (ESC to close)
- **Chart.js Graphs** – Bar, line, doughnut charts with PepsiCo colors
- **Contact Dropdown** – Standard recruiter contact reasons

## Pages

1. **Home** – Hero, prominent competencies with modals, achievements, education
2. **Experience** – Wide timeline cards (1100px) with photos, click for full details
3. **Projects** – Dashboards with SVG rings + Chart.js graphs + detail modals
4. **Competencies** – Animated skill bars, languages, certifications
5. **Contact** – Web3Forms with dropdown, contact cards, availability status

## Deployment

### GitHub + Vercel (No Terminal Needed)

1. Create a new repository on GitHub
2. Upload all files from this folder (drag & drop)
3. Go to vercel.com → Sign in with GitHub
4. Click "Add New Project" → Import your repository
5. Vercel auto-detects static site and deploys in ~30 seconds

## File Structure

```
portfolio/
├── index.html              # Home page
├── experience.html         # Work experience timeline
├── projects.html           # Project dashboards with charts
├── skills.html            # Core competencies
├── contact.html           # Contact form with dropdown
├── Aditya_Abhyankar_CV.pdf # Your CV
├── css/
│   └── style.css          # PepsiCo theme + animations
├── js/
│   └── main.js            # Interactions + Chart.js + dark mode
├── images/                # Add your photos here
└── README.md              # This file
```

## Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript (no frameworks)
- Chart.js 4.4.1 (charts and graphs)
- Font Awesome 6 (icons)
- Google Fonts (Inter)
- Web3Forms API (contact form)

## Customization

### Replace Images
- **Profile Photo**: `index.html` – change the `ui-avatars.com` URL to your image path
- **Experience Photos**: `experience.html` – change the Unsplash URLs

### Update Contact
- Email: `Aditya.abhyankar22@gmail.com` (already set)
- Web3Forms key: `e556db48-9042-4daa-9ee9-b294963e883f` (already set)

### Change Colors
All colors are CSS variables at the top of `css/style.css`:
```css
--accent-primary: #004B93;
--accent-secondary: #00205B;
```

---

Built with precision by Aditya Abhyankar | 2026
