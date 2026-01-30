# SecondSkin Lifestyle - Premium Fashion & Apparel Website

A modern, premium fashion e-commerce website for SecondSkin Lifestyle — a contemporary brand focused on everyday wear that feels like a second skin.

## 🎨 Brand Overview

**Brand Positioning:**
SecondSkin Lifestyle is a contemporary fashion brand focused on everyday wear that feels like a second skin — comfortable, stylish, minimal, and confidence-driven.

**Target Audience:**
Urban men & women (18–35), fashion-conscious, lifestyle-focused, online shoppers.

**Visual Style:**
- Clean, minimal, premium aesthetic
- Neutral tones (black, white, beige, charcoal)
- Soft textures, fabric-focused imagery
- Editorial fashion look (Zara / H&M / Uniqlo inspired)

## 📦 Project Structure

```
secondskin-lifestyle/
├── index.html              # Homepage
├── shop.html               # Shop/Product listing page
├── about.html              # About us page
├── assets/
│   ├── css/
│   │   ├── style.css       # Main stylesheet
│   │   ├── shop.css        # Shop page styles
│   │   └── about.css       # About page styles
│   ├── js/
│   │   ├── main.js         # Main JavaScript
│   │   └── shop.js         # Shop page functionality
│   └── images/             # Image assets
│       ├── hero-bg.jpg
│       ├── collection-*.jpg
│       ├── product-*.jpg
│       ├── brand-story.jpg
│       ├── instagram-*.jpg
│       ├── about-story.jpg
│       ├── sustainability-*.jpg
│       └── team-*.jpg
```

## ✨ Features

### Homepage Sections
- **Hero Banner** - Bold tagline: "Wear Your Second Skin"
- **Featured Collections** - Men / Women / Unisex
- **Bestsellers Carousel** - Interactive product showcase
- **Brand Story** - Comfort meets style narrative
- **Fabric & Fit Highlights** - Feature cards
- **Customer Reviews** - Social proof section
- **Instagram Gallery** - #SecondSkinLifestyle showcase
- **Newsletter Signup** - Email capture with CTA

### Core Pages Included
- ✅ Home (`index.html`)
- ✅ Shop (`shop.html`) - With filters and product grid
- ✅ About Us (`about.html`) - Brand story and values
- 📝 Product Detail Page (template ready)
- 📝 Lookbook (template ready)
- 📝 Contact Us (template ready)
- 📝 Policies (template ready)

### UI/UX Features
- ✅ Mobile-first responsive design
- ✅ Sticky header with smooth scroll
- ✅ Dropdown navigation menus
- ✅ Search overlay functionality
- ✅ Mobile menu drawer
- ✅ Smooth hover animations
- ✅ Modern sans-serif typography (Inter)
- ✅ High-conversion CTAs

### E-commerce Features
- ✅ Product filters (size, color, category, price)
- ✅ Wishlist functionality (localStorage)
- ✅ Cart system (localStorage)
- ✅ Product quick view
- ✅ Sort options
- ✅ Pagination
- ✅ Color and size selectors
- 📝 Checkout flow (template ready)
- 📝 Size guide (template ready)

### Interactive Elements
- Sticky navigation with scroll detection
- Search overlay with Esc key support
- Mobile menu with overlay
- Product carousel with navigation
- Wishlist toggle with notifications
- Smooth scroll for anchor links
- Intersection Observer animations
- Lazy loading images

## 🎨 Design System

### Color Palette
```css
--color-primary: #000000      /* Black */
--color-secondary: #ffffff    /* White */
--color-accent: #2f2f2f       /* Dark Gray */
--color-beige: #d4c5b9        /* Beige */
--color-charcoal: #4a4a4a     /* Charcoal */
--color-light-gray: #f5f5f5   /* Light Gray */
```

### Typography
- **Font Family:** Inter (Google Fonts)
- **Weights:** 300, 400, 500, 600, 700
- **Responsive scaling** using clamp() functions

### Spacing System
```css
--spacing-xs: 0.5rem
--spacing-sm: 1rem
--spacing-md: 1.5rem
--spacing-lg: 2rem
--spacing-xl: 3rem
--spacing-2xl: 4rem
--spacing-3xl: 6rem
```

## 🚀 Getting Started

### 1. Installation
No build process required! Simply open the HTML files in a modern web browser.

```bash
# Clone or download the project
cd secondskin-lifestyle

# Open in browser
# Option 1: Double-click index.html
# Option 2: Use a local server (recommended)
```

### 2. Running with Local Server

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server -p 8000
```

**Using VS Code:**
Install "Live Server" extension and click "Go Live"

### 3. Adding Product Images

Replace placeholder image paths in HTML with actual product images:

```
assets/images/
├── hero-bg.jpg              # 1920x1080px
├── collection-women.jpg     # 800x1066px (3:4 ratio)
├── collection-men.jpg       # 800x1066px (3:4 ratio)
├── collection-unisex.jpg    # 800x1066px (3:4 ratio)
├── product-1.jpg through product-n.jpg  # 600x800px (3:4 ratio)
├── brand-story.jpg          # 800x1000px (4:5 ratio)
├── instagram-1.jpg through instagram-6.jpg  # 400x400px (1:1 ratio)
└── ... (additional images as needed)
```

## 🎯 Customization Guide

### Changing Brand Name
1. Update `<title>` tags in all HTML files
2. Update `.logo` text in HTML
3. Update footer logo text
4. Update meta descriptions

### Modifying Colors
Edit CSS variables in `assets/css/style.css`:
```css
:root {
    --color-primary: #your-color;
    --color-secondary: #your-color;
    /* etc. */
}
```

### Adding Products
In `shop.html`, duplicate product card structure:
```html
<div class="product-card" data-product-id="X">
    <!-- Product markup -->
