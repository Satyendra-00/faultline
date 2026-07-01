# FaultLine

FaultLine is a decision-intelligence platform for founders, builders, and operators to document real startup decisions, share post-mortems, save useful lessons, and build a professional learning profile.

## Live Demo

https://faultlinee.vercel.app

## What It Does

- Google authentication with Supabase Auth
- User onboarding and profile setup
- Editable professional profile
- Decision/story feed
- Story bookmarking and profile bookmark count
- Story publishing flow
- AI-assisted decision analysis
- Notifications and saved collections API foundation
- Production deployment on Vercel
- Supabase-backed database and auth system

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Supabase Auth
- Supabase Database
- Vercel Serverless API
- Gemini API
- Lucide React Icons

## Project Structure

```txt
.
├── api/                    # Vercel serverless API routes
├── src/
│   ├── components/         # React UI components
│   ├── utils/              # API, Supabase, story utilities
│   ├── App.tsx             # Main app shell
│   └── types.ts            # Shared TypeScript types
├── supabase/
│   ├── schema.sql          # Main database schema
│   └── repair_schema.sql   # Repair/migration SQL helpers
├── .env.example            # Environment variable template
├── package.json
└── vercel.json
