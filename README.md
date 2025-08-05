# ShopHub - Modern E-commerce Website Template

A beautiful, interactive e-commerce website template built with React, Node.js, and modern web technologies. Features smooth animations, responsive design, and a complete shopping experience.

## 🚀 Features

### Frontend (React)
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Interactive Components** - Animated product cards, cart management, and forms
- **State Management** - Context API for cart and authentication state
- **Routing** - React Router for seamless navigation
- **Animations** - Framer Motion for smooth, engaging animations
- **Styling** - Tailwind CSS for modern, utility-first styling

### Backend (Node.js/Express)
- **RESTful API** - Complete API endpoints for products, users, and orders
- **Authentication** - JWT-based authentication system
- **Product Management** - CRUD operations for products
- **Order Processing** - Complete checkout and order management
- **Error Handling** - Comprehensive error handling and validation

### Key Features
- 🛍️ **Product Catalog** - Browse products with filtering and sorting
- 🛒 **Shopping Cart** - Add, remove, and manage cart items
- 👤 **User Authentication** - Login and registration system
- 💳 **Checkout Process** - Complete payment and shipping forms
- ⭐ **Product Reviews** - Customer ratings and reviews
- 📱 **Mobile Responsive** - Optimized for all devices
- 🎨 **Beautiful Animations** - Smooth transitions and micro-interactions
- 🔍 **Search & Filter** - Advanced product search and filtering
- 📊 **Order Management** - Track orders and order history

## 🛠️ Technologies Used

### Frontend
- **React 18** - Modern React with hooks and context
- **React Router** - Client-side routing
- **Framer Motion** - Animation library
- **Tailwind CSS** - Utility-first CSS framework
- **Lucide React** - Beautiful icons
- **React Hot Toast** - Toast notifications
- **Axios** - HTTP client

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **CORS** - Cross-origin resource sharing
- **dotenv** - Environment variables

## 📦 Installation

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd ecommerce-template
   ```

2. **Install dependencies**
   ```bash
   # Install root dependencies
   npm install
   
   # Install client dependencies
   cd client
   npm install
   cd ..
   ```

3. **Environment Setup**
   ```bash
   # Create .env file in root directory
   touch .env
   ```
   
   Add the following to your `.env` file:
   ```
   PORT=5000
   NODE_ENV=development
   ```

4. **Start the development servers**
   ```bash
   # Start both frontend and backend (from root directory)
   npm run dev
   
   # Or start them separately:
   # Backend only
   npm run server
   
   # Frontend only
   cd client && npm start
   ```

5. **Access the application**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## 🏗️ Project Structure

```
ecommerce-template/
├── client/                 # React frontend
│   ├── public/            # Static files
│   ├── src/
│   │   ├── components/    # Reusable components
│   │   ├── context/       # React context providers
│   │   ├── pages/         # Page components
│   │   ├── App.js         # Main app component
│   │   └── index.js       # Entry point
│   ├── package.json
│   └── tailwind.config.js
├── server/                # Node.js backend
│   └── index.js          # Express server
├── package.json           # Root package.json
└── README.md
```

## 🎯 Available Scripts

### Root Directory
- `npm run dev` - Start both frontend and backend
- `npm run server` - Start backend server only
- `npm run client` - Start frontend only
- `npm run build` - Build frontend for production
- `npm run install-all` - Install all dependencies

### Client Directory
- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run tests
- `npm run eject` - Eject from Create React App

## 🚀 Deployment

### Frontend Deployment
1. Build the React app:
   ```bash
   cd client
   npm run build
   ```

2. Deploy the `build` folder to your hosting service (Netlify, Vercel, etc.)

### Backend Deployment
1. Deploy the `server` folder to your hosting service (Heroku, Railway, etc.)
2. Set environment variables in your hosting platform
3. Update the API base URL in the frontend

## 📱 Features Overview

### Home Page
- Hero section with call-to-action
- Featured products showcase
- Category browsing
- Trust indicators and features

### Products Page
- Product grid with filtering
- Search functionality
- Sort by price, rating, name
- Grid/list view toggle
- Product cards with hover effects

### Product Detail Page
- Image gallery with thumbnails
- Product information and specifications
- Customer reviews
- Add to cart functionality
- Related products

### Shopping Cart
- Cart item management
- Quantity controls
- Price calculations
- Order summary
- Checkout process

### User Authentication
- Login and registration forms
- Form validation
- Password visibility toggle
- Remember me functionality

### Checkout Process
- Shipping information form
- Payment form
- Order summary
- Secure checkout indicators

## 🎨 Design Features

### Animations
- Page transitions
- Hover effects on buttons and cards
- Loading animations
- Smooth scrolling
- Micro-interactions

### Responsive Design
- Mobile-first approach
- Tablet and desktop optimizations
- Flexible grid layouts
- Touch-friendly interactions

### Color Scheme
- Primary: Blue (#0ea5e9)
- Secondary: Purple (#d946ef)
- Neutral grays for text and backgrounds
- Success/error states

## 🔧 Customization

### Styling
- Modify `tailwind.config.js` for theme changes
- Update colors in the config file
- Custom animations in `src/index.css`

### Content
- Update product data in `server/index.js`
- Modify images and descriptions
- Add new categories and features

### Functionality
- Extend API endpoints in `server/index.js`
- Add new React components
- Implement additional features

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Unsplash for product images
- Lucide for beautiful icons
- Framer Motion for animations
- Tailwind CSS for styling utilities

## 📞 Support

For support or questions, please open an issue in the repository.

---

**Built with ❤️ using React, Node.js, and modern web technologies** 