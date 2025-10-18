# RecruitNexus Website Design Guidelines

## Design Approach
**Hybrid Professional Approach**: Combining LinkedIn's professional credibility with modern B2B service site aesthetics. The design prioritizes trust-building through clean layouts, strategic use of blue brand colors, and content-forward organization while maintaining visual appeal through industry imagery and thoughtful spacing.

## Core Design Principles
1. **Professional Trust**: Every element reinforces credibility and expertise
2. **Content Clarity**: Information hierarchy supports easy scanning and decision-making
3. **Brand Consistency**: Blue color palette maintains RecruitNexus identity throughout
4. **Strategic Visuals**: Industry images complement rather than dominate content

---

## Color Palette

**Primary Colors:**
- **Deep Navy**: 220 70% 25% (main brand, headers, navigation)
- **Corporate Blue**: 220 85% 55% (primary buttons, accents, links)
- **Sky Blue**: 210 100% 92% (backgrounds, subtle highlights)

**Neutral Colors:**
- **Charcoal**: 220 15% 20% (body text, dark mode option)
- **Slate Gray**: 220 10% 45% (secondary text, captions)
- **Cool Gray**: 220 15% 95% (section backgrounds, cards)
- **Pure White**: 0 0% 100% (main background, content areas)

**Accent Colors:**
- **Success Green**: 145 65% 45% (contact form success states)
- **Alert Orange**: 25 90% 60% (CTAs that need attention, use sparingly)

---

## Typography

**Font Families:**
- **Headings**: Inter (weights: 600, 700, 800)
- **Body Text**: Inter (weights: 400, 500, 600)
- **Navigation/UI**: Inter (weights: 500, 600)

**Type Scale:**
- **Hero Headline**: text-5xl md:text-6xl lg:text-7xl, font-bold
- **Page Titles**: text-4xl md:text-5xl, font-bold
- **Section Headers**: text-3xl md:text-4xl, font-semibold
- **Subsection Headers**: text-2xl md:text-3xl, font-semibold
- **Card Titles**: text-xl md:text-2xl, font-semibold
- **Body Large**: text-lg md:text-xl, font-normal
- **Body Regular**: text-base, font-normal
- **Captions**: text-sm, font-medium

**Line Height & Spacing:**
- Headlines: leading-tight (1.2)
- Body text: leading-relaxed (1.75)
- Section headings: leading-snug (1.375)

---

## Layout System

**Spacing Primitives:** Use Tailwind units of 4, 6, 8, 12, 16, 20, 24, 32 for consistent rhythm
- Component padding: p-6, p-8, p-12
- Section spacing: py-16, py-20, py-24, py-32
- Element gaps: gap-4, gap-6, gap-8, gap-12
- Margins: mt-8, mb-12, mx-auto

**Container Widths:**
- Full-width sections: w-full with max-w-7xl mx-auto px-6
- Content sections: max-w-6xl mx-auto
- Text-heavy content: max-w-4xl mx-auto
- Forms: max-w-2xl mx-auto

**Grid System:**
- Industry cards: grid-cols-1 md:grid-cols-2 lg:grid-cols-3
- Service cards: grid-cols-1 md:grid-cols-2 lg:grid-cols-3
- Features: grid-cols-1 md:grid-cols-2
- Contact layout: grid-cols-1 lg:grid-cols-2

---

## Navigation System

**Hamburger Menu:**
- Position: Fixed top-right corner with 24px margin
- Icon: 3 horizontal bars (w-8 h-0.5), Deep Navy color
- Slide-out panel: Full-height from right, w-80, white background with subtle shadow
- Menu items: text-xl, py-4, Deep Navy text, hover with Corporate Blue background tint
- Active page: Corporate Blue text with left border accent
- Close button: Top-right of panel, matching hamburger style
- Backdrop: Semi-transparent overlay (bg-black/50) when menu open
- Animation: Smooth 300ms ease-in-out transition

**Logo Placement:**
- Fixed top-left corner across all pages
- Size: h-12 md:h-16 maintaining aspect ratio
- Always links to home page

---

## Component Library

### Hero Sections

**Home Page Hero:**
- Full-width section with gradient background (Deep Navy to Corporate Blue diagonal)
- Logo centered at top: h-20 md:h-24
- Main headline: "Welcome to RecruitNexus – Your Nexus for Talent" (white, text-5xl md:text-6xl)
- Tagline: "Connecting Organizations. Building Futures." (Sky Blue tint, text-2xl)
- CTA button: "Get Started" (Alert Orange, rounded-lg, px-8 py-4)
- Industry showcase images below: 3-column grid on desktop, stacked on mobile
- Min height: 85vh with content centered

**Interior Page Heroes:**
- Simpler design: Deep Navy background
- Page title centered: white text, text-4xl md:text-5xl
- Subtitle/tagline: Sky Blue tint, text-xl
- Height: 40vh minimum

### Cards