</div>
```

### Customizing Sections
All sections are modular and can be:
- Reordered
- Hidden (add `display: none`)
- Duplicated
- Modified independently

## 📱 Responsive Breakpoints

- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px
- **Large Desktop:** > 1400px (max container width)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance Optimization

### Implemented:
- Lazy loading images
- CSS/JS minification ready
- Optimized animations (GPU-accelerated)
- Intersection Observer for scroll animations
- LocalStorage for cart/wishlist (reduces server calls)

### Recommended:
1. **Image Optimization:**
   - Use WebP format with JPG fallbacks
   - Compress images (TinyPNG, ImageOptim)
   - Implement responsive images with `<picture>` tags

2. **Asset Loading:**
   - Defer non-critical JavaScript
   - Inline critical CSS
   - Use CDN for static assets

3. **Caching:**
   - Set cache headers for static assets
   - Implement service worker for offline support

## 🛠️ Development Roadmap

### Additional Pages to Create:
- [ ] Product Detail Page (product.html)
- [ ] Lookbook/Lifestyle (lookbook.html)
- [ ] Contact Us (contact.html)
- [ ] Policies (policies.html)
  - Shipping Info
  - Returns & Exchanges
  - Size Guide
  - FAQ
  - Privacy Policy
  - Terms of Service

### Future Enhancements:
- [ ] Shopping cart drawer/modal
- [ ] Checkout flow
- [ ] User account system
- [ ] Product reviews system
- [ ] Related products
- [ ] Recently viewed items
- [ ] Size recommendation tool
- [ ] Virtual try-on
- [ ] Live chat integration
- [ ] Multi-currency support
- [ ] Multi-language support

## 🔌 Integration Ready

The website is structured to integrate with:

### E-commerce Platforms:
- **Shopify** - Use as theme base
- **WooCommerce** - Convert to WordPress theme
- **BigCommerce** - Adapt templates
- **Custom Backend** - API-ready structure

### Payment Gateways:
- Stripe
- PayPal
- Square
- Apple Pay / Google Pay

### Marketing Tools:
- Google Analytics
- Facebook Pixel
- Mailchimp
- Klaviyo
- Instagram Shopping

## 📄 File Details

### HTML Files

**index.html (Homepage)**
- Complete hero section with CTA
- Collection showcase grid
- Product carousel
- Brand story
- Feature highlights
- Customer reviews
- Instagram gallery
- Newsletter signup
- Footer with links

**shop.html (Shop Page)**
- Advanced filtering sidebar
- Product grid with pagination
- Sort functionality
- Mobile filter drawer
- Quick view buttons

**about.html (About Page)**
- Brand story section
- Core values grid
- Sustainability commitment
- Team member showcase
- CTA section

### CSS Files

**style.css (Main Styles)**
- CSS custom properties
- Base styles and reset
- Typography system
- Layout components
- Header and navigation
- Hero section
- Product cards
- Features/reviews
- Footer
- Utility classes

**shop.css (Shop Specific)**
- Filter sidebar
- Product grid
- Pagination
- Mobile filters

**about.css (About Specific)**
- About hero
- Story layout
- Values grid
- Team section
- Sustainability section

### JavaScript Files

**main.js (Core Functionality)**
- Header scroll behavior
- Mobile menu
- Search overlay
- Carousel controls
- Wishlist management
- Cart functionality
- Newsletter form
- Notification system
- Smooth scrolling
- Intersection Observer animations

**shop.js (Shop Functionality)**
- Filter interactions
- Sort functionality
- Mobile filter drawer
- Quick view
- Pagination
- URL parameter handling

## 🎨 Design Assets Needed

### Photography Style Guide:
- **Clean backgrounds** - White, beige, or minimal settings
- **Natural lighting** - Soft, diffused light
- **Lifestyle shots** - Models in everyday settings
- **Detail shots** - Fabric texture, stitching close-ups
- **Flat lays** - Product styling on neutral backgrounds

### Image Specifications:
- **Hero:** 1920x1080px (16:9)
- **Product:** 600x800px (3:4)
- **Collection:** 800x1066px (3:4)
- **Instagram:** 400x400px (1:1)
- **Brand Story:** 800x1000px (4:5)

## 📞 Support & Documentation

For questions or customization needs:
- Review code comments in HTML/CSS/JS files
- Check browser console for debugging
- Use browser DevTools for layout adjustments

## 📝 License

This is a custom website template created for SecondSkin Lifestyle.
All rights reserved.

## 🙏 Credits

- **Font:** Inter by Rasmus Andersson (Google Fonts)
- **Icons:** Custom SVG icons (inline)
- **Design:** Inspired by modern editorial fashion websites

---

**Version:** 1.0.0  
**Last Updated:** January 2026  
**Created by:** Blackbox AI Development Team

## 🚀 Quick Start Checklist

- [ ] Download/clone the project
- [ ] Add product images to `assets/images/`
- [ ] Update brand name and meta information
- [ ] Customize colors in CSS variables
- [ ] Test on mobile devices
- [ ] Add real product data
- [ ] Set up analytics tracking
- [ ] Configure email newsletter
- [ ] Set up payment gateway
- [ ] Launch! 🎉
