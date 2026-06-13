# SkillShift Frontend

Career Portal untuk Mahasiswa Indonesia - Frontend React.

## Tech Stack

- **React 19** + Vite
- **CSS Custom** (tanpa Tailwind)
- **Vercel** untuk deployment

## Setup

```bash
# Install dependencies
npm install

# Development
npm run dev

# Production build
npm run build
```

## Environment Variables

Buat file `.env` di root:

```env
VITE_API_URL=http://localhost:3001/api
```

Untuk production (Vercel), set di Vercel Dashboard:
```
VITE_API_URL=https://your-railway-url.up.railway.app/api
```

## Deploy ke Vercel

1. Push ke GitHub repo
2. Import di [vercel.com](https://vercel.com)
3. Set environment variable `VITE_API_URL`
4. Deploy!

## Struktur Folder

```
src/
├── App.jsx          # Main component
├── App.css          # Styles
├── main.jsx         # Entry point
├── index.css        # Global styles
└── components/
    └── LoginPage.jsx
```

## Akun Demo

- **Mahasiswa:** `mahasiswa@skillshift.com` / `123456`
- **Admin:** `admin@skillshift.com` / `admin123`
