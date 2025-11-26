# Product Requirements Document (PRD)
## Taimur Saadat - Finance & Investment Education Platform

---

## 1. Executive Summary

### 1.1 Product Overview
Taimur Saadat's Finance Platform is a professional website showcasing financial education courses, feasibility study services, and investment expertise. The platform targets investment professionals, aspiring traders, and organizations seeking financial analysis services.

### 1.2 Product Vision
To establish an authoritative online presence for Taimur Saadat as a premier finance educator and consultant, providing comprehensive trading education and professional feasibility study services.

### 1.3 Success Metrics
- User engagement (time on site, pages per session)
- Course inquiry conversions
- Contact form submissions
- Mobile user experience satisfaction
- Page load performance (<3s)
- SEO ranking for key financial education terms

---

## 2. Product Description

### 2.1 Target Users

**Primary Users:**
1. **Investment Professionals**
   - Seeking CMT (Chartered Market Technician) certification
   - Looking to enhance trading and technical analysis skills
   - Age: 25-45
   - Background: Finance, economics, business

2. **Aspiring Traders**
   - Individuals starting their trading career
   - Students pursuing finance education
   - Age: 20-35
   - Tech-savvy, mobile-first users

3. **Corporate Clients**
   - Organizations requiring feasibility studies
   - Investment firms seeking consultant services
   - Decision-makers in financial planning

**Secondary Users:**
- Recruiters evaluating Taimur's credentials
- Media/press seeking expert commentary
- Academic institutions for collaboration

---

## 3. User Stories & Use Cases

### 3.1 Core User Journeys

**Journey 1: Course Discovery**
```
As an investment professional
I want to explore trading courses
So that I can advance my career with CMT certification

Steps:
1. Land on homepage via Google search
2. View hero section with value proposition
3. Navigate to Courses section
4. Click on "Trading and Technical Analysis" course
5. Review 3-level curriculum structure
6. Contact via form or email
```

**Journey 2: Feasibility Study Inquiry**
```
As a business decision-maker
I want to learn about feasibility study services
So that I can evaluate investment opportunities

Steps:
1. Access Feasibility Studies page
2. Review service offerings and approach
3. View methodology and outcomes
4. Submit inquiry through contact form
```

**Journey 3: Mobile Browse & Learn**
```
As a mobile user
I want to quickly access course information
So that I can learn on-the-go

Steps:
1. Open site on mobile device
2. Use burger menu to navigate
3. Swipe through hero slider images
4. Review course details with readable text
5. Easily submit contact form
```

---

## 4. Functional Requirements

### 4.1 Homepage

#### 4.1.1 Navigation
- **Desktop Navigation**
  - Fixed navbar with logo, menu items, and theme toggle
  - Dropdown menu for "Courses" with 2 sub-items
  - Smooth scroll to sections
  - Active state indicators

- **Mobile Navigation**
  - Hamburger menu icon (top-left)
  - Theme toggle icon (top-right within menu)
  - Full-screen overlay menu
  - Left-aligned links with course sub-items indented
  - No accordion for course dropdowns (always visible)

#### 4.1.2 Hero Section
- **Slider Component**
  - 5 rotating hero images
  - Auto-advance every 5 seconds
  - Left/Right arrow navigation
  - Touch swipe gestures (mobile)
  - Dot indicators at bottom
  - Dark overlay for text readability

- **Hero Content**
  - Primary heading with gradient text effect
  - Subtitle with value proposition
  - Two CTA buttons:
    - "Courses Offered" → Links to #courses section
    - "Learn More" → Links to #contact section
  - Mobile-optimized button styling with proper sizing

#### 4.1.3 Market Data Widgets
- TradingView Market Overview widget
- TradingView Advanced Real-Time Chart widget
- Responsive iframe embedding

#### 4.1.4 Features Section
- 3-column grid layout
- Icon + title + description cards
- Hover effects with elevation
- Mobile: Single column stack

#### 4.1.5 Courses Section
- 2 course cards in grid layout
- Each card includes:
  - Course thumbnail image
  - "View Course →" overlay on hover
  - Course title
  - Description
  - Level/topic breakdown
- Links to dedicated course pages

#### 4.1.6 About Me Section
- Professional bio with 3 paragraphs
- Profile image
- Split layout (text left, image right)
- Mobile: Stacked layout

#### 4.1.7 Qualifications Section
- List of credentials
- Clean, simple presentation
- Contrasting background

