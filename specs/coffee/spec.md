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
- Click opens modal with full recipe

### 3.3.1 Recipe Modal
Clicking a recipe card opens a centered modal with full recipe details.

**Modal structure:**
- Close button (X) top-right
- Recipe emoji + name
- Equipment list (bullet points)
- Ingredients list (bullet points)
- Steps (numbered list, short summary)
- Pro tip section

**Modal behavior:**
- Opens on card click (fade in)
- Closes on: X click, overlay click, or ESC key
- Scrollable content for long recipes
- Full-width on mobile devices

**Recipe content (short summaries):**

1. **Classic Italian Espresso** — Equipment: espresso machine, grinder, tamper. Ingredients: 18g fine coffee, 36ml water. Steps: Grind, dose, tamp, extract 25-30s. Tip: Fresh beans = best crema.

2. **Smooth Cold Brew Concentrate** — Equipment: jar, strainer, filter. Ingredients: 100g coarse coffee, 700ml cold water. Steps: Combine, steep 12-24hrs, strain. Tip: Dilute 1:1 with water or milk before serving.

3. **Velvety Oat Milk Latte** — Equipment: espresso machine, frother. Ingredients: double shot, 200ml oat milk. Steps: Pull shot, steam milk to microfoam, pour. Tip: Oatly Barista Edition froths best.

4. **Chemex Clean Brew** — Equipment: Chemex, paper filter, kettle. Ingredients: 30g medium-coarse coffee, 500ml water. Steps: Rinse filter, bloom 30s, pour in circles. Tip: Gooseneck kettle gives best control.

5. **Honey Cinnamon Cortado** — Equipment: espresso machine, small glass. Ingredients: double shot, 60ml steamed milk, 1 tsp honey, pinch cinnamon. Steps: Warm honey, pull shot, steam milk, combine, dust cinnamon. Tip: Adjust honey to taste.

6. **Traditional Turkish Coffee** — Equipment: cezve/ibrik, small cups. Ingredients: 10g extra-fine coffee, 70ml water, sugar optional. Steps: Combine in cezve, heat slowly until foam rises, serve immediately. Tip: Never stir after foam forms.

### 3.4 Brewing Tips (3 cards with images)
1. **Water Quality Matters** — filtered water, 195-205°F (image: pour-over coffee)
2. **Measure Your Beans** — 1:15 ratio, use a scale (image: coffee beans close-up)
3. **Freshness is Key** — grind before brewing, 2-4 week window (image: coffee bag)

Each card has a real photo on top, heading, and description below.

### 3.5 Newsletter Signup
- Headline: "Get Weekly Recipes"
- Email input + subscribe button
- Simple form validation

### 3.6 Footer
- Logo and tagline
- Navigation links
- Social media icons (SVG icons: Instagram, X/Twitter, YouTube)
- Copyright notice
- No emojis — uses inline SVG icons

---

## 4. Design System

### 4.1 Color Palette (Dark Premium Theme)
| Name | Hex | Usage |
|------|-----|-------|
| Background Dark | #0F0A06 | Page background |
| Background Section | #1A1209 | Section backgrounds |
| Background Card | #231A10 | Card backgrounds |
| Cream | #F5E6CC | Headings, primary text |
| Gold | #C9A66B | Primary accent, buttons, tags |
| Gold Light | #E0C99A | Hover states |
| Brown Deep | #3D2B1F | Hero gradient, tips section |
| Text Light | #F5E6CC | Body text |
| Text Muted | #A89580 | Descriptions, secondary text |
| White | #FFFFFF | Modal text |

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
- **Buttons:** rounded, gold primary (filled) and outline variants
- **Cards:** dark card background, real photo with gradient overlay, content area, meta row
- **Tags:** small pill badges with gold accent on dark background
- **Form inputs:** dark background, gold border on focus

### 4.5 Images
- **Source:** Unsplash (free, no attribution required)
- **Recipe cards:** Real coffee photography (6 unique images)
- **Card display:** background-image with gradient overlay
- **Modal header:** Same recipe image as background
- **Image size:** 600x400px crops via Unsplash URL parameters

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

- [x] Add real coffee photography — DONE (Unsplash images, verified working)
- [ ] Individual recipe detail pages
- [ ] Light mode toggle (currently dark-only)
- [ ] Search/filter recipes
- [ ] User comments or ratings
- [ ] E-commerce integration
- [ ] Image lazy loading for performance
- [ ] Offline support (PWA)

---

## 10. Success Criteria

- [ ] All 6 recipe cards render correctly
- [ ] All 6 modals open and close properly
- [ ] Modal closes on ESC key and overlay click
- [ ] All 3 brewing tips display
- [ ] Newsletter form validates email
- [ ] Mobile menu toggles properly
- [ ] Smooth scroll works for all nav links
- [ ] Page loads fast (< 1s)
- [ ] Readable on mobile (320px+)
- [ ] Responsive on tablet (768px)
- [ ] Responsive on desktop (1024px+)

---

*Last updated: 2026-07-31 — v2.1 (Tip images + SVG footer icons)*
