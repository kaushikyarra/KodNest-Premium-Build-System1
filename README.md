# KodNest Premium Build System

A calm, intentional, and coherent design system for serious B2C product companies.

## Design Philosophy

**Calm, Intentional, Coherent, Confident**

This is not a student project. This design system is built for serious product companies that value clarity over flash, consistency over novelty, and confidence over trends.

### Core Principles
- No gradients, no glassmorphism, no neon colors
- No animation noise or excessive motion
- Maximum 4 colors across the entire system
- Generous whitespace as a design element
- Every component feels like one mind designed it

## Quick Start

### 1. Include the CSS

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Crimson+Pro:wght@400;600&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="design-system.css">
```

### 2. Use the Layout Structure

Every page follows this structure:

```html
<div class="layout-container">
  <header class="top-bar">...</header>
  <section class="context-header">...</section>
  <main class="main-content">
    <div class="primary-workspace">...</div>
    <aside class="secondary-panel">...</aside>
  </main>
  <footer class="proof-footer">...</footer>
</div>
```

### 3. View the Documentation

- **index.html** - Complete design system documentation
- **components.html** - All components in action

## Color System

```css
--color-background: #F7F6F3;  /* Off-white background */
--color-text-primary: #111111; /* Primary text */
--color-accent: #8B0000;       /* Deep red accent */
--color-success: #2D5016;      /* Muted green */
--color-warning: #8B6914;      /* Muted amber */
```

## Typography

- **Headings:** Crimson Pro (Serif) - Large, confident, generous spacing
- **Body:** Inter (Sans-serif) - 16–18px, line-height 1.6–1.8
- **Max width:** 720px for text blocks

## Spacing System

Consistent 8px-based scale:

```css
--space-xs: 8px;
--space-sm: 16px;
--space-md: 24px;
--space-lg: 40px;
--space-xl: 64px;
```

**Never use random spacing like 13px, 27px, etc.**

## Global Layout Structure

Every page must follow:

1. **Top Bar** - Project name (left), Progress indicator (center), Status badge (right)
2. **Context Header** - Large serif headline, 1-line subtext
3. **Primary Workspace (70%)** - Main product interaction
4. **Secondary Panel (30%)** - Step explanation, prompt box, action buttons
5. **Proof Footer** - Persistent validation checklist

## Component Rules

### Buttons
- **Primary:** Solid deep red background
- **Secondary:** Outlined with border
- Same hover effect and border radius everywhere

```html
<button class="btn btn-primary">Primary Action</button>
<button class="btn btn-secondary">Secondary Action</button>
```

### Inputs
- Clean borders, no heavy shadows
- Clear focus state with accent color

```html
<div class="input-group">
  <label class="input-label">Label</label>
  <input type="text" class="input" placeholder="Placeholder">
</div>
```

### Cards
- Subtle border, no drop shadows
- Balanced padding using spacing scale

```html
<div class="card">
  <h3 class="card__title">Card Title</h3>
  <p class="card__content">Card content goes here.</p>
</div>
```

## Interaction Rules

- **Transitions:** 150–200ms, ease-in-out
- **No bounce effects**
- **No parallax scrolling**
- Subtle, intentional hover states

## Error & Empty States

### Error States
- Explain what went wrong
- Provide clear next steps
- Never blame the user

```html
<div class="error-state">
  <div class="error-state__title">Error Title</div>
  <div class="error-state__message">What went wrong</div>
  <div class="error-state__action">How to fix it</div>
</div>
```

### Empty States
- Provide next action
- Never feel dead or abandoned

```html
<div class="empty-state">
  <div class="empty-state__title">No items yet</div>
  <div class="empty-state__message">Get started by creating one.</div>
  <button class="btn btn-primary">Create First Item</button>
</div>
```

## File Structure

```
kodnest-premium-build-system/
├── design-system.css      # Complete CSS framework
├── index.html            # Design system documentation
├── components.html       # Component showcase
└── README.md            # This file
```

## Git Repository Setup

### Initial Setup (Already Completed)

```bash
cd C:\Antigravity\2
git init
git add .
git commit -m "Initial commit: KodNest Premium Build System v1.0"
```

### Connect to GitHub

1. Create a new repository on GitHub: `kodnest-premium-build-system`
2. Run these commands:

```bash
git remote add origin https://github.com/kaushikyarra/kodnest-premium-build-system.git
git branch -M main
git push -u origin main
```

## Version

**v1.0.0** - Initial Release

## Author

**Kaushik Yarra**
- GitHub: [@kaushikyarra](https://github.com/kaushikyarra)
- Email: kaushikyarra@gmail.com

## License

This design system is proprietary to KodNest.

---

**Remember:** Everything must feel like one mind designed it. No visual drift.
