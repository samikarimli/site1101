# Sami Karimli Portfolio - AI Coding Guidelines

## Architecture Overview
This is a static portfolio website built with vanilla HTML, CSS, and JavaScript. The main content is in `index.html` as a single-page application with anchor-linked sections. Separate pages (`about.html`, `projects.html`, `contact.html`) exist but are less developed.

## Key Patterns & Conventions
- **Theming**: Use CSS custom properties in `:root` for dark theme with gold accents (`--accent-color: #ffd700`)
- **Navigation**: Fixed header with smooth-scrolling anchor links; mobile hamburger menu toggles `.active` class on `.nav-menu`
- **Layout**: `.container` max-width 1200px with 20px padding; sections use full-width backgrounds
- **Animations**: IntersectionObserver triggers `.fade-in` class on scroll; keyframes for `fadeIn`, `slideInLeft`, `slideInRight`
- **Forms**: Contact form in `contact.html` and `#contact` section uses basic client-side validation with alerts (no backend)

## Development Workflow
- Edit HTML files directly; no build process required
- Test responsiveness by resizing browser or using dev tools
- Run locally by opening `index.html` in browser
- External dependencies: Google Fonts (Inter), Font Awesome icons

## Code Style Examples
- **CSS Classes**: Use semantic names like `.hero-content`, `.timeline-item`, `.skill-category`
- **JS Events**: Attach listeners for menu toggle, smooth scroll, form submit
- **Responsive**: Media queries for mobile (hamburger menu shows at smaller screens)
- **Accessibility**: Semantic HTML with proper headings, labels on form inputs

## Common Tasks
- Adding new sections: Create `<section id="new-section">` in `index.html`, add nav link, style in `styles.css`
- Updating content: Edit text directly in HTML; update dates in timeline items
- Styling: Modify CSS variables for theme changes; use `var(--variable)` throughout
- Scripts: Add functionality in `script.js`; observe new elements with IntersectionObserver if animated

## File Reference
- `css/styles.css`: All styling, ~800 lines with comprehensive responsive rules
- `js/script.js`: Interactive features including menu, scroll, form validation
- `portfolio-development-summary.md`: Development history and key snippets</content>
<parameter name="filePath">/Users/samikarimli/Desktop/site1101/.github/copilot-instructions.md