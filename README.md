# 🚀 QYVENOX

**Build the Impossible.**

QYVENOX is an all-in-one AI platform designed to empower everyone to create, learn, automate, and develop their projects with powerful and easy-to-use artificial intelligence.

## Vision

To become a global reference in AI-assisted creation tools.

## What Users Can Do

- 💬 Chat with advanced AI
- 🎨 Generate images
- 🎥 Create videos
- 🌐 Build websites
- 🎵 Generate music
- 🎙️ Clone voices
- 📝 Write content
- 💼 Create CVs
- 📊 Generate presentations
- 💻 Write code
- 📱 Design applications
- 📈 Develop their business

## Tech Stack

### Frontend
- **Framework**: React 18 + TypeScript
- **Styling**: Tailwind CSS
- **State Management**: Zustand
- **HTTP Client**: Axios
- **Build Tool**: Vite

### Backend
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: PostgreSQL
- **ORM**: Prisma
- **Authentication**: JWT + OAuth2
- **API Integration**: OpenAI, Stability AI, etc.

### Deployment
- **Frontend**: Vercel
- **Backend**: Railway/Render
- **Database**: Railway/Heroku
- **Storage**: AWS S3 / Supabase Storage

## Project Structure

```
qyvenox/
├── client/                 # Frontend (React)
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── store/
│   │   └── App.tsx
│   └── package.json
├── server/                 # Backend (Node.js)
│   ├── src/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── services/
│   │   ├── middleware/
│   │   ├── database/
│   │   └── index.ts
│   └── package.json
├── shared/                 # Shared types/utils
└── package.json
```

## Getting Started

### Prerequisites
- Node.js 18+
- PostgreSQL
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/jadencee50-del/qyvenox.git
cd qyvenox

# Install dependencies
npm install

# Setup environment variables
cp .env.example .env

# Setup database
npm run db:setup

# Start development server
npm run dev
```

The app will be available at:
- Frontend: http://localhost:5173
- Backend: http://localhost:5000

## Features

### Personal Dashboard
- History
- Files
- Projects
- Favorites
- AI Credits

### Authentication
- Google Sign-In
- Apple Sign-In
- GitHub Sign-In
- Microsoft Sign-In
- Email/Password

### Premium Features
- Faster AI
- HD Images
- 4K Videos
- More Credits
- Cloud Storage
- API Access
- Advanced Tools

## Roadmap

### Phase 1 (Current)
- ✅ Project setup
- ⏳ Landing page
- ⏳ Authentication
- ⏳ Dashboard
- ⏳ AI Chat

### Phase 2
- Image generation
- Video generation
- Code assistant

### Phase 3
- Mobile apps (iOS, Android)
- Website builder
- Marketplace
- API access

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT

## Contact

For inquiries: contact@qyvenox.com
