# 🍵 Tea House - Premium Tea Experience

A modern, responsive landing page for a premium tea house, featuring elegant design, smooth animations, and an intuitive user interface.

![Tea House Banner](./images/banner.png)

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, contemporary design with smooth animations and transitions
- **Sticky Navigation**: Glass-morphism navigation bar that stays accessible while scrolling
- **Interactive Elements**: Hover effects, animated cards, and dynamic button states
- **Product Showcase**: Beautiful grid layout displaying featured tea products with pricing
- **Customer Testimonials**: Eye-catching review section with layered card design
- **Newsletter Integration**: Email subscription form in the footer
- **Social Media Links**: Quick access to social platforms

## 🎨 Design Highlights

### Visual Elements

- Gradient text effects for headings
- Floating animations on hero image
- Product cards with lift-on-hover effects
- Glass-morphism effects for modern aesthetics
- Smooth fade-in animations for sections

### Color Palette

- Primary: Orange (#f97316) to Red (#ef4444) gradients
- Background: Soft orange tones (#fff7ed) to white
- Text: Gray scale for optimal readability

### Typography

- Font Family: Manrope (Google Fonts)
- Weight Range: 200-800 for varied emphasis

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS (for customization)

### Installation

1. **Clone or Download** the repository:

   ```bash
   git clone https://github.com/yourusername/tea-house.git
   ```

2. **Navigate** to the project directory:

   ```bash
   cd tea-house
   ```

3. **Open** `index.html` in your browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser

### Project Structure

```
tea-house/
│
├── index.html           # Main HTML file
├── README.md           # Project documentation
│
└── images/             # Image assets
    ├── banner.png      # Hero section image
    ├── cup.png         # Logo image
    ├── tea-1.png       # Milk tea product
    ├── tea-2.png       # Black tea product
    ├── tea-3.png       # Green tea product
    ├── tea-4.png       # Lemon tea product
    ├── fresh-1.png     # Fresh tea image 1
    ├── fresh-2.png     # Fresh tea image 2
    └── client.png      # Client testimonial avatar
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom animations and transitions
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Manrope font family

## 📱 Sections

### 1. Navigation Bar

- Sticky positioning with glass-morphism effect
- Logo and brand name
- Quick links to all sections
- Mobile-responsive hamburger menu

### 2. Hero Section

- Eye-catching headline with gradient text
- Call-to-action button with hover effects
- Floating tea cup animation
- Trust Pilot rating badge

### 3. Featured Products

- Grid layout showcasing 4 tea varieties
- Individual product cards with:
  - Product image
  - Name and description
  - Pricing information
  - Add to Cart button

### 4. About Section

- Image gallery with gradient backgrounds
- Brand story and values
- Feature highlights with icons

### 5. Testimonials

- Gradient background section
- Layered review cards with hover effects
- Customer ratings and feedback

### 6. Footer

- Call-to-action banner
- Quick links organized in columns
- Newsletter subscription form
- Social media links
- Copyright information

## 🎯 Customization

### Changing Colors

Update the gradient colors in the `<style>` section:

```css
.gradient-text {
  background: linear-gradient(135deg, #your-color-1, #your-color-2);
}
```

### Modifying Products

Edit the product cards in the HTML:

```html
<div class="product-card ...">
  <h3>Your Tea Name</h3>
  <p>Your description</p>
  <span>$X.XX</span>
</div>
```

### Adjusting Animations

Modify animation keyframes in the `<style>` section:

```css
@keyframes yourAnimation {
  from {
    /* start state */
  }
  to {
    /* end state */
  }
}
```

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 🔧 Performance Optimization

- Utilizes CDN for external libraries
- Optimized image loading
- Minimal custom CSS for faster load times
- Lazy loading for animations

## 📋 TODO / Future Enhancements

### High Priority

- [ ] **Shopping Cart Functionality**: Implement a working cart system with add/remove items
- [ ] **Product Detail Pages**: Create individual pages for each tea product
- [ ] **Backend Integration**: Connect to a database for dynamic product management
- [ ] **Payment Gateway**: Integrate Stripe or PayPal for checkout
- [ ] **User Authentication**: Add login/signup functionality for customers
- [ ] **Order Tracking**: Allow customers to track their orders

### Medium Priority

- [ ] **Search Functionality**: Add search bar to find products quickly
- [ ] **Product Filtering**: Filter by price, type, rating, etc.
- [ ] **Wishlist Feature**: Let users save favorite products
- [ ] **Product Reviews**: Enable customers to leave detailed reviews
- [ ] **Blog Section**: Add tea-related articles and brewing guides
- [ ] **Multi-language Support**: Internationalization (i18n) for global reach
- [ ] **Dark Mode**: Implement theme toggle for better accessibility
- [ ] **Live Chat Support**: Add customer service chat widget

### Low Priority

- [ ] **Animations Enhancement**: Add scroll-triggered animations with libraries like AOS
- [ ] **Product Comparison**: Compare multiple teas side-by-side
- [ ] **Loyalty Program**: Reward system for repeat customers
- [ ] **Gift Cards**: Digital gift card purchase and redemption
- [ ] **Tea Quiz**: Interactive quiz to recommend teas based on preferences
- [ ] **Virtual Tea Tasting**: AR/VR experience for product visualization
- [ ] **Subscription Box**: Monthly tea subscription service
- [ ] **Mobile App**: Native iOS/Android applications

### Technical Improvements

- [ ] **SEO Optimization**: Add meta tags, structured data, and sitemap
- [ ] **Accessibility (a11y)**: WCAG 2.1 compliance for screen readers
- [ ] **Progressive Web App (PWA)**: Make site installable and work offline
- [ ] **Image Optimization**: WebP format and responsive images
- [ ] **Analytics Integration**: Google Analytics or similar tracking
- [ ] **Performance Monitoring**: Lighthouse score optimization
- [ ] **Unit Testing**: Add test coverage for JavaScript functionality
- [ ] **CI/CD Pipeline**: Automated deployment workflow

### Content Additions

- [ ] **FAQ Section**: Frequently asked questions about products and shipping
- [ ] **About Us Page**: Detailed company history and mission
- [ ] **Contact Form**: Direct communication with customer support
- [ ] **Store Locator**: Map showing physical store locations
- [ ] **Press/Media Kit**: Resources for journalists and partners
- [ ] **Sustainability Page**: Environmental initiatives and commitments

## 👥 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or feedback, please reach out:

- **Email**: md.sazzadul.islam15@gmail.com

## 🙏 Acknowledgments

- Design inspiration from modern e-commerce websites
- Icons provided by Font Awesome
- Typography by Google Fonts
- Built with love for tea enthusiasts ☕

---

**Made with ♥ for tea lovers everywhere**

_Last updated: December 2025_
