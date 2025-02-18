 <h2 align="center"> CrimeAlert- Anonymous Reporting App</h2>

   <div align="center">
     A secure platform for anonymous incident reporting
    </div>
</div>
## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Environment Setup](#environment)
6. 🚀 [Deployment](#deployment)

## <a name="introduction">🤖 Introduction</a>

This is a anonymous reporting system built with Next.js 14, designed to provide a secure platform for reporting incidents while maintaining complete anonymity.

## <a name="tech-stack">⚙️ Tech Stack</a>

- NextJS 14 
- TypeScript
- Prisma with Neon Database
- NextAuth.js for Authentication
- Tailwind CSS
- React Hook 
- Google Gemini
- BCrypt for Password Encryption

## <a name="quick-start">🤸 Quick Start</a>

**Prerequisites**

Make sure you have the following installed:

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

**Installation**

```bash
# Clone the repository
git clone <your-repo-url>
cd CrimeAlert-app

# Install dependencies
npm install

# Set up the database
npx prisma generate
npx prisma db push

# Start the development server
npm run dev
```

## <a name="environment">🕸️ Environment Setup</a>

Create a `.env` file in the root directory with the following variables:

```env

NEXT_PUBLIC_MAPBOX_API_KEY=your-mapbox-key
DATABASE_URL=postgresql:your-database-url
NEXTAUTH_SECRET="your-secret-key"
NEXTAUTH_URL="http://localhost:3000/api/auth"
GEMINI_API_KEY=your-gemini-api-key

```

## <a name="deployment">🚀 Deployment</a>

The application can be easily deployed on [Vercel](https://vercel.com):

1. Push your code to a Git repository
2. Connect your repository to Vercel
3. Configure the environment variables
4. Deploy!

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) first.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
