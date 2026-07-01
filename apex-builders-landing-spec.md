# Apex Builders — Landing Page Design Spec

## Brand

| Element | Value |
|---------|-------|
| **Company Name** | Apex Builders |
| **Tagline** | Building Tomorrow's Landmarks Today |
| **Industry** | Construction & Development |

---

## Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Primary (Dark Navy) | Deep Blue | `#1A2744` |
| Secondary (White) | Pure White | `#FFFFFF` |
| Accent (Gold) | Warm Gold | `#C9A962` |
| Text Primary | Charcoal | `#2D2D2D` |
| Text Secondary | Slate Gray | `#6B7280` |
| Background Light | Off-White | `#F8F9FA` |
| Background Dark | Navy Tint | `#0F1729` |

---

## Typography

| Element | Font | Weight | Size |
|---------|------|--------|------|
| Logo/Brand | Playfair Display | 700 | 28px |
| H1 (Hero) | Playfair Display | 700 | 56px |
| H2 (Section Titles) | Playfair Display | 600 | 40px |
| H3 (Card Titles) | Inter | 600 | 20px |
| Body | Inter | 400 | 16px |
| Button | Inter | 600 | 14px |
| Nav Links | Inter | 500 | 15px |

---

## Page Structure

### 1. Navigation Bar (Fixed)
- **Height:** 80px
- **Background:** `#1A2744` (Navy)
- **Layout:** Logo left, nav links center, CTA right
- **Logo:** "APEX" in Playfair Display, gold accent underline
- **Links:** Home • Services • About • Projects • Contact
- **CTA Button:** "Get a Quote" — Gold background (`#C9A962`), navy text

---

### 2. Hero Section
- **Height:** 100vh (full viewport)
- **Background:** Construction site image with dark overlay (`rgba(26,39,68,0.75)`)
- **Layout:** Centered content
- **H1:** "Building Tomorrow's Landmarks Today" — White
- **Subheadline:** "Award-winning construction company delivering excellence across residential, commercial, and renovation projects." — White, 18px
- **CTA Button:** "Get a Quote" — Gold background, large (padding: 18px 40px)
- **Secondary Link:** "View Our Work" — White text with gold underline

---

### 3. Services Section
- **Background:** `#F8F9FA` (Light)
- **Padding:** 100px vertical
- **H2:** "Our Services" — Navy
- **Subtitle:** "Comprehensive construction solutions tailored to your vision."
- **Layout:** 4-column grid (2 on tablet, 1 on mobile)

#### Service Cards (x4)
| Service | Icon | Description |
|---------|------|-------------|
| Residential Construction | 🏠 House icon | Custom homes, multi-family dwellings, and community developments built with quality and sustainability in mind. |
| Commercial Projects | 🏢 Building icon | Office spaces, retail centers, and industrial facilities designed for productivity and lasting value. |
| Renovations | 🔨 Hammer icon | Modern transformations of existing structures, from kitchen remodels to full property overhauls. |
| Project Management | 📋 Clipboard icon | End-to-end oversight ensuring timelines, budgets, and quality standards are met. |

- **Card Style:** White background, subtle shadow (`0 4px 20px rgba(0,0,0,0.08)`), 24px padding, 8px border-radius
- **Icon:** 48px, gold color
- **Title:** Navy, Inter 600
- **Description:** Slate gray, 15px

---

### 4. About Section
- **Background:** White
- **Padding:** 100px vertical
- **Layout:** 2-column (image left, text right)
- **Image:** Placeholder for team/office photo (aspect ratio 4:3)
- **H2:** "Crafting Excellence Since 1995"
- **Body Text:** "At Apex Builders, we believe great construction is born from the fusion of skilled craftsmanship, innovative thinking, and unwavering commitment to client satisfaction. Every project we undertake is a testament to our dedication to quality."
- **Stats Row:** 
  - "250+" Projects Completed
  - "25+" Years Experience
  - "100%" Client Satisfaction

- **Stats Style:** Large numbers in gold, labels in slate gray

---

### 5. Projects / Portfolio Section
- **Background:** `#1A2744` (Dark Navy)
- **Padding:** 100px vertical
- **H2:** "Featured Projects" — White
- **Subtitle:** "A glimpse into our recent work."
- **Layout:** 3-column masonry grid

