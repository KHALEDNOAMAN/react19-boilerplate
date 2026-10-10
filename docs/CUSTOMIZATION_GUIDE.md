# React 19 Boilerplate - Customization Guide

## What You Get
| Technology | Version | Purpose |
|-----------|---------|---------|
| React | 19 | UI Framework |
| Next.js | 15 | SSR + Routing |
| Tailwind CSS | 4 | Styling |
| Motion | Latest | Animations |

## Quick Start
```bash
npx create-next-app -e https://github.com/seckinyasar/react19-boilerplate
cd my-app
npm run dev
```

## Customization

### Adding Pages
Create files in `app/` directory. Next.js 15 uses App Router by default.

### Theme Configuration
Edit `tailwind.config.ts` to customize colors, fonts, breakpoints.

### Adding Authentication
This boilerplate pairs with the OAuth boilerplate for auth.

### Environment Variables
| Variable | Required | Description |
|----------|----------|-------------|
| NEXT_PUBLIC_API_URL | Yes | Backend API URL |
| DATABASE_URL | Optional | DB connection string |

## Project Structure
- app/ - Pages and layouts
- components/ - Reusable UI components
- lib/ - Utilities and helpers
- public/ - Static assets