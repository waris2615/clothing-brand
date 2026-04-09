# ELEGANTE - Luxury Clothing Brand Website

## 📋 Project Overview

**Project Name:** ELEGANTE  
**Type:** Multi-page Luxury E-commerce Website  
**Live URL:** https://waris2615.github.io/clothing-brand  
**Repository:** https://github.com/waris2615/clothing-brand  

---

## 🎯 Project Description

ELEGANTE is a premium luxury clothing brand website featuring a classic, elegant design with 3D elements and modern web technologies. The website showcases high-end fashion products with an emphasis on timeless sophistication.

---

## 📁 File Structure

```
clothing-brand/
├── index.html          # Home page - Landing with hero, featured products
├── shop.html           # Shop page - Product listing with filters
├── collections.html    # Collections page - Seasonal & category showcases
├── about.html          # About page - Brand heritage, team, timeline
├── contact.html        # Contact page - Form & boutique locations
├── product.html        # Product detail page - Gallery, options, reviews
├── cart.html           # Shopping cart - Items, summary, promo codes
├── checkout.html       # Checkout - Shipping, payment, order summary
├── account.html        # My Account - Dashboard, orders, wishlist, profile
├── blog.html           # Journal/Blog - Articles, categories, newsletter
├── blog-post.html      # Blog post - Full article with related posts
├── .gitignore         # Git ignore file
└── README.md          # This documentation
```

> **Note:** All pages are now standalone and self-contained. CSS and JavaScript are embedded directly within each HTML file for easy deployment. Only Google Fonts and Font Awesome CDN links remain external.

---

## 🧑‍💻 Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| HTML5 | - | Page structure & semantic markup |
| CSS3 | - | Styling, animations, 3D effects |
| JavaScript | ES6+ | Interactive features & DOM manipulation |
| Google Fonts | - | Typography (Playfair Display, Cormorant Garamond, Montserrat) |
| Font Awesome | 6.4.0 | Icons |

---

## 🎨 Design System

### Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary | `#1a1a1a` | Text, buttons, backgrounds |
| Accent | `#c9a959` | Highlights, CTAs, decorative elements |
| Accent Dark | `#a68b3d` | Hover states |
| Cream | `#f8f5f0` | Backgrounds |
| Light Gray | `#e8e4df` | Borders, dividers |
| Text | `#333333` | Body text |
| Text Light | `#666666` | Secondary text |
| White | `#ffffff` | Cards, contrast elements |

### Typography

| Font | Family | Usage |
|------|--------|-------|
| Display | Playfair Display | Headlines, headings |
| Body | Cormorant Garamond | Paragraphs, descriptions |
| Sans | Montserrat | UI elements, labels, buttons |

### Font Sizes

| Element | Size |
|---------|------|
| H1 | 4rem (64px) |
| H2 | 3rem (48px) |
| H3 | 1.5rem (24px) |
| Body | 1.1rem (18px) |
| Small | 0.9rem (14px) |
| Caption | 0.75rem (12px) |

---

## 📄 Page Documentation

### 1. Home Page (`index.html`)

**Purpose:** Landing page showcasing the brand identity and featured products.

**Sections:**
- **Navigation** - Fixed navbar with logo, links, cart icon
- **Hero Section** - Full-height hero with 3D mannequin, animated background layers
- **Features Bar** - Premium quality, free shipping, easy returns, secure payment
- **Collections Grid** - 5-card grid showcasing main categories
- **Showcase** - Featured product spotlight with 3D coat model
- **Products Grid** - 6 featured products with hover effects
- **About Section** - Brand heritage with image and statistics
- **Testimonials** - Client reviews carousel
- **Newsletter** - Email subscription form
- **Contact Section** - Boutique locations and contact form
- **Footer** - Links, social media, copyright

**Key Features:**
- 3D mannequin animation with CSS transforms
- Parallax background effects
- Custom cursor with follower
- Animated statistics counter
- Floating 3D coat model
- Testimonials auto-slider

---

### 2. Shop Page (`shop.html`)

**Purpose:** Product catalog with filtering and sorting capabilities.

**Sections:**
- **Page Header** - Title and breadcrumb
- **Sidebar Filters**
  - Categories (All, Men's Outerwear, Women's, Shirts, Accessories, Footwear)
  - Price Range slider ($0 - $3,000)
  - Size options (XS, S, M, L, XL)
  - Color swatches
