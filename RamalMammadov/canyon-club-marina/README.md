# Canyon Club Resort Marina Website

A professional, responsive website for Canyon Club Resort Marina - Cape May's Premier Full-Service Boating Facility.

## 🌊 About

Canyon Club Resort Marina is located at 900 Ocean Drive, Cape May, NJ 08204. This website showcases our marina services, amenities, and provides information for boaters and visitors.

## 🚀 Features

### Design & Layout
- **Nautical/Coastal Theme** - Professional maritime design with ocean-inspired colors
- **Responsive Design** - Mobile-first approach, works perfectly on all devices
- **Modern UI/UX** - Clean, elegant interface with smooth animations
- **Accessibility** - WCAG compliant with proper ARIA labels and semantic HTML

### Color Palette
- Deep Navy Blue: `#002b45`
- Ocean Turquoise: `#008c9e`
- White: `#ffffff`
- Sandy Beige: `#f6f1e7`
- Accent Yellow: `#ffd700`

### Sections & Pages
1. **Home** - Hero section with call-to-action
2. **About** - Marina introduction and overview
3. **Marina & Amenities** - Services and facilities
4. **Fishing** - Fishing information and tournaments
5. **Service Center** - Mechanical, fiberglass, carpentry, parts
6. **Ship's Store** - Retail store with premium brands
7. **Events** - Seasonal events and celebrations
8. **Contact & Location** - Contact form and Google Maps integration

### Interactive Features
- **Sticky Navigation** - Fixed header with smooth scrolling
- **Mobile Menu** - Hamburger menu for mobile devices
- **Auto-scrolling Manufacturers** - Infinite loop logo carousel
- **Service Tabs** - Interactive tab system for service center
- **Store Carousel** - Image carousel for ship's store
- **Contact Form** - Functional contact form with validation
- **Scroll Animations** - Intersection Observer for smooth animations
- **Scroll to Top** - Floating button for easy navigation

## 🛠️ Technology Stack

- **HTML5** - Semantic markup with accessibility features
- **CSS3** - Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Font Awesome** - Icons for UI elements
- **Google Fonts** - Poppins font family
- **Google Maps** - Embedded map for location

## 📁 Project Structure

```
canyon-club-marina/
├── index.html              # Main HTML file
├── styles/
│   ├── main.css           # Main stylesheet
│   └── responsive.css     # Responsive design rules
├── scripts/
│   └── main.js           # JavaScript functionality
├── images/
│   ├── README.md         # Image specifications
│   ├── hero-marina.jpg   # Hero banner image
│   ├── about-marina.jpg  # About section image
│   ├── logo1.jpg         # Manufacturer logos (1-11)
│   ├── fishing-boat.jpg  # Fishing section image
│   ├── service1.jpg      # Service center images
│   ├── parts-department.jpg
│   ├── fiberglass-work.jpg
│   ├── event1.jpg        # Event images
│   ├── event2.jpg
│   ├── store1.jpg        # Ship's store images
│   └── store2.jpg
└── README.md             # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **For Development**: Use a local server like Live Server (VS Code extension)

### Local Development Server

Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Using Node.js:
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile Large**: 576px - 767px
- **Mobile Small**: 375px - 575px
- **Extra Small**: Below 375px

## 🎨 Customization

### Colors
Edit CSS custom properties in `styles/main.css`:
```css
:root {
    --navy-blue: #002b45;
    --ocean-turquoise: #008c9e;
    --white: #ffffff;
    --sandy-beige: #f6f1e7;
    --accent-yellow: #ffd700;
}
```

### Content
- Update text content in `index.html`
- Replace placeholder images in `images/` folder
- Modify contact information and links

### Styling
- Main styles: `styles/main.css`
- Responsive rules: `styles/responsive.css`
- JavaScript functionality: `scripts/main.js`

## 📸 Image Requirements

### Required Images
- **Hero Banner**: 1920x1080px (hero-marina.jpg)
- **About Section**: 800x600px (about-marina.jpg)
- **Manufacturer Logos**: 200x100px each (logo1.jpg to logo11.jpg)
- **Section Images**: 600x400px to 800x600px

### Image Sources
- Use high-quality, professional photos
- Ensure proper licensing for commercial use
- Optimize for web (compress appropriately)
- Add descriptive alt text for accessibility

## 🔧 Features in Detail

### Navigation
- Sticky header with backdrop blur
- Smooth scrolling to sections
- Mobile hamburger menu
- Active state indicators

### Animations
- Intersection Observer for scroll animations
- CSS transitions and transforms
- Auto-scrolling manufacturer logos
- Fade-in effects for content

### Forms
- Contact form with validation
- Email format checking
- Success/error notifications
- Form reset after submission

### Performance
- Lazy loading for images
- Debounced scroll events
- Optimized animations
- Minimal JavaScript footprint

## 🌐 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 SEO Features

- Semantic HTML structure
- Meta tags for title, description, keywords
- Proper heading hierarchy
- Alt text for images
- Clean URL structure
- Fast loading times

## ♿ Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- Screen reader friendly
- High contrast ratios
- Focus indicators
- Reduced motion support

## 📞 Contact Information

**Canyon Club Resort Marina**
- Address: 900 Ocean Drive, Cape May, NJ 08204
- Phone: (609) 884-0195
- Email: info@canyonclubmarina.com

## 🔗 External Links

- **Tournaments**: [South Jersey Tournaments](https://southjerseytournaments.com/)
- **Weather**: [Weather Forecast](https://weather.com)
- **Marina Network**: [South Jersey Marina](https://southjerseymarina.com)
- **Dining**: [SaltWater Cafe](https://saltwatercafe.com)

## 📄 License

This project is created for Canyon Club Resort Marina. All rights reserved.

## 🤝 Contributing

For updates or modifications:
1. Review the existing code structure
2. Follow the established naming conventions
3. Test on multiple devices and browsers
4. Ensure accessibility compliance
5. Optimize for performance

## 📞 Support

For technical support or questions about the website, please contact the development team or refer to the documentation in this README.

---

**Built with ❤️ for Canyon Club Resort Marina** 