#### Project Cards (x6)
| # | Project Name | Category | Placeholder Image |
|---|--------------|----------|-------------------|
| 1 | Harbor View Towers | Commercial | Modern high-rise |
| 2 | The Oak Residence | Residential | Custom home |
| 3 | Downtown Office Renovation | Commercial | Office interior |
| 4 | Sunset Villa | Residential | Luxury home |
| 5 | Metro Shopping Center | Commercial | Retail building |
| 6 | Heritage Museum Restoration | Renovation | Restored building |

- **Card Style:** Image with dark overlay, project name overlaid at bottom in white
- **Hover:** Slight scale (1.02) + gold border accent

---

### 6. Testimonials Section
- **Background:** `#F8F9FA`
- **Padding:** 80px vertical
- **Layout:** Centered quote carousel style
- **Quote:** "Apex Builders transformed our vision into reality. Their professionalism and attention to detail were exceptional from start to finish."
- **Author:** — Sarah Mitchell, CEO of Mitchell Realty
- **Style:** Large quotation marks in gold, italic body text

---

### 7. Contact Section
- **Background:** White
- **Padding:** 100px vertical
- **Layout:** 2-column (form left, info right)

#### Contact Form (Left)
- **Fields:** 
  - Full Name (text)
  - Email (email)
  - Phone (tel)
  - Project Type (dropdown: Residential / Commercial / Renovation / Other)
  - Message (textarea)
- **Submit Button:** "Send Message" — Gold background, full width
- **Style:** Clean input fields with 1px border `#E5E7EB`, 12px padding, 6px radius

#### Contact Info (Right)
- **H2:** "Let's Build Something Great"
- **Body:** "Ready to start your project? Get in touch for a free consultation."
- **Details:**
  - 📞 (555) 123-4567
  - 📧 info@apexbuilders.com
  - 📍 1250 Construction Ave, Suite 400, Denver, CO 80202
- **Office Hours:** Mon–Fri: 8:00 AM – 6:00 PM

---

### 8. Footer
- **Background:** `#0F1729` (Darker Navy)
- **Padding:** 60px vertical
- **Layout:** 4-column

| Column | Content |
|--------|---------|
| Brand | Logo + tagline + brief description |
| Quick Links | Home, Services, About, Projects, Contact |
| Services | Residential, Commercial, Renovations, Project Management |
| Social | Facebook, LinkedIn, Instagram, Twitter icons |

- **Bottom Bar:** Copyright © 2026 Apex Builders. All rights reserved.
- **Text:** Slate gray, 14px

---

## Responsive Breakpoints

| Breakpoint | Width | Adjustments |
|------------|-------|-------------|
| Desktop | 1200px+ | Full layout |
| Tablet | 768px–1199px | 2-column grids → 2 columns |
| Mobile | <768px | Single column, hamburger nav, stacked sections |

---

## Figma Implementation Tips

1. **Auto Layout** — Use Figma's auto layout for cards and nav
2. **Components** — Create reusable: Button, Card, Input, NavLink
3. **Variants** — Button: Primary / Secondary / Ghost
4. **Color Styles** — Define as styles: `Primary`, `Secondary`, `Accent`, `TextPrimary`, `TextSecondary`, `BackgroundLight`, `BackgroundDark`
5. **Text Styles** — Define: `H1`, `H2`, `H3`, `Body`, `Button`, `NavLink`
6. **Images** — Use `Unsplash` or `Pexels` for construction placeholder images

---

## Copy All

### Nav
- Home
- Services
- About
- Projects
- Contact

### Hero
- Headline: Building Tomorrow's Landmarks Today
- Subheadline: Award-winning construction company delivering excellence across residential, commercial, and renovation projects.
- CTA: Get a Quote
- Secondary: View Our Work

### Services Titles
- Residential Construction
- Commercial Projects
- Renovations
- Project Management

### About
- Heading: Crafting Excellence Since 1995
- Body: At Apex Builders, we believe great construction is born from the fusion of skilled craftsmanship, innovative thinking, and unwavering commitment to client satisfaction. Every project we undertake is a testament to our dedication to quality.
- Stats: 250+ Projects • 25+ Years • 100% Satisfaction

### Contact
- Heading: Let's Build Something Great
- Phone: (555) 123-4567
- Email: info@apexbuilders.com
- Address: 1250 Construction Ave, Suite 400, Denver, CO 80202