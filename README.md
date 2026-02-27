# Scrapelytic Landing Page

A modern, responsive landing page built with HTML5 and TailwindCSS 4, replicating the Figma design pixel-perfectly.

## 🚀 Features

- **Fully Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **TailwindCSS 4** - Using the latest TailwindCSS via CDN
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Interactive Elements** - Hover effects, FAQ accordion, and smooth transitions
- **Font Awesome Icons** - Beautiful icons throughout the page
- **Optimized Performance** - Fast loading and smooth scrolling

## 📋 Sections Included

1. **Header/Navigation** - Logo, menu items, and CTA button
2. **Hero Section** - Main headline with compelling CTA and social proof
3. **Problem Statement** - 4 circular icons showcasing pain points
4. **Services Section** - 4 service cards (Lead Gen, Product Data, Research, Custom API)
5. **Data Collection** - Feature cards with benefits
6. **Social Proof** - Stats and customer testimonials
7. **Growth/Results** - Mixed layout showcasing key metrics
8. **FAQ Section** - Interactive accordion-style questions
9. **CTA Banner** - Sticky engagement banner
10. **Footer** - Links and company information

## 🎨 Design Elements

- **Color Palette**: 
  - Primary: Amber/Orange (#F59E0B, #FBBF24)
  - Background: Cream (#FFF9F0), White
  - Accents: Lime, Pink, Blue, Orange pastels
  
- **Typography**: Inter font family (Google Fonts)
- **Icons**: Font Awesome 6.5.1

## 🛠️ How to Use

### Option 1: Open Directly
Simply double-click `index.html` to open it in your default browser.

### Option 2: Use a Local Server (Recommended)
For the best experience, use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using PHP
php -S localhost:8000

# Using Node.js (http-server)
npx http-server -p 8000
```

Then visit: `http://localhost:8000`

## 🎯 Customization

### Update Images
Replace the Unsplash image URLs in the HTML with your own images:
- Service cards (Lines ~330-370)
- Testimonials (Lines ~490-550)
- Growth section (Lines ~620-680)

### Change Colors
The color scheme can be easily modified by updating the TailwindCSS classes:
- Primary color: `bg-amber-500`, `text-amber-600`
- Background: `bg-[#FFF9F0]`
- Accent colors: `bg-lime-300`, `bg-pink-300`, etc.

### Update Content
All text content is in plain HTML and can be edited directly in `index.html`.

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎭 Interactive Features

- **Service Cards**: Hover effects with image zoom and card lift
- **FAQ Accordion**: Click to expand/collapse answers
- **Smooth Transitions**: All interactive elements have smooth animations
- **Hover States**: Buttons and links have hover effects

## 🔧 Dependencies

All dependencies are loaded via CDN:
- TailwindCSS 4.x
- Font Awesome 6.5.1
- Google Fonts (Inter)

No build process or npm installation required!

## 📞 Support

For questions or issues, please contact the Scrapelytic team.

---

**Built with ❤️ using HTML5 & TailwindCSS 4**

