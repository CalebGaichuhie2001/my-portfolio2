# Caleb Tech Portfolio

A simple static portfolio website showcasing services, projects, and basic auth-related pages. Built with plain HTML and CSS, with a few visual effects (animations, hover overlays, and background videos).

## Overview
- **Homepage**: Hero, services, projects, about, and contact sections with a background video.
- **Login**: Responsive login form with social icons (Font Awesome via CDN).
- **Signup**: Modern sign-up card over a full-screen looping video background.

## Tech Stack
- **HTML5**
- **CSS3**
- **Font Awesome** (CDN on `login.html`)

## Demo
Once GitHub Pages is enabled for this repo, your site will be available at:
- https://calebgaichuhie2001.github.io/my-portfolio2/

## File Structure
```
my-portfolio/
├─ homepage.html
├─ login.html
├─ signup2.html
├─ styles.css        # Homepage styles (navbar, hero, services, projects, about, contact)
├─ style.css         # Login page styles
├─ style5.css        # Signup page styles
├─ images/
│  ├─ caleb.jpg
│  ├─ paris.jpg
│  └─ pexels-photo-326503.webp
└─ videos/
   ├─ my-video.mp4
   └─ my-video2.mp4
```

## Features
- **Fixed navbar** with quick links to Home, About, Contact, Services
- **Hero section** with CTA
- **Services** cards with hover and slide-in animations
- **Projects grid** with image overlay and “View Project” interaction
- **About section** with image and CTA
- **Contact section** with embedded background video and form UI (no backend)
- **Login** page with social icons
- **Signup** page with glassmorphism card and gradient button hover effect

## Getting Started (Local)
1. Clone the repo:
   ```bash
   git clone https://github.com/CalebGaichuhie2001/my-portfolio2.git
   cd my-portfolio2
   ```
2. Open `homepage.html` directly in your browser (double‑click or drag into browser).

> Tip: If you run via a local server, all relative assets load the same (no special config required).

## Deployment (GitHub Pages)
You can host this static site using GitHub Pages:
1. Push to the `main` branch of the repo.
2. In GitHub: Settings → Pages → Build and deployment → Branch: `main` (root) → Save.
3. Your site will be available at the URL listed in the Demo section above.

## Screenshots
Add screenshots to visually showcase the pages. Suggested shots:
- `homepage` hero and services
- `projects` grid hover effect
- `about` section
- `contact` section with video background
- `login` page
- `signup` page

Example markdown once images are added to a `screenshots/` folder:
```md
![Homepage Hero](screenshots/home-hero.png)
![Projects Grid](screenshots/projects.png)
```

## Customization
- Replace images and videos in `images/` and `videos/` with your own media.
- Update copy in `homepage.html`, `login.html`, and `signup2.html`.
- Update buttons and links (e.g., project links, social links) to point to real destinations.
- Adjust styles in `styles.css`, `style.css`, and `style5.css` to match your brand.

## Known Notes / Improvements
- The navbar links now correctly reference `signup2.html`.
- Forms are front-end only; wire up to a backend or a service like Formspree/Netlify Forms for real submissions.
- Consider optimizing media (images/videos) for faster load times.

## License
No license specified. Add a license if you plan to share or reuse this work.

## Author
Caleb Tech 