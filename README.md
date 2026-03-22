# Greenair Handling - B2B HVAC Supplier Website

## Overview

A complete, professional B2B HVAC supplier website for **Greenair Handling**, designed to generate inquiries, improve SEO rankings, and build trust with international buyers.

**Positioning:** B2B Supplier of HVAC Products for International Markets  
**Target Audience:** HVAC distributors, installers, construction companies, European and North American buyers

---

## Website Structure

```
greenair-website/
├── index.html                    # Homepage
├── css/
│   └── styles.css               # Complete stylesheet
├── js/
│   └── main.js                  # JavaScript functionality
├── images/                      # Image assets (placeholders)
├── products/
│   ├── index.html               # Product categories overview
│   ├── air-valves.html          # Air valves category page
│   ├── vcd-r-100.html           # Sample product detail page
│   ├── diffusers.html           # (to be created)
│   ├── louvers.html             # (to be created)
│   ├── dampers.html             # (to be created)
│   ├── duct-accessories.html    # (to be created)
│   └── hvac-fittings.html       # (to be created)
├── industries/
│   ├── index.html               # Industries overview
│   ├── commercial.html          # (to be created)
│   ├── hvac-systems.html        # (to be created)
│   ├── industrial.html          # (to be created)
│   └── residential.html         # (to be created)
├── about/
│   └── index.html               # About page
├── resources/
│   └── index.html               # Resources & downloads
├── blog/
│   └── index.html               # Blog listing
└── contact/
    └── index.html               # Contact page with form
```

---

## Pages Created

### 1. Homepage (`index.html`)
- Hero section with CTA
- Stats/trust section
- Product categories preview (6 cards)
- Industry applications (4 cards)
- Why Choose Us (4 features)
- Featured products grid
- CTA section
- Footer

### 2. Products Overview (`products/index.html`)
- SEO intro text
- 6 product category cards
- Download catalog CTA

### 3. Air Valves Category (`products/air-valves.html`)
- Filter sidebar (type, material, size, actuation, certification)
- Product grid with 8 products
- Bulk quote CTA
- Related categories

### 4. Product Detail (`products/vcd-r-100.html`)
- Product images
- Description tab
- Specifications table
- Applications tab
- Downloads tab
- Quick inquiry form
- Related products sidebar

### 5. Industries Overview (`industries/index.html`)
- SEO intro text
- 4 industry sections with:
  - Large images
  - Key applications
  - Recommended products
  - CTA buttons

### 6. About Page (`about/index.html`)
- Company story
- Mission & Vision
- Core Values (6 values)
- Certifications
- Global presence

### 7. Resources Page (`resources/index.html`)
- Product catalogs
- Technical documentation
- CAD & BIM files
- Installation guides

### 8. Blog Page (`blog/index.html`)
- Featured post
- Blog grid (6 posts)
- Pagination

### 9. Contact Page (`contact/index.html`)
- Contact form
- Office locations
- Working hours

---

## Design System

### Colors
- **Primary Green:** #2E7D32
- **Dark Green:** #1B5E20
- **Light Green:** #4CAF50
- **White:** #FFFFFF
- **Gray 100:** #F5F5F5
- **Gray 800:** #424242 (body text)
- **Gray 900:** #212121 (headings)

### Typography
- **Headings:** Montserrat (400, 500, 600, 700)
- **Body:** Open Sans (400, 500, 600)

### Components
- Buttons (primary, secondary, outline, link)
- Cards (product, category, blog)
- Forms (inputs, selects, textareas)
- Tabs
- Tables
- Breadcrumbs

---

## SEO Implementation

### Meta Tags (per page)
- Title tag (50-60 characters)
- Meta description (150-160 characters)
- Keywords

### H1 Structure
- Homepage: "Clean Air Solutions for Modern Buildings"
- Products: "HVAC Products"
- Air Valves: "Air Valves - HVAC Air Valve Supplier"
- Product Detail: "[Product Name] | [Product Code]"
- Industries: "Industry Solutions"
- About: "About Greenair Handling"
- Contact: "Contact Greenair Handling"

### Internal Linking
- Breadcrumb navigation on all pages
- Related products on product detail pages
- Cross-category links
- Footer navigation

---

## Conversion Elements

### CTAs Implemented
1. **"Request a Quote"** - Primary CTA in header, hero, product pages
2. **"Contact Us"** - Secondary CTA
3. **"Download Catalog"** - Resource CTA
4. **"View Details"** - Product exploration
5. **"Add to Inquiry"** - Product selection

### Sticky Elements
- Sticky header on scroll
- Sticky contact button (bottom right)

### Forms
- Contact form with validation
- Quick inquiry form on product pages
- Newsletter signup

---

## Responsive Design

### Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

### Mobile Optimizations
- Hamburger menu
- Stacked layouts
- Touch-friendly buttons
- Optimized typography

---

## JavaScript Features

### Implemented
- Header scroll effect
- Mobile menu toggle
- Smooth scroll for anchors
- Tab functionality
- Form validation
- Lazy loading (placeholder)
- Scroll animations
- Cookie consent banner
- Event tracking (placeholder)

---

## Next Steps for Implementation

### 1. Add Images
Create or source the following images:
- `images/hero-bg.jpg` - Hero background
- `images/about-facility.jpg` - Company facility
- `images/global-map.jpg` - World map
- `images/category-*.jpg` - 6 category images
- `images/industry-*.jpg` - 4 industry images
- `images/product-*.jpg` - Product images
- `images/blog-*.jpg` - Blog post images

### 2. Create Additional Product Pages
- `products/diffusers.html`
- `products/louvers.html`
- `products/dampers.html`
- `products/duct-accessories.html`
- `products/hvac-fittings.html`

### 3. Create Additional Product Detail Pages
Use `products/vcd-r-100.html` as a template for:
- Each product in the catalog
- Include unique specifications
- Add product-specific images

### 4. Create Industry Detail Pages
- `industries/commercial.html`
- `industries/hvac-systems.html`
- `industries/industrial.html`
- `industries/residential.html`

### 5. Create Blog Posts
- `blog/fire-damper-requirements.html`
- `blog/selecting-air-diffuser.html`
- Additional blog posts

### 6. Add PDF Resources
- `resources/catalog.pdf`
- `resources/air-valves-catalog.pdf`
- `resources/diffusers-catalog.pdf`
- `resources/technical-specs.pdf`
- Product datasheets
- CAD files (DWG)
- Revit families (RFA)

### 7. Backend Integration
- Form submission handling
- Email notifications
- CRM integration
- Analytics (Google Analytics 4)

### 8. SEO Enhancements
- XML sitemap
- Robots.txt
- Schema markup
- Open Graph tags
- Canonical URLs

---

## Performance Optimization

### Recommended
- Compress images (WebP format)
- Enable GZIP compression
- Use CDN for static assets
- Implement caching headers
- Lazy load below-fold images
- Minify CSS/JS for production

---

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)

---

## License

© 2024 Greenair Handling. All rights reserved.

---

## Contact

For questions or support:
- Email: sales@greenairhandling.com
- Phone: +31 10 123 4567
