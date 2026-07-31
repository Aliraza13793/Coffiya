# Coffiya - Specialty Coffee Recipe Website

## 1. Project Overview

**Name:** Coffiya
**Type:** Recipe showcase website (single-page)
**Purpose:** Share free specialty coffee recipes, brewing guides, and tips
**Audience:** Casual coffee drinkers who want to explore specialty coffee at home
**Tech:** Single static HTML file (HTML/CSS/JS inlined)

---

## 2. Goals

- Build a warm, inviting brand presence for coffee lovers
- Share recipes openly to build trust and community
- Encourage return visits with fresh, useful content
- Grow an email list for ongoing engagement

---

## 3. Website Sections

### 3.1 Navigation
- Fixed top navbar with logo + links
- Mobile hamburger menu
- Smooth scroll to sections

### 3.2 Hero
- Brand headline and subheadline
- Primary CTA: "Explore Recipes"
- Secondary CTA: "Brewing Guides"
- Warm gradient background with decorative accent

### 3.3 Featured Recipes (6 cards)
| Recipe | Category | Difficulty | Time |
|--------|----------|------------|------|
| Classic Italian Espresso | Espresso | Beginner | 5 min |
| Smooth Cold Brew Concentrate | Cold Brew | Easy | 12 hrs |
| Velvety Oat Milk Latte | Latte Art | Intermediate | 8 min |
| Chemex Clean Brew | Pour Over | Beginner | 6 min |
| Honey Cinnamon Cortado | Specialty | Easy | 5 min |
| Traditional Turkish Coffee | Turkish | Intermediate | 10 min |

**Card contents:**
- Recipe name
- Short description
- Category tag
- Time estimate
- Difficulty level
- Hover effect (lift + shadow)

### 3.4 Brewing Tips (3 cards)
1. **Water Quality Matters** — filtered water, 195-205°F
2. **Measure Your Beans** — 1:15 ratio, use a scale
3. **Freshness is Key** — grind before brewing, 2-4 week window

### 3.5 Newsletter Signup
- Headline: "Get Weekly Recipes"
- Email input + subscribe button
- Simple form validation

### 3.6 Footer
- Logo and tagline
- Navigation links
- Social media icons (Instagram, Twitter, YouTube)
- Copyright notice

---

## 4. Design System

### 4.1 Color Palette
| Name | Hex | Usage |
|------|-----|-------|
| Cream | #FDF6EC | Page background |
| Warm Brown | #6B4423 | Primary accent, buttons |
| Dark Brown | #3D2314 | Headings, footer |
| Amber | #D4A574 | Cards, highlights |
| Light Amber | #E8C9A0 | Borders, tags |
| Soft Orange | #C98B5E | Secondary accent |
| Text Dark | #2C1810 | Body text |
| Text Muted | #6B5B4F | Descriptions |
| White | #FFFFFF | Card backgrounds |

### 4.2 Typography
- **Headings:** Playfair Display (serif) — elegant, warm
- **Body:** Inter (sans-serif) — clean, readable
- **Hero title:** clamp(2.5rem, 6vw, 4rem)
- **Section titles:** clamp(2rem, 4vw, 3rem)
- **Body text:** 1rem–1.15rem

### 4.3 Layout
- Max content width: 1200px
- Section padding: 6rem top/bottom
- Card border-radius: 1rem
- Generous whitespace throughout

### 4.4 Components
- **Buttons:** rounded, primary (filled) and outline variants
- **Cards:** cream background, image area, content area, meta row
- **Tags:** small pill badges with light amber background
- **Form inputs:** bordered, rounded, focus state

---

## 5. Responsive Breakpoints

| Breakpoint | Behavior |
|------------|----------|
| > 768px | Desktop — full nav, 3-column grid |
| <= 768px | Mobile — hamburger menu, single column, stacked CTAs |

---

## 6. Interactions & Animations

- Smooth scroll on nav link clicks
- Card hover: translateY(-5px) + box-shadow
- Button hover: color shift + subtle lift
- Mobile menu toggle
- Newsletter form submit: alert confirmation

---

## 7. Technical Requirements

- Single HTML file, all CSS/JS inlined
- No external dependencies (except Google Fonts)
- Semantic HTML5 structure
- Accessible: alt text, ARIA labels, focus states
- SEO: meta description, proper heading hierarchy

---

## 8. File Structure

```
specs/coffee/spec.md    ← this file
coffee/index.html       ← built from spec
```

---

## 9. Future Enhancements (Out of Scope)

- [ ] Add real coffee photography
- [ ] Individual recipe detail pages
- [ ] Dark mode toggle
- [ ] Search/filter recipes
- [ ] User comments or ratings
- [ ] E-commerce integration

---

## 10. Success Criteria

- [ ] All 6 recipe cards render correctly
- [ ] All 3 brewing tips display
- [ ] Newsletter form validates email
- [ ] Mobile menu toggles properly
- [ ] Smooth scroll works for all nav links
- [ ] Page loads fast (< 1s)
- [ ] Readable on mobile (320px+)

---

*Last updated: 2026-07-31*
