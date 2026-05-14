# WGSI SL Tourism Website

A modern, luxury, fully responsive tourism website for a Sri Lankan travel brand called **WGSI SL**.

## Features

### Design
- Premium and modern travel website design
- Mobile-friendly responsive layout
- Smooth animations and elegant transitions (Framer Motion)
- Full-screen hero section with auto-sliding backgrounds
- Professional UI/UX with glassmorphism effects
- Tropical color palette: Ocean Blue, Palm Green, Sunset Orange
- Rounded cards and modern styling
- SEO optimized with meta tags

### Pages & Sections
1. **Home Page** - Hero banner, featured destinations, stats counter, CTA buttons
2. **About Us** - Company intro, mission/vision, team showcase
3. **Tour Packages** - 6 curated packages with filtering (Ella, Sigiriya, South Coast, Kandy, Yala, Nuwara Eliya)
4. **Gallery** - Masonry layout with category filtering and lightbox
5. **Hotels** - Featured luxury accommodations
6. **Travel Tips** - Essential travel information
7. **Reviews System** - Star ratings, comment posting, verified badges, like/report
8. **Photo Upload** - Community photo gallery with drag-and-drop upload
9. **FAQ** - Accordion-style questions and answers
10. **Contact/Booking** - Full booking form with tour selection and date picker
11. **Emergency Assistance** - Floating button with tourist police contacts, safety tips

### Interactive Features
- Sticky navigation with scroll-aware styling
- Animated counters (5000+ travelers, 50+ destinations, etc.)
- Customer testimonial carousel
- Category filtering for destinations, tours, and gallery
- Image lightbox with keyboard navigation
- WhatsApp floating contact button
- Emergency assistance floating button (accessible from every page)
- Review submission form with star ratings
- Photo upload with preview
- Smooth scroll navigation
- Mobile-responsive hamburger menu

### Security & Admin Features (Architecture Ready)
- Modular component structure for easy CMS integration
- Reusable components for scalable content management
- Clean data layer (`src/lib/data.ts`) for easy backend integration
- Zustand-ready state management structure
- Form validation ready for backend integration
- Image upload preview system ready for Cloudinary integration

## Technology Stack
- **Next.js 14** - React framework with App Router
- **React 18** - UI library
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Animations and transitions
- **Lucide React** - Icon library
- **CLSX + Tailwind Merge** - Conditional class handling

## Color Palette
| Color | Hex | Usage |
|-------|-----|-------|
| Ocean Blue | #0284c7 | Primary brand, buttons, links |
| Palm Green | #16a34a | Secondary, nature elements |
| Sunset Orange | #f97316 | Accents, CTAs, highlights |
| White | #ffffff | Backgrounds, cards |

## Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build
```

## Project Structure
```
wgsi-sl-tourism/
├── src/
│   ├── app/
│   │   ├── globals.css      # Global styles & Tailwind
│   │   ├── layout.tsx       # Root layout with metadata
│   │   └── page.tsx         # Main page with all sections
│   ├── components/
│   │   └── (sections in page.tsx)
│   ├── lib/
│   │   ├── utils.ts         # Utility functions
│   │   └── data.ts          # All website data
│   ├── types/
│   │   └── index.ts         # TypeScript interfaces
│   └── hooks/
│       └── (custom hooks)
├── public/
│   └── images/
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── next.config.js
```

## Future Expansion Ready
The codebase is structured for easy integration of:
- **CMS** (Sanity, Strapi, Contentful) - Data layer is cleanly separated
- **Database** (Firebase, Supabase) - Form submissions ready for API integration
- **Authentication** - Admin panel routes can be added
- **Payment Gateway** - Booking system ready for Stripe/PayPal
- **Multi-language** - i18n structure ready for Sinhala/English
- **Blog/News** - Component structure supports dynamic content
- **Admin Dashboard** - Modular components allow easy dashboard assembly

## SEO Features
- Semantic HTML structure
- Meta tags and Open Graph
- Alt text on all images
- Fast loading optimized
- Mobile-first responsive design

## License
Proprietary - WGSI SL