**Industry Cards:**
- White background with subtle border (Cool Gray)
- Rounded corners: rounded-xl
- Padding: p-8
- Industry icon/image at top: h-48 w-full object-cover rounded-t-xl
- Title: text-2xl font-semibold, Deep Navy
- Tagline: Corporate Blue, text-lg, italic
- Description: Slate Gray, text-base, leading-relaxed
- Hover state: Shadow lift (shadow-lg), subtle scale (scale-105), Corporate Blue border

**Service Cards:**
- Similar to industry cards but with icon instead of image
- Icon: w-12 h-12, Corporate Blue
- Compact layout: p-6
- 3-column grid on desktop

### Forms

**Contact Form:**
- Clean white card with shadow: rounded-xl, p-8, shadow-md
- Input fields: border-2 border-Cool Gray, rounded-lg, p-4, focus:border-Corporate Blue
- Labels: text-sm font-semibold, Deep Navy, mb-2
- Textarea: min-h-40
- Submit button: Corporate Blue background, white text, rounded-lg, px-8 py-4, hover:opacity-90
- Required fields marked with Corporate Blue asterisk

**Form Layout:**
- Two-column grid on desktop: Form left, Company info right
- Single column on mobile
- Contact info card: matching form style with Deep Navy background, white text

### Content Sections

**Text Content Blocks:**
- Max-width for readability: max-w-4xl
- Paragraph spacing: mb-6
- Section spacing: py-20
- Alternating background colors: white and Sky Blue for visual rhythm

**List Presentations:**
- Bullet points with Corporate Blue markers
- Grid layout for feature lists: 2 columns on desktop
- Icon + text combination where appropriate

---

## Images

**Hero Background Image:**
- Home page: Use abstract professional imagery (office, collaboration, diversity in workplace) with Deep Navy overlay (opacity-70) to maintain text readability
- Dimensions: 1920x1080 minimum, optimized for web

**Industry Section Images:**
- Provided images showcasing Banking, Finance, Healthcare, Manufacturing, IT sectors
- Display in 3-column grid below hero on home page
- Each image: aspect-ratio 16:9, object-cover, rounded-lg
- Mobile: Stack vertically with mb-6

**Supporting Images:**
- About Us: Team/office environment image (if available) - top of page, full-width, h-96
- Industries Served: Individual industry hero images per section
- Services: Icon-based rather than photo-based to maintain clarity

**Image Treatment:**
- All images: Subtle rounded corners (rounded-lg to rounded-xl)
- Shadow on hover for interactive images: shadow-lg transition
- Maintain 16:9 aspect ratio for consistency

---

## Interactive Elements

**Buttons:**
- Primary CTA: Alert Orange background, white text, rounded-lg, px-8 py-4, font-semibold
- Secondary: Corporate Blue outline, Corporate Blue text, rounded-lg, px-6 py-3
- Hover states: Slight opacity change (hover:opacity-90) or subtle scale (hover:scale-105)
- Focus states: Ring-2 ring-Corporate Blue ring-offset-2

**Links:**
- Default: Corporate Blue underline on hover
- Navigation: Deep Navy with Corporate Blue on hover/active
- Footer: Slate Gray with white on hover

**Smooth Scroll:**
- All internal navigation uses smooth scrolling
- Anchor links with offset for fixed header (if implemented)

---

## Page-Specific Guidelines

**Home Page:**
- Hero with logo, headline, tagline, CTA
- Company overview section: 2-column layout (text + image)
- Industry showcase grid: 3 images with captions
- Services summary: 3-column card grid
- CTA section before footer: Deep Navy background, centered content

**About Us:**
- Hero with "About RecruitNexus" title
- Mission statement: full-width, centered, max-w-4xl
- Values section: 2-column grid with icons
- "Why Choose Us": Alternating text/image sections

**Industries Served:**
- Hero with page title
- Each industry: Full section with image, tagline, description
- Alternating layout: Image left/right for visual interest

**Services:**
- Hero with page title
- "End-to-End Recruitment" as featured section
- Supporting services: 3x3 grid of cards
- Each service card: Icon, title, brief description

**Contact Us:**
- Hero with page title
- 2-column layout: Contact form left, Company info right
- Info section includes: Phone, website, address, business hours
- Google Maps embed (optional): full-width below contact section

---

## Responsive Behavior

**Breakpoints:**
- Mobile: < 768px (single column, stacked elements)
- Tablet: 768px - 1024px (2-column layouts)
- Desktop: > 1024px (full multi-column layouts)

**Mobile Optimizations:**
- Hamburger menu replaces horizontal nav
- All grids collapse to single column
- Font sizes scale down appropriately
- Images: full-width on mobile
- Padding reduced: py-12 instead of py-20

---

## Accessibility

**Color Contrast:**
- All text meets WCAG AA standards (4.5:1 minimum)
- Deep Navy on white: 14.6:1
- Corporate Blue on white: 4.8:1
- Focus indicators: High contrast ring

**Interactive Elements:**
- All buttons/links: min-height 44px for touch targets
- Form inputs: Clear labels and focus states
- Skip-to-content link for keyboard navigation
- Alt text for all images

---

## Performance Considerations

- Lazy loading for below-fold images
- Optimize all images (WebP format preferred)
- Minimize animations (smooth transitions only, 300ms max)
- CSS-based effects over JavaScript where possible