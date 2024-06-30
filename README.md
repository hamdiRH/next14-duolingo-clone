# Build a Duolingo Clone With Nextjs, React, Drizzle, Stripe (2024)

![Duolingo thumb (1)](./youthumb.png)

This is a repository for a "Build a Duolingo Clone With Nextjs, React, Drizzle, Stripe (2024)" youtube video.

[VIDEO TUTORIAL](https://www.youtube.com/watch?v=dP75Khfy4s4)

Key Features:

- 🌐 Next.js 14 & server actions
- 🗣 AI Voices using Elevenlabs AI
- 🎨 Beautiful component system using Shadcn UI
- 🎭 Amazing characters thanks to KenneyNL
- 🔐 Auth using Clerk
- 🔊 Sound effects
- ❤️ Hearts system
- 🌟 Points / XP system
- 💔 No hearts left popup
- 🚪 Exit confirmation popup
- 🔄 Practice old lessons to regain hearts
- 🏆 Leaderboard
- 🗺 Quests milestones
- 🛍 Shop system to exchange points with hearts
- 💳 Pro tier for unlimited hearts using Stripe
- 🏠 Landing page
- 📊 Admin dashboard React Admin
- 🌧 ORM using DrizzleORM
- 💾 PostgresDB using NeonDB
- 🚀 Deployment on Vercel
- 📱 Mobile responsiveness

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/AntonioErdeljac/next14-duolingo-clone.git
```

### Install packages

```shell
npm i
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY = "";
CLERK_SECRET_KEY = "";
DATABASE_URL = "postgresql://...";
STRIPE_API_KEY = "";
STRIPE_WEBHOOK_SECRET = "";
NEXT_PUBLIC_APP_URL = "http://localhost:3000";
```

### Setup Drizzle ORM

```shell
npm run db:push

```

### Seed the app

```shell
npm run db:seed

```

or

```shell
npm run db:prod

```

### Start the app

```shell
npm run dev
```
