# UnityBazzar - Shop Local, Shine Global 🇮🇳

A responsive MVP for an online shopping web application showcasing "Made in Bharat" products with a patriotic theme inspired by the Indian tricolour.

## 🎨 Design Philosophy

UnityBazzar combines modern e-commerce functionality with a distinctly Indian identity:
- **Colors**: Soft gradients of saffron, white, and green (Indian tricolour)
- **Theme**: Patriotism, Trust, and Simplicity
- **Typography**: Modern Poppins font family
- **Visual Identity**: Clean, professional, and approachable

## ✨ Features

### 🏠 Homepage
- Sticky header with logo and navigation
- Search bar with product search functionality
- Auto-playing banner carousel with promotional messages
- Product showcase sections:
  - 🔥 Top Deals
  - ⭐ Best Sellers
  - ✨ New Arrivals
- Responsive footer with "Made with ❤️ in Bharat" tagline

### 🛍️ Product Listing Page
- Grid layout with product cards
- Filter by category (Handicrafts, Textiles, Home Decor, Traditional Wear, Jewelry)
- Filter by price range
- Sort options (Popularity, Price, Rating, Newest)
- Real-time product count display
- Fully responsive sidebar filters

### 📦 Product Details Page
- Large product display with emoji icons
- Product information (name, category, price, rating)
- Detailed description
- "Add to Cart" and "Buy Now" buttons
- Related products section
- Breadcrumb navigation

### 🛒 Shopping Cart
- Display added products with images
- Quantity controls (increase/decrease)
- Remove item functionality
- Real-time total calculation
- Delivery charges calculation (Free above ₹999)
- Automatic discount (10% on orders above ₹2000)
- Empty cart state with CTA

### 💳 Checkout Page
- Simple delivery details form
  - Full Name
  - Mobile Number (10 digits)
  - Email Address
  - Complete Address
  - City & State
  - Pincode (6 digits)
  - Order Notes (optional)
- Order summary with item breakdown
- Payment info (100% secure, free delivery info)
- Success modal with order ID

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript**: No frameworks or libraries
- **LocalStorage**: Cart persistence
- **Font Awesome**: Icons
- **Google Fonts**: Poppins typography

## 📁 Project Structure

```
UnityBazzar/
│
├── index.html              # Homepage
├── products.html           # Product listing page
├── product-detail.html     # Individual product page
├── cart.html              # Shopping cart
├── checkout.html          # Checkout form
├── styles.css             # All styling (1000+ lines)
├── app.js                 # All JavaScript functionality
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Installation

No installation required! Simply open the files in a web browser.

1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **Start Shopping!** 🛍️

### Usage

```bash
# Option 1: Direct file open
# Simply double-click index.html

# Option 2: Use a local server (recommended)
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Then navigate to http://localhost:8000
```

## 🎯 Key Functionality

### Cart Management
- **Add to Cart**: Click "Add to Cart" on any product
- **Update Quantity**: Use +/- buttons in cart
- **Remove Items**: Click "Remove" button
- **Persistent Storage**: Cart saved in localStorage

### Search & Filter
- **Global Search**: Available on all pages, searches across product names, categories, and descriptions
- **Category Filter**: Multiple category selection
- **Price Range Filter**: Select price brackets
- **Sort Options**: Multiple sorting criteria

### Responsive Design
- **Desktop**: Full feature set with sidebar filters
- **Tablet**: Optimized grid layout
- **Mobile**: Hamburger menu, stacked layouts, hidden sidebar on products page

## 🎨 Color Palette

```css
/* Indian Tricolour Theme */
--saffron: #FF9933;
--saffron-light: #FFB366;
--saffron-pale: #FFECD9;
--white: #FFFFFF;
--off-white: #F9F9F9;
--green: #138808;
--green-light: #4CAF50;
--green-pale: #E8F5E9;
--navy: #000080;
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎁 Product Categories

1. **Handicrafts**: Traditional art and craft items
2. **Textiles**: Fabrics, sarees, and textiles
3. **Home Decor**: Decorative items for home
4. **Traditional Wear**: Ethnic clothing
5. **Jewelry**: Traditional jewelry pieces

## 💡 Features Highlights

### Shopping Experience
- 🎠 Auto-rotating carousel with 3 promotional slides
- 🔍 Real-time search functionality
- 🎨 Emoji-based product visuals (scalable and lightweight)
- 📱 Touch-friendly interface
- ⚡ Fast loading (no external dependencies beyond fonts/icons)

### Business Logic
- Free delivery on orders ≥ ₹999
- 10% discount on orders > ₹2000
- Form validation on checkout
- Order ID generation
- Success confirmation modal

## 🔄 State Management

Cart data is stored in browser's localStorage:
```javascript
localStorage.setItem('unityBazzarCart', JSON.stringify(cart));
```

This ensures cart persistence across page refreshes and browser sessions.

## 🎯 Future Enhancements

While this is an MVP, potential enhancements could include:
- User authentication
- Payment gateway integration
- Order tracking
- Wishlist functionality
- Product reviews and ratings
- Advanced filtering (size, color, material)
- Multi-language support
- Backend integration
- Admin panel

## 📄 License

This project is created for educational and demonstration purposes.

## 🙏 Credits

- **Design**: Custom design inspired by Indian heritage
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Google Fonts (Poppins)
- **Product Data**: Mock data representing authentic Indian products

## 🌟 Made with ❤️ in Bharat

UnityBazzar celebrates local artisans, traditional crafts, and the rich cultural heritage of India. Every product showcases the skill and dedication of Indian craftspeople.

---

**Note**: This is a frontend-only MVP. All product data is stored in JavaScript and cart data persists in localStorage. For production use, integrate with a proper backend and database system.