- **Toolbar** - Results count, sort dropdown, view toggle
- **Products Grid** - 12 products with pagination
- **Features Bar** - Brand promises
- **Footer**

**Products Displayed:**
- Classic Wool Jacket - $895
- Silk Evening Dress - $1,250
- Cotton Oxford Shirt - $285
- Italian Leather Tote - $1,450
- Oxford Brogue Shoes - $780
- Cashmere V-Neck Sweater - $520
- Classic Navy Blazer - $1,195
- Cocktail Midi Dress - $890
- Wool Blend Overcoat - $2,450
- Merino Wool Cardigan - $485
- Leather Briefcase - $1,850
- Leather Penny Loafers - $625

**Features:**
- Filter by category, price, size, color
- Sort by Featured, Price (Low/High), Newest
- Grid/List view toggle
- Pagination (4 pages)
- "Add to Bag" on hover
- Sale badges with original price strikethrough

---

### 3. Collections Page (`collections.html`)

**Purpose:** Showcase seasonal collections and product categories.

**Sections:**
- **Seasonal Collections**
  - Autumn/Winter 2026 - "The Renaissance Collection"
  - Spring/Summer 2026 - "The Mediterranean Dreams"
- **Category Grid** - 6 category cards (Men's, Women's, Knitwear, Accessories, Footwear, Outerwear)
- **Lookbook** - Editorial-style gallery
- **Exclusive Collection** - Limited edition countdown timer
- **Features Bar**
- **Footer**

**Key Features:**
- Alternating layout for seasonal sections
- Hover zoom on images
- Live countdown timer (12 days, 8 hours, 45 minutes, 30 seconds)
- Instagram-style lookbook gallery

---

### 4. About Page (`about.html`)

**Purpose:** Brand story, values, team, and heritage.

**Sections:**
- **Heritage** - Brand founding story (1952)
- **Values Grid** - 4 core values:
  - Uncompromising Quality
  - Handcrafted Excellence
  - Sustainable Future
  - Timeless Design
- **Atelier Section** - Milan workshop features
- **Team Grid** - 4 leadership members with photos and roles
- **Statistics Bar** - Animated counters (70+ years, 150 craftsmen, 50 countries, 100 awards)
- **Timeline** - Brand milestones from 1952 to 2026
- **Features Bar**
- **Footer**

**Team Members:**
1. Alessandro ELEGANTE - Creative Director
2. Sofia Marchetti - Head of Design
3. Giovanni Rossi - Master Tailor
4. Elena Bianchi - Sustainability Director

**Timeline Milestones:**
- 1952: The Beginning
- 1968: Women's Collection Launch
- 1985: International Expansion
- 2002: 50th Anniversary
- 2020: Sustainability Initiative
- 2026: The Future

---

### 5. Contact Page (`contact.html`)

**Purpose:** Contact information, inquiry forms, and boutique locations.

**Sections:**
- **Contact Info** - Get in touch methods
- **Contact Methods**
  - Visit Our Boutiques
  - Call Us (+1 800 ELEGANTE)
  - Email Us (concierge@elegante.com)
  - Live Chat
- **Social Links** - Instagram, Facebook, Pinterest, Twitter, YouTube
- **Contact Form** - Full inquiry form with:
  - First Name, Last Name
  - Email Address
  - Phone Number
  - Subject dropdown (Order, Appointment, Custom, Returns, Styling, Other)
  - Message textarea
  - Newsletter checkbox
- **Boutiques Grid** - 6 global locations:
  1. Milan (Flagship)
  2. Paris
  3. New York
  4. London
  5. Tokyo
  6. Dubai
- **Appointment CTA** - Private shopping booking
- **Features Bar**
- **Footer**

**Boutique Details:**
| Location | Address | Hours |
|----------|---------|-------|
| Milan | Via Montenapoleone 12, 20121 | Mon-Sat: 10am-7pm |
| Paris | 24 Rue du Faubourg Saint-Honoré, 75008 | Mon-Sat: 10am-7pm |
| New York | 725 Fifth Avenue, NY 10022 | Mon-Sat: 10am-8pm |
| London | 171 New Bond Street, W1S 4RD | Mon-Sat: 10am-6pm |
| Tokyo | 5-8-1 Ginza, Chuo-ku | Daily: 11am-8pm |
| Dubai | The Dubai Mall, Fashion Avenue | Sun-Thu: 10am-10pm |

---

## ⚙️ Components

