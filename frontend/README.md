# ACDC PROS Frontend

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Create environment file
cp .env.example .env

# Start development server
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

## 📁 Structure

```
src/
├── pages/          # 12 page components
├── components/     # Reusable components
├── styles/         # CSS variables
├── App.jsx        # Main router
└── main.jsx       # Entry point
```

## 🎨 Features

- ✅ 12 fully functional pages
- ✅ CoachBot AI component
- ✅ Admin dashboard (email protected)
- ✅ Estimator tool
- ✅ Video session booking
- ✅ Membership tiers
- ✅ Emergency dispatch
- ✅ Responsive design

## 🔧 Build

```bash
# Development
npm run dev

# Production build
npm run build

# Preview production build
npm run preview

# Lint
npm run lint
```

## 🔌 API Integration

Update `src/pages/*` components to call backend endpoints:

- `GET /api/admin/stats` - Dashboard statistics
- `POST /api/estimates` - Generate estimates
- `GET /api/memberships` - Membership tiers
- `POST /api/sessions` - Book video sessions
- `POST /api/dispatch` - Emergency dispatch
- `GET /api/products` - Shop products

## 📚 Dependencies

- React 18.3.1
- React Router 7.12.0
- React Icons 5.5.0
- Vite 6.0.5

## 🐛 Troubleshooting

**Port already in use?**
```bash
npm run dev -- --port 3000
```

**Clear cache:**
```bash
rm -rf node_modules package-lock.json
npm install
```
