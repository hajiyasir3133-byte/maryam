# Maryam Sultani – Graphic Designer Portfolio

## Project Overview
- **Project Name**: Sabrina Portfolio
- **Type**: Premium single-page portfolio website
- **Core Functionality**: Showcase graphic design portfolio with high-end 3D visual effects and luxury aesthetic
- **Target Users**: Potential clients, creative agencies, brands seeking graphic design services

---

## UI/UX Specification

### Layout Structure

**Page Sections (Top to Bottom)**
1. Fixed Navbar (transparent → solid on scroll)
2. Hero Section (100vh)
3. About Section
4. Projects Section
5. Services Section
6. Testimonials Section
7. Contact Section
8. Footer

**Responsive Breakpoints**
- Mobile: < 576px
- Tablet: 576px - 991px
- Desktop: ≥ 992px

---

### Visual Design

**Color Palette**
- Primary: `#1a1a2e` (Deep Black)
- Secondary: `#16213e` (Dark Navy)
- Accent Blue: `#0f3460` (Elegant Blue)
- Accent Purple: `#7b2cbf` (Deep Purple)
- Highlight: `#9d4edd` (Bright Purple)
- Glow Blue: `#00d4ff` (Cyan Blue)
- Glow Purple: `#e040fb` (Magenta Purple)
- White: `#ffffff`
- Light Gray: `#f8f9fa`
- Text Muted: `#a0a0a0`

**Gradient Combinations**
- Hero Background: Linear gradient from #1a1a2e → #16213e → #0f3460
- Accent Gradient: linear-gradient(135deg, #7b2cbf, #9d4edd)
- Glow Gradient: radial-gradient(circle, rgba(0,212,255,0.15) 0%, transparent 70%)
- Card Gradient: linear-gradient(145deg, rgba(123,44,191,0.1), rgba(15,52,96,0.1))

**Typography**
- Logo Font: 'Playfair Display', serif (700 weight)
- Headings: 'Sora', sans-serif (600, 700 weights)
- Body: 'DM Sans', sans-serif (400, 500 weights)
- Font Sizes:
  - Logo: 2rem
  - H1: 4rem (desktop), 2.5rem (mobile)
  - H2: 3rem (desktop), 2rem (mobile)
  - H3: 1.75rem
  - Body: 1rem
  - Small: 0.875rem

**Spacing System**
- Section Padding: 100px 0 (desktop), 60px 0 (mobile)
- Container Max Width: 1320px
- Card Padding: 30px
- Element Gap: 2rem

**Visual Effects**
- Glassmorphism: backdrop-filter: blur(10px), semi-transparent backgrounds
- Box Shadows: 0 25px 50px rgba(0,0,0,0.3)
- Glow Shadows: 0 0 30px rgba(123,44,191,0.3)
- Border Radius: 20px (cards), 50px (buttons), 10px (inputs)

---

### Components

**Navbar**
- Height: 80px
- Background: transparent → rgba(26,26,46,0.95) on scroll
- Logo: "Sabrina" with gradient text effect (purple → blue)
- Nav Links: Home, About, Projects, Services, Testimonials, Contact
- Link Hover: Underline slide animation with glow
- Social Icons: Instagram, Google (with pulse glow on hover)
- Mobile: Hamburger icon → Offcanvas from right

**Hero Section**
- Layout: 2 columns (text left, image right)
- Headline: "Creative Graphic Designer"
- Subheadline: Brief intro text
- CTA Button: Gradient background, hover scale + glow
- 3D Elements: Floating geometric shapes, design tool icons
- Background: Animated gradient with floating particles

**About Section**
- Bio Card: Glassmorphism style
- Skills: Progress bars with animated fill
- Floating 3D shapes in background

**Projects Section**
- Grid: 3 columns (desktop), 2 (tablet), 1 (mobile)
- Cards: Image + overlay with title
- Hover: Zoom effect, gradient overlay reveal
- Categories: Logos, Posters, Branding, Social Media

**Services Section**
- 4 Service Cards with icons
- 3D tilt effect on hover
- Glowing border animation
- Services: Logo Design, Brand Identity, Print Design, Social Media Design

**Testimonials Section**
- Bootstrap Carousel
- Card style with quote icon
- Navigation dots with glow

**Contact Section**
- 2 Columns: Contact Info (left), Form (right)
- Info Items: Icon + text with glow
- Form Inputs: Floating labels, glowing border on focus
- Submit Button: Gradient with animation

**Footer**
- Gradient background (black → purple → blue)
- 3D wave or geometric decoration
- Social icons, copyright

---

## Functionality Specification

### Core Features
1. Smooth scroll navigation
2. Navbar background change on scroll
3. 3D floating background elements (CSS animations)
4. Parallax scrolling effect on hero
5. Project card hover zoom
6. Service card 3D tilt effect
7. Testimonial carousel auto-play
8. Form validation with visual feedback
9. Mobile offcanvas menu
10. Scroll-triggered entrance animations

### User Interactions
- Click nav link → smooth scroll to section
- Hover cards → 3D lift + glow effect
- Hover buttons → scale + glow pulse
- Scroll → elements fade in from bottom
- Mobile menu toggle → smooth slide animation

### Edge Cases
- Long project titles truncated with ellipsis
- Form validation prevents empty submission
- Images have fallback backgrounds

---

## Acceptance Criteria

1. ✅ Page loads without errors
2. ✅ All 7 sections visible and properly styled
3. ✅ Navbar collapses to offcanvas on mobile (<992px)
4. ✅ Smooth scroll works for all navigation links
5. ✅ Hero section has 3D floating elements
6. ✅ Project cards have hover zoom effect
7. ✅ Service cards have 3D tilt animation
8. ✅ Testimonial carousel functions
9. ✅ Contact form has focus animations
10. ✅ Fully responsive on all breakpoints
11. ✅ Colors match specified palette
12. ✅ Fonts load correctly (Google Fonts)
13. ✅ Icons display (Font Awesome)
