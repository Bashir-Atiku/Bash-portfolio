# Bashir Atiku - Computer Engineering Portfolio

A professional, modern portfolio website for Bashir Atiku, a 500-level Computer Engineering student at Ahmadu Bello University, Zaria, with a focus on Control Engineering and Automation.

## 📋 Features

### Pages
- **Home** - Welcome page with hero section and key highlights
- **About** - Educational background, personal journey, and areas of focus
- **Skills** - Technical skills in programming, computer engineering, control systems, and more
- **Projects** - Showcase of engineering projects and work
- **Contact** - Contact form and connection information

### Design Features
✅ Fully Responsive Design (Mobile, Tablet, Desktop)
✅ Modern, Professional UI with smooth animations
✅ Interactive Navigation with Hamburger Menu
✅ Scroll Animations and Effects
✅ Contact Form with Validation
✅ Social Media Links
✅ Progress Bars for Skills
✅ Timeline for Education
✅ Project Cards with Tags
✅ Professional Color Scheme

## 🎨 Color Scheme
- **Primary Color**: #2563eb (Blue)
- **Secondary Color**: #10b981 (Green)
- **Accent Color**: #f59e0b (Amber)
- **Text Dark**: #1f2937
- **Background Light**: #f9fafb

## 📁 File Structure

```
Bash portfolio/
├── index.html          # Home page
├── about.html          # About page
├── skills.html         # Skills page
├── projects.html       # Projects page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet (responsive)
├── script.js           # JavaScript interactivity
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Open Directly
Simply double-click `index.html` in the file explorer to open the portfolio in your default browser.

### Option 2: Using VS Code
1. Open the folder in VS Code
2. Install the "Live Server" extension (if you want live reloading)
3. Right-click on `index.html` and select "Open with Live Server"

### Option 3: Using Python (Simple HTTP Server)
Open command prompt/terminal in the portfolio folder and run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ⌨️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables and Grid/Flexbox
- **JavaScript (Vanilla)** - No external dependencies, pure JS
- **Font Awesome** - Icons (via CDN)
- **Responsive Design** - Mobile-first approach

## 🔧 Customization Guide

### Update Contact Information
Edit `contact.html` - Replace placeholder contact details:
```html
<p><a href="mailto:bashir.atiku@example.com">bashir.atiku@example.com</a></p>
<p><a href="tel:+2348XXXXXXXXX">+234 8XX XXXX XXX</a></p>
```

### Update Social Media Links
Find social media links throughout the HTML files and replace `href="#"` with actual profiles:
```html
<a href="https://linkedin.com/in/bashir-atiku" class="social-link">
<a href="https://github.com/bashir-atiku" class="social-link">
<a href="https://twitter.com/bashir_atiku" class="social-link">
```

### Add Personal Photo
Add an image file to the folder and update the `about.html`:
```html
<div class="about-image">
    <img src="your-photo.jpg" alt="Bashir Atiku" style="width: 250px; border-radius: 12px;">
</div>
```

### Change Color Scheme
Edit `styles.css` CSS variables at the top:
```css
:root {
    --primary-color: #2563eb;      /* Change to your color */
    --secondary-color: #10b981;
    --accent-color: #f59e0b;
    /* ... other colors */
}
```

### Add More Projects
Edit `projects.html` and duplicate the `.project-card` div:
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Description...</p>
        <!-- Add more content -->
    </div>
</div>
```

## 📊 Features Breakdown

### Navigation
- Sticky navbar that stays visible while scrolling
- Mobile hamburger menu
- Active page indicator
- Smooth scrolling

### Hero Section
- Eye-catching welcome message
- Call-to-action buttons
- Gradient background

### Sections
- **About**: Timeline of education with expandable details
- **Skills**: Organized skill cards with progress bars
- **Projects**: Project showcase with tags and descriptions
- **Contact**: Contact form with validation and info cards

### Forms
- Client-side form validation
- Visual feedback for errors/success
- Required field validation
- Email format checking

### Animations
- Scroll-triggered animations
- Hover effects on cards
- Smooth transitions
- Progress bar fill animations

## 🔗 Social Media Integration

Update social links in all pages:
1. LinkedIn: `https://linkedin.com/in/[your-profile]`
2. GitHub: `https://github.com/[your-username]`
3. Twitter: `https://twitter.com/[your-handle]`

## ✨ Best Practices Implemented

✅ Semantic HTML5
✅ Mobile-first responsive design
✅ CSS Grid and Flexbox layouts
✅ CSS Variables for easy theming
✅ Minimal JavaScript (no dependencies)
✅ Accessibility considerations
✅ Cross-browser compatibility
✅ Fast loading and performance optimized
✅ SEO-friendly structure
✅ Progressive enhancement

## 🌟 Future Enhancements

Potential additions to make it even better:
- Backend contact form (send emails)
- Blog section
- Photo gallery
- PDF CV download
- Dark mode toggle
- Multi-language support
- Search functionality
- Comments system

## 📞 Contact & Support

For updates or customizations, refer to the contact page or reach out through:
- Email: bashiratiku5@gmail.com
- LinkedIn: [Your LinkedIn]
- GitHub: [@bashir-atiku]

## 📄 License

This portfolio template is free to use and modify for personal use.

---


*Computer Engineering | Control Engineering | Technology | Innovation*
