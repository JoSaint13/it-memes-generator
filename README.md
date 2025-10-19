# MemeTech

> Empowering tech professionals with intelligent, contextual meme creation

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/memetech/repo)

## Overview

MemeTech is the definitive meme generation platform for IT professionals, transforming workplace communication through targeted, professional humor. Our platform enables developers and tech teams to create contextually relevant, engaging memes that resonate with technical audiences.

## Features

- ✨ AI-powered contextual meme generation
- 🚀 Tech-specific template library
- 💡 Instant sharing and collaboration tools
- 🔒 Secure user authentication

## Tech Stack

**Frontend:**
- React 18 with TypeScript
- Vite 5.x
- Tailwind CSS
- Zustand State Management

**Backend:**
- Next.js API Routes
- Node.js 20 LTS
- PostgreSQL with Prisma ORM
- NextAuth.js Authentication

**Deployment:**
- Vercel
- Supabase
- Cloudinary

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/memetech/memetech.git

# Install dependencies
cd memetech
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to see the application.

## Project Structure

```
/
├── src/
│   ├── components/     # React components
│   ├── pages/          # Next.js pages
│   ├── utils/          # Utility functions
│   └── styles/         # Tailwind CSS
├── public/             # Static assets
├── tests/              # Test files
└── docs/               # Documentation
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Build for production
npm run test        # Run tests
npm run lint        # Lint code
```

### Environment Variables

Required environment variables:

```env
NEXT_PUBLIC_API_URL=your-api-url
DATABASE_URL=your-database-connection-string
NEXTAUTH_SECRET=your-auth-secret
```

## Testing

```bash
# Run unit tests
npm run test

# Run with coverage
npm run test:coverage

# Run E2E tests
npm run test:e2e
```

## Deployment

### Vercel (Recommended)

```bash
npm run build
vercel --prod
```

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/tech-meme-template`)
3. Commit your changes (`git commit -m 'Add new tech meme template'`)
4. Push to the branch (`git push origin feature/tech-meme-template`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our development process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@memetech.dev or open a GitHub issue.

---

**Generated with ❤️ by the MemeTech Team**