### Navigation Bar
- Fixed position with backdrop blur
- Logo (ELEGANTE)
- Navigation links (Home, Shop, Collections, About, Contact)
- Action icons (Search, Wishlist, Cart with badge)
- Mobile hamburger menu

### Product Card
- 3D hover effect (rotateX/rotateY)
- Primary and hover images
- Action buttons (Eye, Heart, Sync)
- "Add to Bag" slide-up on hover
- Category label
- Product name
- Price display
- Color options
- Sale/New badges

### Buttons
| Type | Style |
|------|-------|
| Primary | Solid background (primary/accent), white text |
| Secondary | Transparent, border, fills on hover |
| Outline | Transparent, thin border |

### Form Elements
- Text inputs with labels
- Select dropdowns
- Textareas
- Checkboxes
- Range sliders
- Focus states with accent border

### Footer
- 4-column layout
- Brand info with logo and social links
- Quick Links
- Customer Care links
- About links
- Copyright bar

---

## 🎭 Animations & Effects

### 3D Effects
- **Mannequin Float** - Continuous up/down motion
- **Product Cards** - 3D rotation on hover
- **Coat 3D** - Rotation based on mouse position
- **Collection Cards** - Tilt effect following cursor

### Scroll Animations
- Fade-in on scroll (Intersection Observer)
- Parallax background layers
- Navigation highlight based on section

### Hover Effects
- Image zoom/scale
- Button background transitions
- Card lift with shadow
- Link underline animations
- Icon color transitions

### Other Animations
- Custom cursor with follower
- Mouse wheel scroll indicator
- Counter number animation
- Testimonials auto-slider (5s interval)
- Cart badge bounce on add
- Countdown timer

---

## 📱 Responsive Breakpoints

| Breakpoint | Width | Changes |
|------------|-------|---------|
| Desktop XL | 1200px+ | Full layout, 3-4 column grids |
| Desktop | 992px - 1199px | 2-3 column grids |
| Tablet | 768px - 991px | 2 column grids, stacked layouts |
| Mobile | < 768px | Single column, hamburger menu |

### Mobile Adaptations
- Navigation collapses to hamburger menu
- Hero hides 3D element
- Grids reduce to single column
- Typography scales down
- Hide custom cursor
- Form fields stack vertically
- Footer becomes single column

---

## 🔧 JavaScript Features

### DOM Manipulation
- Navigation toggle
- Scroll-based navigation highlighting
- Intersection Observer for animations
- Dynamic stat counters

### Form Handling
- Newsletter subscription (simulated)
- Contact form submission (simulated)
- Cart counter updates

### Visual Effects
- Custom cursor tracking
- Parallax scrolling
- Mouse-based 3D rotations
- Testimonial slider with dots

### Utilities
- Smooth scroll navigation
- Scroll-triggered animations
- Product card hover enhancements

---

## 🔒 Security Notes

### API Keys
This project does NOT include any API keys. All forms are frontend-only simulations.

### Environment Variables
No backend is required. All functionality is client-side.

### Git Ignore
The `.gitignore` file excludes:
- Environment files (`.env`, `.env.local`)
- API key files (`*.key`, `credentials.json`)
- MCP config (`.mcp.json`)
- Node modules
- OS files

---

## 🚀 Deployment

### GitHub Pages
The website is deployed using GitHub Pages from the `gh-pages` branch.

**Live URL:** https://waris2615.github.io/clothing-brand/

### Deployment Steps
1. Push code to `gh-pages` branch
2. GitHub automatically builds the site
3. Available at `https://[username].github.io/[repo-name]/`

---

## 🔮 Future Enhancements

Potential features for future development:

- [ ] Product detail pages
- [ ] Shopping cart functionality with localStorage
- [ ] User authentication
- [ ] Backend API integration
- [ ] Wishlist functionality
- [ ] Size guide modal
- [ ] Live chat integration
- [ ] Instagram feed integration
- [ ] Blog/editorial section
- [ ] Multi-language support

---

## 👥 Credits

**Design & Development:** Generated with AI assistance  
**Brand:** ELEGANTE (Fictional luxury brand)  
**Images:** Unsplash (placeholder product and lifestyle images)  
**Fonts:** Google Fonts  
**Icons:** Font Awesome 6.4.0

---

## 📄 License

This project is for demonstration purposes. All images are from Unsplash and remain property of their respective owners.

---

*Document Version: 1.0*  
*Last Updated: April 9, 2026*
