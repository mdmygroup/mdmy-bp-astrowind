# Bizot Paysagistes - Astro Website

This project has been migrated from vanilla HTML to Astro framework following modern web development best practices.

## 🚀 Project Structure

```
/
├── public/
│   └── assets/          # Static assets (images, logos, etc.)
├── src/
│   ├── components/      # Reusable Astro components
│   │   ├── Header.astro
│   │   └── Footer.astro
│   ├── layouts/         # Layout templates
│   │   └── BaseLayout.astro
│   └── pages/           # Page routes
│       ├── index.astro
│       ├── services.astro
│       ├── realisations.astro
│       ├── a-propos.astro
│       └── contact.astro
├── astro.config.mjs     # Astro configuration
├── tailwind.config.mjs  # Tailwind CSS configuration
└── package.json         # Project dependencies
```

## 🛠️ Installation & Setup

1. **Install Node.js** (if not already installed):
   - Download from https://nodejs.org/ (LTS version recommended)
   - Or use Homebrew: `brew install node`

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start development server**:
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:4321`

4. **Build for production**:
   ```bash
   npm run build
   ```
   The static site will be generated in `dist/` folder

5. **Preview production build**:
   ```bash
   npm run preview
   ```

## 📝 Migration Status

### ✅ Completed
- ✅ Astro project structure created
- ✅ Tailwind CSS integration configured
- ✅ BaseLayout with SEO meta tags
- ✅ Header component with navigation
- ✅ Footer component
- ✅ All page routes created (index, services, realisations, a-propos, contact)
- ✅ Assets moved to public folder
- ✅ AOS (Animate On Scroll) integration
- ✅ Alpine.js integration for interactivity

### 🔄 To Complete
The current pages have the basic structure but need the full content from the original HTML files. To complete:

1. **Expand index.astro**: Add all sections from `index.html`:
   - Google Reviews section
   - Services section
   - Portfolio section
   - About section
   - Newsletter section

2. **Expand services.astro**: Add all service detail sections
3. **Expand realisations.astro**: Add portfolio grid with filters
4. **Expand a-propos.astro**: Add story, values, team sections
5. **Expand contact.astro**: Add contact form and FAQ

## 🎨 Tech Stack

- **Framework**: Astro 4.x
- **Styling**: Tailwind CSS 3.4
- **Interactivity**: Alpine.js (for dropdowns, modals)
- **Animations**: AOS (Animate On Scroll)
- **Icons**: Heroicons (inline SVG)
- **Fonts**: Google Fonts (Inter)

## 🎯 Key Features

### Astro Benefits
- ⚡ **Zero JS by default**: Ships minimal JavaScript to the client
- 🔧 **Component-based**: Reusable Header, Footer, and Layout components
- 📦 **Static Site Generation**: Fast load times and great SEO
- 🎨 **Tailwind Integration**: Utility-first CSS with custom theme
- 🔄 **Hot Module Replacement**: Instant updates during development

### Design System
Custom Tailwind theme with brand colors:
- `brand`: #80ab97 (main green)
- `brandLight`: #cbecdd (light green)
- `brandDark`: #386D56 (dark green)
- `accent`: #F97316 (orange)
- `textColor`: #102611 (dark text)
- `bgColor`: #FFFFFF (background)

## 📂 Next Steps

1. **Complete page content**: Copy remaining sections from original HTML files
2. **Create reusable components**: Extract repeated patterns (service cards, project cards, etc.)
3. **Add image optimization**: Use Astro's Image component for better performance
4. **Test responsiveness**: Verify all pages work on mobile, tablet, desktop
5. **Set up deployment**: Configure hosting (Netlify, Vercel, etc.)

## 🔧 Development Tips

- Use `src/components/` for reusable UI elements
- Use `src/layouts/` for page templates
- Use `src/pages/` for routes (file-based routing)
- Static assets go in `public/` (accessible at `/assets/...`)
- Use Astro props for component customization

## 📖 Documentation

- [Astro Documentation](https://docs.astro.build)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [Alpine.js](https://alpinejs.dev)
- [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)

## 🤝 Contributing

To continue development:
1. Complete the page content from original HTML
2. Extract repeated sections into components
3. Add responsive images
4. Test across browsers
5. Optimize for performance

---

**Made with ❤️ using Astro + Tailwind CSS**
