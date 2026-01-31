# 🍔 FoodExpress - Food & Grocery Delivery App

A modern, full-featured food and grocery delivery web application built with React, TypeScript, Vite, and Supabase.

![FoodExpress](https://images.unsplash.com/photo-1504674900247-0877df9cc836?w=1200&h=400&fit=crop)

## 🚀 Features

### Customer Features
- **🔐 User Authentication** - Secure login/signup with Supabase Auth
- **🍕 Restaurant Browsing** - Explore 500+ restaurants with filters
- **🛒 Grocery Shopping** - Shop fresh groceries from local stores
- **🛍️ Shopping Cart** - Add items, manage quantities, checkout
- **💳 Multiple Payment Options** - UPI, Card, Cash on Delivery
- **📦 Order Tracking** - Real-time order status updates
- **❤️ Favorites** - Save your favorite restaurants and dishes
- **👤 User Profile** - Manage account information
- **🌙 Dark/Light Theme** - Toggle between themes

### Business Features
- **🏪 Restaurant Dashboard** - Manage menu items and orders
- **🥬 Grocery Dashboard** - Manage inventory and orders
- **📊 Admin Panel** - Full administrative control

### New Pages Added
- **📄 About Page** - Company information, team, mission statement
- **📞 Contact Page** - Contact form and support options
- **👤 Profile Page** - User profile management

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui components
- **State Management**: React Context, TanStack Query
- **Backend**: Supabase (Auth, Database, Storage)
- **Routing**: React Router v6
- **Forms**: React Hook Form, Zod validation
- **Icons**: Lucide React

## 📋 Prerequisites

Before running this project, make sure you have:

- **Node.js** (v18 or higher) - [Download](https://nodejs.org/)
- **npm** (comes with Node.js) or **bun**
- A code editor (VS Code recommended)

## 🚀 How to Run

### Step 1: Clone/Download the Project

```bash
cd d:\food-express-login-system-main
```

### Step 2: Install Dependencies

```bash
npm install
```

Or if you prefer Bun:
```bash
bun install
```

### Step 3: Start the Development Server

```bash
npm run dev
```

### Step 4: Open in Browser

The app will be available at:
- **Local**: http://localhost:8080/
- **Network**: http://[your-ip]:8080/

## 📦 Build for Production

```bash
npm run build
```

The built files will be in the `dist` folder.

## 🔧 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run build:dev` | Build for development |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint |

## 📁 Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── auth/          # Authentication components
│   ├── cart/          # Shopping cart components
│   ├── layout/        # Layout components (Navbar, Footer)
│   ├── orders/        # Order-related components
│   └── ui/            # shadcn/ui components
├── data/              # Static data (restaurants, grocery)
├── hooks/             # Custom React hooks
├── integrations/      # External service integrations
│   └── supabase/      # Supabase client & types
├── lib/               # Utility functions
├── pages/             # Page components
│   ├── admin/         # Admin dashboard pages
│   ├── About.tsx      # About page
│   ├── Auth.tsx       # Login/Signup page
│   ├── Contact.tsx    # Contact page
│   ├── Dashboard.tsx  # User dashboard
│   ├── Favorites.tsx  # Favorites page
│   ├── Index.tsx      # Home page
│   ├── Menu.tsx       # Menu/Browse page
│   ├── Orders.tsx     # Orders page
│   ├── Payment.tsx    # Payment page
│   ├── Profile.tsx    # User profile page
│   └── ...
└── App.tsx            # Main app component
```

## 🔗 Routes

### Public Routes
| Route | Description |
|-------|-------------|
| `/` | Home page |
| `/auth` | Login/Signup |
| `/menu` | Browse restaurants & groceries |
| `/menu/:id` | Restaurant details |
| `/grocery/:id` | Grocery store details |
| `/about` | About us page |
| `/contact` | Contact page |

### Protected Routes (Login Required)
| Route | Description |
|-------|-------------|
| `/dashboard` | User dashboard |
| `/orders` | Order history |
| `/favorites` | Saved favorites |
| `/payment` | Checkout & payment |
| `/profile` | User profile |

### Admin Routes
| Route | Description |
|-------|-------------|
| `/admin` | Admin dashboard |
| `/admin/orders` | Manage orders |
| `/admin/users` | Manage users |
| `/admin/restaurants` | Manage restaurants |
| `/admin/grocery-stores` | Manage grocery stores |
| `/admin/analytics` | View analytics |
| `/admin/settings` | Admin settings |

## 🎨 Features in Detail

### 1. Restaurant Ordering
- Browse restaurants by cuisine
- View menus with images and prices
- Add items to cart
- Checkout with multiple payment options

### 2. Grocery Shopping
- Shop from local grocery stores
- Browse by category
- Fresh produce, dairy, and more

### 3. Order Management
- Track order status in real-time
- View order history
- Reorder favorite items

### 4. User Profile
- Update personal information
- View order statistics
- Manage preferences

### 5. Payment Options
- **UPI**: Scan QR code or enter UPI ID
- **Card**: Credit/Debit card payments
- **COD**: Cash on Delivery

## 🔐 Environment Variables

Create a `.env` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_anon_key
VITE_SUPABASE_PROJECT_ID=your_project_id
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License.

## 📞 Support

For support, email support@foodexpress.com or visit our [Contact Page](/contact).

---

Made with ❤️ by the FoodExpress Team
