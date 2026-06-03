# The Lash Bar — Mobile-Optimized Website Components

A collection of responsive, high-fashion HTML/Tailwind CSS blocks designed for embedding in Google Sites. All components are fully optimized for mobile devices with a focus on touch accessibility, responsive layouts, and luxury brand presentation.

## 🎯 Design Philosophy

Three core responsive principles applied across all blocks:

1. **True Responsive Stack** – Single-column vertical layout on mobile, multi-column on desktop
2. **Flexible Heights** – Uses `min-h` and aspect ratios instead of rigid fixed heights
3. **Touch-Safe Targets** – Generous padding and spacing for thumb-friendly interactions

## 📁 Components

### 1. Header Navigation Bar (`01-header-nav.html`)
- Sticky top navigation with logo, menu links, and call-to-action button
- Mobile-friendly hamburger menu pattern ready
- Backdrop blur effect on scroll
- Premium prism shimmer button effect

### 2. Hero Section (`02-hero-section.html`)
- Full-bleed hero with responsive background image
- Overlay gradient for text legibility on mobile
- Dynamic content animation on page load
- Scaling text and typography for all screen sizes

### 3. Philosophy & Experience Section (`03-philosophy-grid.html`)
- Two-column desktop layout → single column mobile
- Image with grayscale filter and responsive aspect ratio
- Italicized accent quotes with premium typography
- Smooth hover effects on desktop

### 4. Services Menu (`04-services-menu.html`)
- Stacked service cards with pricing and duration
- Desktop: side-by-side layout for name/price
- Mobile: full-width stacked layout for readability
- Hover animations and underline effects

### 5. Booking Portal (`05-booking-form.html`)
- Full-width stacked form inputs on mobile
- Date/time selection with touch-friendly spacing
- Confirmation success state
- Focus states with color-coded visual feedback

### 6. Footer & Map (`06-footer-map.html`)
- Single column on mobile → two columns on desktop
- Embedded Google Maps with responsive sizing
- Contact hours and location details
- Dark luxury theme

## 🚀 Quick Start

1. **Copy any HTML block** into your Google Sites embed frame
2. All blocks include:
   - Tailwind CSS CDN (no build step required)
   - Responsive meta viewport tags
   - Google Fonts imports
   - Custom CSS animations
3. **No dependencies** – Pure HTML/CSS/Tailwind

## 📱 Mobile-First Breakpoints

- **Mobile:** Base styles (< 640px)
- **Small (sm:):** 640px and up
- **Medium (md:):** 768px and up  
- **Large (lg:):** 1024px and up

All Tailwind utilities use these breakpoints for progressive enhancement.

## 🎨 Design System

**Color Palette:**
- Primary Dark: `#2C1A14`
- Accent Tan: `#C59B87`
- Cream Background: `#FDFBF7`
- Warm Gray: `#6E5A53`

**Typography:**
- Serif: Playfair Display (headlines, luxury accents)
- Sans-serif: Inter (body text, UI elements)

**Spacing:**
- Mobile-safe gutters: `px-4` to `px-5`
- Desktop padding: `px-12`
- Vertical spacing: Proportional using Tailwind scale

## ✅ Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile Safari (iOS 12+)
- ✅ Chrome Mobile

## 🔧 Customization

Each block is self-contained with inline styles. To customize:

1. Update color values (search for hex codes like `#2C1A14`)
2. Modify text content in HTML
3. Replace image URLs (currently using Unsplash placeholders)
4. Adjust spacing using Tailwind scale (e.g., `px-6` → `px-8`)

## 📝 Notes

- All components include a `<meta name="viewport">` tag for proper mobile scaling
- Google Sites embed frames may override some styles; test thoroughly
- Images use Unsplash URLs; replace with your own high-quality assets
- Form submissions redirect to a success state (not integrated with backend)

## 🎯 Testing Checklist

Before deploying to Google Sites:

- [ ] Test on iPhone 12 (390px width)
- [ ] Test on iPhone SE (375px width)
- [ ] Test on Android (360px width)
- [ ] Test landscape orientation
- [ ] Verify form inputs are touch-accessible (44×44px minimum)
- [ ] Check that images don't distort or get cut off
- [ ] Verify all links work correctly
- [ ] Test map embed loads without lag

---

**Created:** June 2026  
**Author:** Kayelisse  
**License:** Personal Use