#### 4.1.8 Contact Form Section
- **Form Fields:**
  - Name (text input)
  - Email (email input)
  - Message (textarea)
  - Submit button
- **Contact Information Display:**
  - Email address
  - Phone number
  - Location
- **Form Validation:**
  - Required field indicators
  - Proper input types
  - Mobile-optimized with proper boundaries

#### 4.1.9 Footer
- 3-column layout:
  - Brand info with tagline
  - Quick Links (matching navbar order)
  - Social media links (X/Twitter, LinkedIn, Facebook)
- Copyright notice
- Consistent across all pages (except Feasibility Studies)

### 4.2 Trading & Technical Analysis Page

#### 4.2.1 Course Hero Section
- Gradient background
- Course title
- Brief description

#### 4.2.2 Course Levels
- **Level I: Foundation**
  - Learning objectives
  - Topics covered (Week 1)
  
- **Level II: Advanced Concepts**
  - Learning objectives
  - Topics covered (Week 2 & 3)
  
- **Level III: Expert Techniques**
  - Learning objectives
  - Topics covered (Week 4-7)

#### 4.2.3 Course Structure
- Visual cards for each level
- Expandable/collapsible content
- Bullet-point format for easy scanning

#### 4.2.4 Registration CTA
- Prominent call-to-action section
- Link to contact form

### 4.3 Derivatives & Portfolio Management Page

#### 4.3.1 Content Sections
- **I. Derivatives and Structured Products**
  - Introduction paragraph
  - Detailed course list with sub-items
  - Options strategies coverage

- **II. Portfolio Construction**
  - Key principles
  - Investment philosophy
  - Risk mitigation strategies

- **III. Portfolio Asset Allocation**
  - Investor type classifications
  - Asset allocation strategies
  - Risk profiles

- **IV. Equity Trading Strategies**
  - Advanced trading concepts
  - Market timing
  - Technical analysis application

#### 4.3.2 Text Readability
- Enhanced font sizing (1.05rem)
- Improved line height (1.7-1.8)
- Proper color contrast
- Adequate spacing between sections

### 4.4 Feasibility Studies Page

#### 4.4.1 Services Overview
- Professional introduction
- Service categories
- Industry expertise

#### 4.4.2 Methodology
- Step-by-step approach
- Analysis frameworks
- Deliverables description

#### 4.4.3 Page Requirements
- **No Footer** (per client requirement)
- Full-width hero section
- Structured content layout

---

## 5. Non-Functional Requirements

### 5.1 Performance
- **Page Load Time:** <3 seconds on 4G connection
- **First Contentful Paint:** <1.5 seconds
- **Time to Interactive:** <3.5 seconds
- **Lighthouse Score:** >90 (Performance, Accessibility, Best Practices, SEO)

### 5.2 Responsiveness
- **Breakpoints:**
  - Mobile: 320px - 480px
  - Tablet: 481px - 768px
  - Desktop: 769px+
  
- **Mobile-First Design:**
  - Touch-optimized buttons (min 44px tap target)
  - Swipe gestures for slider
  - Optimized form fields
  - Readable text (16px minimum)

### 5.3 Browser Compatibility
- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)
- Mobile browsers (iOS Safari, Chrome Mobile)

### 5.4 Accessibility (WCAG 2.1 AA)
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for all images
- Keyboard navigation support
- ARIA labels where necessary
- Sufficient color contrast ratios (4.5:1 minimum)
- Focus indicators for interactive elements

### 5.5 SEO Requirements
- **Meta Tags:**
  - Unique title tags per page
  - Meta descriptions (150-160 characters)
  - Open Graph tags for social sharing
  
- **Structured Data:**
  - Person schema for Taimur Saadat
  - Course schema for educational offerings
  - Organization schema

- **Technical SEO:**
  - Sitemap.xml
  - Robots.txt
  - Canonical URLs
  - Mobile-friendly (Google Mobile-First Indexing)

### 5.6 Security
- HTTPS encryption
- Secure form submission
- No sensitive data storage
- XSS protection
- CSRF protection for forms

---

## 6. Design System

### 6.1 Color Palette

**Primary Colors:**
- Primary Blue: `#1e3a8a` (Dark Blue)
- Secondary Blue: `#4a6fff` (Accent Blue)
- Gradient: `linear-gradient(135deg, #4a6fff 0%, #6b5eff 100%)`

