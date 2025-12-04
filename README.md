# V Hair Vault Website

A modern, responsive e-commerce website for V Hair Vault, a premium wig and hair products retailer based in Johannesburg, South Africa.

## 📋 Project Overview

V Hair Vault Website is a single-page application showcasing three main product categories:
- Headband Wigs
- Textured Wigs
- Human-hair Wigs

The site features an integrated lay-by (installment) payment system and professional branding with a luxury aesthetic.

## 🎨 Design Features

- **Color Scheme**: Black, deep black, gold accents, and white
- **Typography**: Poppins font family for modern appearance
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices
- **Accessibility**: Semantic HTML and ARIA labels throughout

## 📁 Project Structure

```
├── index.html          # Main HTML file with all page sections
├── styles.css          # Custom styling and responsive design
└── README.md           # This file
```

### Image Assets Required

The following images should be placed in the project directory:
- `vhair-logo.png` - Company logo for header
- `vhair-image.jpg` - Hero section background image
- `DD-BrazilianHair.jpg` - Headband wigs product image
- `JC-HairWig.jpg` - Textured wigs product image
- `WW-Humanhair.jpg` - Human-hair wigs product image

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic web server to serve files (optional, for local development)

### Installation

1. Clone or download the project files
2. Ensure all image assets are in the project directory
3. Open `index.html` in your web browser

### Development Setup

For a better development experience, use a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js with http-server
npx http-server
```

Then navigate to `http://localhost:8000`

## 📑 Page Sections

### 1. **Header/Navigation**
- Logo branding
- Navigation menu (Home, About Us, Contact Us, Shop)
- "Lay-by Today" call-to-action button
- Responsive mobile menu

### 2. **About/Hero Section**
- Company story and mission
- Featured hero image
- "Learn More" button

### 3. **Products Section**
- Three product category cards
- Product images with smooth styling
- Responsive grid layout

### 4. **Lay-by Form Section**
- Overlay background with blur effect
- Email input
- Product name input
- Start date picker
- Duration (weeks) input
- Remember me checkbox
- Form submission button

### 5. **Footer**
- Social media links (Instagram, TikTok)
- Email contact link
- FAQ navigation
- Location information
- Copyright information

## 🎯 Key CSS Classes

| Class | Purpose |
|-------|---------|
| `.site-header` | Main navigation bar styling |
| `.btn-layby` | Lay-by button styling |
| `.product-card` | Product display cards |
| `.product-img` | Product images |
| `.layby-card` | Lay-by form container |
| `.form-control` | Form input styling |
| `.site-footer` | Footer section styling |

## 📱 Responsive Breakpoints

- **Tablets** (max-width: 992px): Center text, adjust product image heights
- **Large Mobile** (max-width: 768px): Stack navigation, reduce image heights
- **Phones** (max-width: 576px): Reduce product image heights, adjust form padding
- **Extra Small** (max-width: 400px): Reduce font size and image heights

## 🎨 CSS Variables

```css
--black: #000
--deep-black: #0d0d0d
--gold: #c9a856
--white: #ffffff
--soft-grey: #d1d1d1
```

## 🔗 External Dependencies

- **Bootstrap 5.3.8**: CSS framework for layout and components
- **Poppins Font**: Via system font fallback (ensure installed or use Google Fonts)

## 📝 Future Enhancements

- [ ] Add JavaScript for form validation and submission
- [ ] Implement product filtering
- [ ] Add shopping cart functionality
- [ ] Create individual product detail pages
- [ ] Add image lightbox gallery
- [ ] Integrate payment gateway for lay-by system
- [ ] Add email notification system
- [ ] Create admin dashboard for product management

## 🐛 Known Issues

- Lay-by form background image path needs to be verified: `vhair-image.jpg`
- Form currently has no backend validation or submission handler
- Missing logo image placeholder

## 📧 Contact & Social

- **Email**: vhairvault@gmail.com
- **Instagram**: [@vhair_vault](https://www.instagram.com/vhair_vault)
- **TikTok**: [@vhairvault](https://www.tiktok.com/@vhairvault)
- **Location**: Johannesburg, South Africa

## 📄 License

© 2025 V Hair Vault. All rights reserved.

## ✨ Credits

Designed and developed for V Hair Vault premium hair products.
