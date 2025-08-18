# 🏭 OSM - One Smart Mate Landing Page

Professional landing page for the OSM (One Smart Mate) industrial autonomous maintenance software, specialized in TPM, CILT, and OPL methodologies.

## ✨ Features

- **Modern Design**: Responsive landing page with scroll reveal animations
- **TPM Methodology**: Educational section about the 8 pillars of TPM
- **Advanced Technology**: Tailwind CSS with custom variables
- **Smooth Animations**: Appearance effects with Intersection Observer API
- **Optimized**: Performance optimized without affecting user experience

## 🚀 Technologies Used

- **HTML5** - Semantic structure
- **Tailwind CSS v4** - CSS framework with `@theme` variables
- **JavaScript ES6+** - Interactive functionalities
- **Inter Font** - Modern and readable typography
- **SVG Icons** - Scalable vector iconography

## 🛠️ Installation and Development

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Installation
```bash
# Clone the repository
git clone <your-repository>
cd .landingOSM

# Install dependencies
npm install

# Compile CSS (development)
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch

# Compile CSS (production)
npx tailwindcss -i ./src/input.css -o ./src/output.css --minify
```

### Local Development
```bash
# Start development server (optional)
npx serve .

# Or simply open index.html in the browser
```

## 🎨 Customization

### Primary Colors
Colors are defined in `src/input.css` using CSS variables:

```css
--color-primary: #4C5B91;
--color-primary-dark: #001E40;
--color-white: #ffffff;
```

### Fonts
- **Inter Variable Font**: Main font with complete accent support
- Configured for weights from 100 to 900

### Animations
- **Scroll Reveal**: Smooth appearance of sections when scrolling
- **Staggered Animations**: Staggered effects for multiple elements
- **Hover Effects**: Subtle interactions on buttons and cards

## 📱 Landing Page Sections

1. **Hero Section** - Impactful introduction
2. **Stats** - Key industry metrics
3. **Features** - 4 main process steps
4. **AM (Autonomous Maintenance)** - TPM methodology
5. **CILT** - Cleaning, Inspection, Lubrication, Tightening
6. **OPL** - One Point Lessons
7. **Benefits** - Industrial transformation
8. **Technology** - Real technical capabilities
9. **TPM Methodology** - The 8 pillars of TPM

## 🔧 Production Configuration

### Optimization
```bash
# Compile optimized CSS for production
npx tailwindcss -i ./src/input.css -o ./src/output.css --minify

# Check bundle size
ls -la src/output.css
```

## 📊 Performance

- **Lighthouse Score**: Optimized for performance
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🤝 Contributing

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

Developed with ❤️ to revolutionize industrial maintenance.