**Neutral Colors:**
- Background (Light): `#ffffff`
- Background (Dark): `#0f0f1e`
- Card Background (Light): `#f8f9fa`
- Card Background (Dark): `#1a1a2e`
- Text (Light): `#333333`
- Text (Dark): `#e0e0e0`
- Secondary Text: `#666666` / `#a0a0a0`

**Functional Colors:**
- Success: `#10b981`
- Warning: `#f59e0b`
- Error: `#ef4444`
- Info: `#3b82f6`

### 6.2 Typography

**Font Family:**
- Primary: `'Segoe UI', Tahoma, Geneva, Verdana, sans-serif`
- Fallback: System fonts

**Font Sizes:**
- Hero Heading: 3rem (desktop), 2rem (mobile)
- H1: 2.5rem
- H2: 2rem
- H3: 1.5rem
- H4: 1.2rem
- Body: 1rem
- Small: 0.875rem

**Font Weights:**
- Regular: 400
- Medium: 500
- Semi-bold: 600
- Bold: 700

### 6.3 Spacing System
- Base unit: 0.5rem (8px)
- Scale: 0.5rem, 1rem, 1.5rem, 2rem, 3rem, 4rem, 6rem

### 6.4 Component Specifications

#### 6.4.1 Buttons
- **Primary Button:**
  - Background: Blue gradient
  - Color: White
  - Padding: 1rem 2rem
  - Border-radius: 12px
  - Font-weight: 600
  - Box-shadow on hover
  
- **Secondary Button:**
  - Background: Transparent with glassmorphic effect
  - Border: 2px solid rgba(255,255,255,0.3)
  - Backdrop-filter: blur(10px)
  - Color: White
  - Same padding/radius as primary

#### 6.4.2 Cards
- Border-radius: 10px-15px
- Box-shadow: `0 10px 40px rgba(0, 0, 0, 0.1)`
- Padding: 2rem-3rem
- Hover: Slight elevation increase

#### 6.4.3 Forms
- Input height: 48px minimum
- Border: 2px solid rgba(74, 111, 255, 0.15)
- Border-radius: 10px
- Focus state: Border color change + glow
- Mobile: Full width with box-sizing

### 6.5 Animations & Transitions
- **Hover Transitions:** 0.3s ease
- **Slide Transitions:** 0.5s ease
- **Button Press:** Scale 0.95-0.97
- **Menu Slide:** 0.3s cubic-bezier
- **Gradient Animation:** 3s ease infinite

---

## 7. Technical Architecture

### 7.1 Technology Stack

**Frontend:**
- HTML5 (semantic markup)
- CSS3 (with CSS Grid, Flexbox, CSS Variables)
- Vanilla JavaScript (ES6+)
- No frameworks (lightweight approach)

**External Libraries:**
- Font Awesome 6.5.1 (icons)
- TradingView Widgets (market data)

**Hosting & Infrastructure:**
- Static site hosting (Netlify, Vercel, or GitHub Pages)
- CDN for asset delivery
- DNS management

### 7.2 File Structure
```
taimu/
├── index.html
├── trading-analysis.html
├── derivatives.html
├── feasibilities.html
├── css/
│   └── styles.css (2767 lines)
├── js/
│   ├── main.js (theme, navigation, scroll)
│   └── slider.js (hero slider + swipe gestures)
├── assets/
│   ├── images/
│   │   ├── hero1.jpg - hero5.jpg
│   │   ├── testimonial1.jpg, testimonial2.jpg
│   │   ├── Logo_taimur.png
│   │   └── taimur-profile.jpg
│   └── favicon/
│       ├── favicon.ico
│       ├── apple-touch-icon.png
│       └── site.webmanifest
└── PRD.md (this document)
```

### 7.3 JavaScript Modules

**main.js Functions:**
- `toggleTheme()`: Switch between light/dark mode
- `handleScroll()`: Navbar background on scroll
- `smoothScroll()`: Smooth anchor navigation
- `toggleMobileMenu()`: Burger menu open/close
- `handleDropdown()`: Desktop dropdown hover
- Image lazy loading with IntersectionObserver

**slider.js Functions:**
- `showSlide(index)`: Display specific slide
- `nextSlide()`: Advance to next slide
- `prevSlide()`: Go to previous slide
- Touch event handlers: `touchstart`, `touchend`
- Swipe gesture detection
- Auto-advance timer (5s interval)

### 7.4 CSS Architecture

**Organization:**
- CSS Variables for theming
- Mobile-first media queries
- Component-based selectors
- Utility classes for common patterns

