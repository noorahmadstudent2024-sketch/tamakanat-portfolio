# Tamakanat Khalid Portfolio - 2026 Premium Dark Theme

## Project Overview

A modern, futuristic portfolio website built with pure HTML, CSS, and JavaScript. Features a premium dark theme with glassmorphism design, neon accents, and smooth animations.

**Live URL:** https://[username].github.io/tamkanat-portflio/

---

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern features (Grid, Flexbox, CSS Variables, Animations)
- **Vanilla JavaScript** - No frameworks/libraries
- **Google Fonts** - Inter & Space Grotesk

---

## Design System

### Color Palette

```css
/* Dark Theme Colors */
--bg-primary: #0a0a0f;      /* Main background */
--bg-secondary: #12121a;    /* Secondary background */
--bg-tertiary: #1a1a25;     /* Tertiary background */

/* Gradient Colors */
--gradient-start: #667eea;  /* Blue */
--gradient-mid: #764ba2;    /* Purple */
--gradient-end: #f093fb;    /* Pink */

/* Neon Accents */
--neon-blue: #00d4ff;
--neon-purple: #b24bf3;
--neon-pink: #ff006e;
--neon-cyan: #00ffff;

/* Text Colors */
--text-primary: #ffffff;
--text-secondary: rgba(255, 255, 255, 0.7);
--text-muted: rgba(255, 255, 255, 0.5);
```

### Typography

- **Headings:** Space Grotesk (400-700 weight)
- **Body:** Inter (300-900 weight)
- **Base size:** 16px
- **Line height:** 1.6

### Spacing & Radius

```css
--radius-sm: 12px;
--radius-md: 16px;
--radius-lg: 24px;
--radius-xl: 32px;
```

### Transitions

```css
--transition-fast: 0.2s cubic-bezier(0.4, 0, 0.2, 1);
--transition-smooth: 0.4s cubic-bezier(0.4, 0, 0.2, 1);
--transition-slow: 0.6s cubic-bezier(0.4, 0, 0.2, 1);
```

---

## Features

### 1. Glassmorphism UI
- Semi-transparent backgrounds (`rgba(255, 255, 255, 0.03)`)
- Backdrop blur effect (`backdrop-filter: blur(20px)`)
- Subtle borders (`rgba(255, 255, 255, 0.08)`)
- Soft shadows

### 2. Custom Cursor
- Main cursor ring with neon border
- Center dot with glow
- Large glow orb following mouse (smooth lag)
- Hover state changes on interactive elements
- Hidden on touch devices

### 3. Particles Background
- Canvas-based particle system
- 60 floating particles
- Connecting lines between nearby particles
- Responsive to window resize

### 4. Gradient Orbs
- 3 large blurred gradient orbs
- Parallax effect on mouse movement
- Float animation

### 5. Navigation
- Floating pill-style navbar
- Glassmorphism effect
- Active link highlighting on scroll
- Mobile hamburger menu with full-screen overlay
- Shrinks on scroll

### 6. Scroll Progress Indicator
- Fixed at top of page
- Gradient color (blue → purple → pink)
- Neon glow effect

### 7. Animations
- Preloader with progress bar
- Scroll reveal (fade up)
- Typing effect for roles
- Counter animation for stats
- Card hover lift
- Button shine effect
- Profile ring rotation

### 8. Responsive Breakpoints

```css
@media (max-width: 1024px)  /* Tablet landscape */
@media (max-width: 768px)   /* Tablet portrait */
@media (max-width: 480px)   /* Mobile */
@media (max-width: 360px)   /* Small mobile */
```

---

## File Structure

```
tamkanat-portflio/
├── index.html          # Main HTML file (includes CSS & JS)
├── CLAUDE.md           # This documentation
├── img/
│   └── profile.png     # Profile image
└── README.md           # (optional)
```

---

## Sections

1. **Hero** - Profile image, name, typing effect, CTA buttons
2. **About** - Career objective, stats cards
3. **Education** - Timeline with glassmorphism cards
4. **Experience** - Work history card
5. **Skills** - 4-column grid of skill cards
6. **Hobbies** - 4-column grid with hover effects
7. **Contact** - Phone & email cards
8. **Footer** - Logo, social links, navigation

---

## Customization Guide

### Change Colors
Edit CSS variables in `:root` section at top of `<style>` tag.

### Change Profile Image
Replace `img/8b6fdbb9-0e60-4155-80a5-0bfca495db6e.png` with your image path.

### Update Content
Edit the HTML directly - all content is in `index.html`.

### Add New Sections
1. Create section HTML with `reveal` class for animations
2. Add navigation link
3. Style using existing `.glass-card` class

### Modify Animations
- Scroll reveal: Edit `.reveal` class and `revealObserver`
- Particles: Modify `Particle` class and `particleCount`
- Typing: Edit `phrases` array in JavaScript

---

## Performance Optimizations

- No external CSS/JS libraries
- Optimized animations with `requestAnimationFrame`
- Efficient particle system
- Lazy scroll reveal with IntersectionObserver
- Hardware-accelerated CSS transforms

---

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- Mobile browsers (iOS Safari, Chrome Android)

---

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select branch (main/master) and save
4. Site will be live at `https://[username].github.io/[repo-name]/`

---

## Credits

- **Design & Development:** Claude AI
- **Fonts:** Google Fonts (Inter, Space Grotesk)
- **Icons:** Custom SVG icons

---

## Version History

- **v2.0** (Feb 2026) - Complete redesign with 2026 Premium Dark Theme
- **v1.0** (Feb 2026) - Initial portfolio with navy/gold theme

---

## Contact

**Tamakanat Khalid**
- Email: tamkanatkhalid@gmail.com
- Phone: +92-302-2562021
- WhatsApp: [wa.me/923022562021](https://wa.me/923022562021)
