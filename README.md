# 🧑‍💼 AI Career Coach App (Full Stack)

Build a powerful AI-driven Career Coach platform using **Next.js**, **Neon Database**, **Tailwind CSS**, **Prisma**, **Inngest**, and **Shadcn UI**. This project integrates **Clerk Authentication** and **Gemini API** to deliver personalized career guidance.


## 🚀 Tech Stack
- Next.js 14 (App Router)
- Neon Database (Serverless PostgreSQL)
- Tailwind CSS
- Prisma ORM
- Inngest (Background Jobs / Serverless Functions)
- Shadcn UI Components
- Clerk Authentication
- Gemini AI API (Google AI)

## 🔑 Environment Variables
Create a `.env` file in the root with the following:
```env
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