**Key Sections:**
1. Root variables & resets
2. Navbar & navigation
3. Hero section & slider
4. Feature sections
5. Course cards
6. Forms & inputs
7. Footer
8. Course pages (trading-analysis, derivatives)
9. Feasibility studies page
10. Responsive media queries

---

## 8. Content Requirements

### 8.1 Homepage Content

**Hero Section:**
- Headline: "Strategic investing with a focus on growth and risk control"
- Subtext: "Driving smart investments, ensuring sustainable growth, and strategically managing risk for long-term financial success"

**About Me:**
- 3-paragraph professional bio covering:
  - 15+ years experience
  - Expertise areas (FX, Treasury, Risk Management, etc.)
  - Leadership and results-driven approach

**Qualifications:**
- MSc Finance - Heriot-Watt University
- MBA, Finance & Islamic Banking - Preston University Ajman
- Associate's Degree, Technical Analysis - Market Technician Association

### 8.2 Course Content

**Trading & Technical Analysis:**
- CMT Level 1, 2, 3 curriculum
- Week-by-week topic breakdown
- Learning objectives per level

**Derivatives:**
- 4 main sections (Derivatives, Portfolio Construction, Asset Allocation, Equity Trading)
- Detailed bullet points
- Practical applications
- Risk profiles

### 8.3 Images & Media

**Required Images:**
- 5 hero slider images (trading-related visuals)
- 2 course thumbnails
- 1 profile photo
- 3 feature icons (chart, shield, brain/AI)
- Logo (transparent PNG)

**Image Specifications:**
- Hero images: 1920x1080px, optimized <500KB each
- Course thumbnails: 800x600px
- Profile: 500x500px
- Logo: Scalable SVG preferred, PNG fallback

---

## 9. User Interface Specifications

### 9.1 Mobile Interface (320px - 768px)

**Navigation:**
- Burger icon: 3 lines, 24px width
- Menu overlay: Full-screen, dark background with blur
- Logo: Visible with left margin (not cut off)
- Theme toggle: Top-right, fully visible

**Hero Section:**
- Slider arrows: 45x45px, blue with opacity 0.7
- Swipe gestures: Minimum 50px horizontal distance
- Buttons: Full-width (max 320px), stacked vertically
- Button text: 1rem, centered, adequate line-height

**Contact Form:**
- Inputs: Full-width with proper box-sizing
- No border overflow
- Labels above fields
- Submit button: Full-width

### 9.2 Desktop Interface (>768px)

**Navigation:**
- Fixed top navbar
- Horizontal menu items
- Dropdown on hover
- Theme toggle: Right side

**Hero Section:**
- Slider arrows: 60x60px, positioned 30px from edges
- Mouse click + keyboard navigation
- Buttons: Inline, gradient effects

**Content Layout:**
- Max-width: 1200px container
- Grid layouts for features, courses
- 2-column splits for about/qualification sections

### 9.3 Interactions

**Hover States:**
- Cards: Slight lift (translateY -5px)
- Buttons: Scale 1.05, enhanced shadow
- Links: Color change, underline
- Images: Scale 1.05 (overflow hidden)

**Active States:**
- Buttons: Scale 0.95-0.97
- Forms: Focus ring with glow
- Slider dots: Color + size change

**Loading States:**
- Images: Lazy load with fade-in
- Forms: Disable button on submit
- Page transitions: Smooth scroll

---

## 10. Testing Requirements

### 10.1 Functional Testing

**Test Cases:**
1. **Navigation**
   - [ ] All navbar links work correctly
   - [ ] Dropdown menu shows/hides properly
   - [ ] Mobile burger menu opens/closes
   - [ ] Course sub-items are visible in mobile
   - [ ] Theme toggle switches between light/dark
   - [ ] Smooth scroll to anchors works

2. **Hero Slider**
   - [ ] Auto-advance works (5s interval)
   - [ ] Left arrow goes to previous slide
   - [ ] Right arrow goes to next slide
   - [ ] Swipe left/right changes slides (mobile)
   - [ ] Dot indicators reflect current slide
   - [ ] Clicking dots navigates to specific slide

3. **Forms**
   - [ ] Name field accepts text input
   - [ ] Email field validates email format
   - [ ] Message textarea allows multi-line input
   - [ ] Submit button is clickable
   - [ ] Required fields show validation
   - [ ] No border overflow on mobile

