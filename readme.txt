# 🥗 Foodmart - Food E-commerce Website

A responsive food e-commerce website built with HTML, CSS, JavaScript, and Bootstrap, featuring a modern design and smooth user experience.

![Foodmart Preview](https://foodmart-demo.netlify.app/assets/images/preview.png)

## 🚀 Live Demo

[View Live Site](https://foodmart-demo.netlify.app)

## 💻 Technologies Used

- **HTML5**
  - Semantic markup
  - SEO optimized structure
  - Accessibility features

- **CSS3**
  - Custom variables
  - Flexbox & Grid layouts
  - Media queries
  - Animations & transitions
  - SCSS preprocessing

- **JavaScript**
  - ES6+ features
  - DOM manipulation
  - Event handling
  - Local storage
  - Form validation
  - Cart functionality

- **Bootstrap 5**
  - Responsive grid system
  - Navigation components
  - Cards & modals
  - Form elements
  - Utility classes

## ✨ Features

- **Responsive Design**
  - Mobile-first approach
  - Cross-browser compatibility
  - Tablet & desktop optimized

- **User Interface**
  - Dynamic navigation menu
  - Product filtering
  - Shopping cart
  - Image gallery
  - Product quick view
  - Custom animations

- **Shopping Features**
  - Add to cart functionality
  - Quantity adjustment
  - Price calculation
  - Order summary
  - Checkout process

## 📁 Project Structure

```
foodmart/
├── assets/
│   ├── images/          # Image files
│   ├── css/            # CSS files
│   │   ├── style.css   # Main styles
│   │   └── custom.css  # Custom styles
│   └── js/             # JavaScript files
│       ├── main.js     # Main functionality
│       └── cart.js     # Cart functions
├── vendor/             # Third-party libraries
│   └── bootstrap/      # Bootstrap files
├── index.html          # Home page
├── products.html       # Products page
├── cart.html          # Shopping cart
└── checkout.html      # Checkout page
```

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/anasraheemdev/Foodmart

# Navigate to project directory
cd Foodmart

# Open with live server
# or simply open index.html in your browser
```

## 📱 Pages & Components

### Home Page
- Hero section with slider
- Featured products
- Categories showcase
- Special offers
- Newsletter signup

### Products Page
- Filter sidebar
- Product grid
- Quick view modals
- Add to cart buttons
- Pagination

### Shopping Cart
- Product list
- Quantity controls
- Price calculations
- Checkout button

### Checkout
- Form validation
- Order summary
- Payment options

## 🎨 Styling Guide

### Colors
```css
:root {
  --primary-color: #ff6b6b;
  --secondary-color: #4ecdc4;
  --dark-color: #2d3436;
  --light-color: #f8f9fa;
  --success-color: #6c5ce7;
}
```

### Typography
- Primary Font: 'Poppins', sans-serif
- Secondary Font: 'Open Sans', sans-serif
- Headings: 'Playfair Display', serif

### Bootstrap Customization
```scss
// Custom Bootstrap variables
$theme-colors: (
  "primary": #ff6b6b,
  "secondary": #4ecdc4,
  "success": #6c5ce7
);
```

## 🔧 JavaScript Features

### Cart Functionality
```javascript
// Add to cart
function addToCart(productId) {
  // Cart logic here
}

// Update quantity
function updateQuantity(productId, quantity) {
  // Quantity update logic
}

// Calculate total
function calculateTotal() {
  // Total calculation logic
}
```

### Form Validation
```javascript
// Validate form
function validateForm() {
  // Form validation logic
}

// Handle submission
function handleSubmit(event) {
  // Submit handling logic
}
```

## 📱 Responsive Breakpoints

```css
/* Small devices (phones) */
@media (min-width: 576px) { ... }

/* Medium devices (tablets) */
@media (min-width: 768px) { ... }

/* Large devices (desktops) */
@media (min-width: 992px) { ... }

/* Extra large devices */
@media (min-width: 1200px) { ... }
```

## 🚀 Performance Optimization

- Minified CSS and JavaScript
- Optimized images
- Lazy loading implementation
- Browser caching
- Gzip compression

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👨‍💻 Author

Anas Raheem
- GitHub: [@anasraheemdev](https://github.com/anasraheemdev)
- LinkedIn: [Anas Raheem](https://linkedin.com/in/anasraheem)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

⭐ Star this repo if you found it helpful!
