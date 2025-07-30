# BDBT (Big Dose Big Tips) React Application

A comprehensive cold shower tracking Progressive Web App built with React, TypeScript, and Supabase.

## 🚀 Features

- **Cold Shower Tracking**: Track daily cold shower sessions with duration and temperature
- **Progressive Web App**: Install on mobile devices for native-like experience
- **User Authentication**: Secure login/signup with Supabase Auth
- **Tips System**: Browse and manage wellness tips database
- **Data Analytics**: Track progress and streaks over time
- **Responsive Design**: Works seamlessly on desktop and mobile
- **Dark/Light Theme**: Toggle between themes for better UX

## 🛠 Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, Framer Motion
- **Backend**: Supabase (Database, Auth, Storage)
- **PWA**: Service Worker, Web App Manifest
- **Deployment**: Vercel-ready configuration

## 📁 Project Structure

```
src/
├── components/          # React components
│   ├── auth/           # Authentication components
│   ├── features/       # Feature-specific components
│   ├── landing/        # Landing page components
│   ├── tips/           # Tips-related components
│   └── ui/             # Reusable UI components
├── hooks/              # Custom React hooks
├── lib/                # Utility libraries and Supabase client
├── pages/              # Page components
├── services/           # API services and business logic
├── styles/             # Design system and styles
├── types/              # TypeScript type definitions
└── utils/              # Utility functions
```

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Lordsisodia/bdbt-final-upload.git
   cd bdbt-final-upload
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env
   ```
   Fill in your Supabase credentials and other environment variables.

4. **Run development server**
   ```bash
   npm run dev
   ```

5. **Build for production**
   ```bash
   npm run build
   ```

## 🌐 Environment Variables

Required environment variables (see `.env.example`):
- `VITE_SUPABASE_URL`: Your Supabase project URL
- `VITE_SUPABASE_ANON_KEY`: Your Supabase anonymous key
- `VITE_GROK_API_KEY`: Grok API for AI features (optional)
- `VITE_CANVA_API_KEY`: Canva integration (optional)

## 🚀 Deployment

This app is configured for deployment on Vercel:

1. Connect your GitHub repository to Vercel
2. Set environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

## 📱 PWA Features

- Offline functionality with service worker
- Install prompt for mobile devices
- Push notifications support
- Background sync capabilities

## 🤝 Contributing

This is a production-ready React application with comprehensive features for cold shower tracking and wellness tips management.

## 📄 License

Built with React + TypeScript + Supabase