4. **Links & CTAs**
   - [ ] "Courses Offered" scrolls to #courses
   - [ ] "Learn More" scrolls to #contact
   - [ ] Course cards link to respective pages
   - [ ] Footer links navigate correctly
   - [ ] Social icons open in new tabs

### 10.2 Responsive Testing

**Devices to Test:**
- iPhone 12/13/14 (390x844)
- iPhone SE (375x667)
- Samsung Galaxy S21 (360x800)
- iPad (768x1024)
- Desktop 1920x1080

**Orientation:**
- Portrait and landscape for mobile/tablet

### 10.3 Browser Testing
- Chrome Windows/Mac
- Safari macOS/iOS
- Firefox Windows/Mac
- Edge Windows
- Mobile browsers (Chrome Mobile, Safari iOS)

### 10.4 Accessibility Testing
- [ ] Keyboard navigation works (Tab, Enter, Escape)
- [ ] Screen reader compatibility (NVDA, JAWS)
- [ ] Color contrast ratios meet WCAG AA
- [ ] Focus indicators are visible
- [ ] Alt text present for all images
- [ ] Form labels properly associated

### 10.5 Performance Testing
- [ ] Lighthouse audit: >90 score
- [ ] PageSpeed Insights: Green scores
- [ ] Image optimization verified
- [ ] No console errors
- [ ] Network waterfall analysis

---

## 11. Deployment & Maintenance

### 11.1 Deployment Checklist
- [ ] All pages tested and functional
- [ ] Mobile responsiveness verified
- [ ] Forms working (backend if applicable)
- [ ] Analytics installed (Google Analytics)
- [ ] Favicon visible in all browsers
- [ ] Meta tags for SEO complete
- [ ] Social media preview images working
- [ ] 404 page created
- [ ] HTTPS certificate active
- [ ] Domain DNS configured

### 11.2 Ongoing Maintenance

**Weekly:**
- Monitor form submissions
- Check uptime/availability
- Review analytics data

**Monthly:**
- Update course content if changed
- Check for broken links
- Review performance metrics
- Security patch updates

**Quarterly:**
- Content refresh
- SEO audit
- Accessibility review
- User feedback analysis

### 11.3 Version Control
- Git repository for code
- Semantic versioning (v1.0.0)
- Development branch for testing
- Main/production branch

---

## 12. Future Enhancements

### 12.1 Phase 2 Features (3-6 months)
- [ ] Course enrollment system with payment integration
- [ ] Student dashboard/login area
- [ ] Video course content delivery
- [ ] Live chat support
- [ ] Newsletter subscription
- [ ] Blog section for market insights
- [ ] Downloadable resources (PDFs, guides)

### 12.2 Phase 3 Features (6-12 months)
- [ ] Learning Management System (LMS)
- [ ] Student progress tracking
- [ ] Certification issuance
- [ ] Community forum
- [ ] Webinar scheduling system
- [ ] Multi-language support
- [ ] Advanced analytics dashboard

### 12.3 Technical Improvements
- [ ] Convert to React/Next.js for scalability
- [ ] Implement headless CMS for content management
- [ ] Add automated testing suite
- [ ] Progressive Web App (PWA) capabilities
- [ ] Offline functionality
- [ ] Advanced caching strategies

---

## 13. Stakeholder Sign-off

### 13.1 Approval Required From:
- **Client (Taimur Saadat):** Content, design, functionality
- **Developer:** Technical feasibility, timeline
- **Designer (if applicable):** Visual design, UX flow

### 13.2 Success Criteria
✅ All functional requirements met  
✅ Mobile experience optimized  
✅ Forms working properly  
✅ Footer consistent across pages (except Feasibility)  
✅ Text readability on all pages  
✅ Hero slider with swipe gestures functional  
✅ Performance targets achieved  

---

## 14. Appendix

### 14.1 Glossary
- **CMT:** Chartered Market Technician certification
- **LMS:** Learning Management System
- **CTA:** Call-to-Action
- **SEO:** Search Engine Optimization
- **PWA:** Progressive Web App
- **WCAG:** Web Content Accessibility Guidelines

### 14.2 References
- Market Technicians Association: https://www.mta.org/
- TradingView Widgets: https://www.tradingview.com/widget/
- WCAG Guidelines: https://www.w3.org/WAI/WCAG21/quickref/

### 14.3 Document History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2025-11-26 | Development Team | Initial PRD creation |

---

**End of Product Requirements Document**

