<p align="center">
  <img src="public/images/robots/ezbuddy-happy.png" alt="EZCare AI Logo" width="120" height="120" />
</p>

<h1 align="center">🌿 EZCare AI</h1>

<p align="center">
  <strong>Your AI-Powered Wellness Companion</strong><br/>
  <em>Build healthy habits, track your wellness journey, and achieve your goals</em>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-deployment">Deployment</a> •
  <a href="#-contributing">Contributing</a>
</p>

---

## 📖 Overview

**EZCare AI** is a comprehensive, science-backed wellness tracking platform that combines behavioral science with modern technology. Built with Next.js 16 and powered by Supabase, it provides users with:

- 🧘 **Daily Wellness Tracking** — Monitor mood, energy, sleep quality, and stress levels with morning and evening check-ins
- 🍎 **Smart Meal Logging** — Capture meals with photos, receive nutritional scores, and track eating patterns
- 📊 **Progress Visualization** — View healing scores, trend analysis, and weekly insights
- 🤖 **AI-Powered Guidance** — Get personalized recommendations from EZBuddy, your friendly AI wellness companion
- 🔬 **Evidence-Based Approach** — All recommendations backed by research from Harvard Health, PubMed, NIH, and other trusted sources

Whether you're looking to improve sleep, reduce stress, manage weight, or boost energy levels, EZCare AI provides the tools and insights to support your wellness journey.

---

## ✨ Features

### 🌅 Daily Check-Ins
- **Morning Check-In** — Start your day by tracking mood, energy, and sleep quality
- **Evening Reflection** — Conclude with stress assessment, meal satisfaction, and goal planning
- **Streak Tracking** — Build consistency and maintain motivation with daily adherence tracking

### 🍽️ Smart Meal Logging
- **Photo Upload** — Seamlessly capture meals with secure image storage via Supabase
- **Nutritional Scoring** — Rate meals on a 0-100 scale with intelligent categorization
- **Trend Analytics** — Visualize eating patterns, meal timing, and nutritional averages
- **Rich Context** — Add notes about ingredients, portion sizes, and how meals made you feel

### 📈 Progress & Analytics
- **Healing Score** — Composite wellness metric based on daily habits and check-ins
- **Trend Visualization** — Track sleep, energy, stress, and mood patterns over time
- **AI-Powered Insights** — Receive personalized recommendations based on your unique data
- **Historical Data** — Review and analyze your wellness journey across weeks and months

### 🧠 Personalized Onboarding
- **15+ Step Journey** — Comprehensive setup to understand your goals, challenges, and lifestyle
- **Goal Selection** — Choose from weight management, energy improvement, stress reduction, and more
- **Lifestyle Assessment** — Capture diet preferences, activity levels, sleep habits, and symptoms
- **Science Integration** — Access credible research sources supporting each recommendation

### 💬 AI Chat with EZBuddy
- **Contextual Support** — Get wellness advice tailored to your personal data and patterns
- **24/7 Availability** — Your AI companion is always ready to answer questions
- **Supportive Tone** — Encouraging, friendly, and judgment-free guidance

### 📊 Analytics & Insights
- **PostHog Integration** — Comprehensive event tracking for product analytics
- **100+ Tracked Events** — Full instrumentation across authentication, onboarding, check-ins, meals, and progress
- **Privacy-First Design** — Opt-in analytics with development stub mode for testing

---

## 🎬 User Journey

```
┌─────────────────────────────────────────────────────────────────┐
│                      🌐 LANDING PAGE                             │
│                   Discover EZCare AI                             │
└─────────────────────┬───────────────────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────────────────┐
│                  🚀 ONBOARDING (15 Steps)                        │
│  Splash → Goals → Diet → Activity → Sleep → Symptoms → Plan     │
└─────────────────────┬───────────────────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────────────────┐
│                     📱 MEMBER DASHBOARD                          │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐        │
│  │   Home   │  │   Chat   │  │ Progress │  │ Settings │        │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘        │
└─────────────────────────────────────────────────────────────────┘
                      │
        ┌─────────────┼─────────────┐
        ▼             ▼             ▼
┌───────────────┐ ┌───────────────┐ ┌───────────────┐
│ 🌅 Morning    │ │ 🍽️ Meal       │ │ 🌙 Evening    │
│ Check-In      │ │ Logging       │ │ Reflection    │
└───────────────┘ └───────────────┘ └───────────────┘
```

---

## 🛠️ Tech Stack

### Core Technologies
| Layer | Technology | Purpose |
|-------|------------|---------|
| **Framework** | [Next.js 16](https://nextjs.org/) | React framework with App Router, Turbopack, and Server Components |
| **Language** | [TypeScript 5](https://www.typescriptlang.org/) | Type-safe development with modern JavaScript features |
| **UI Library** | [React 19](https://react.dev/) | Component-based UI with hooks and concurrent features |
| **Styling** | [Tailwind CSS 4](https://tailwindcss.com/) | Utility-first CSS framework with custom design tokens |

### Backend & Infrastructure
| Service | Technology | Purpose |
|---------|------------|---------|
| **Database** | [Supabase](https://supabase.com/) (PostgreSQL) | Scalable PostgreSQL database with real-time capabilities |
| **Authentication** | [Supabase Auth](https://supabase.com/auth) | Secure user authentication with email/password and OAuth |
| **Storage** | [Supabase Storage](https://supabase.com/storage) | S3-compatible object storage for meal photos |
| **API** | Next.js API Routes | Server-side endpoints for check-ins, meals, and subscriptions |

### Developer Experience
| Tool | Purpose |
|------|---------|
| **PostHog** | Product analytics and feature flags |
| **Heroicons** | Beautiful hand-crafted SVG icons |
| **Headless UI** | Unstyled, accessible UI components |
| **ESLint** | Code quality and consistency |
| **Vitest** | Fast unit testing framework |

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** 18.x or higher ([Download](https://nodejs.org/))
- **npm**, **yarn**, or **pnpm** package manager
- **Supabase Account** ([Sign up for free](https://supabase.com/))
- **Git** for version control

### Installation

Follow these steps to set up EZCare AI locally:

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ezcare-web-app.git
cd ezcare-web-app
```

#### 2. Install dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

#### 3. Configure environment variables

Create a `.env.local` file in the root directory:

```bash
cp .env.example .env.local
```

Add your Supabase credentials to `.env.local`:

```env
# Supabase Configuration (Required)
NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key

# PostHog Analytics (Optional)
NEXT_PUBLIC_POSTHOG_API_KEY=your-posthog-key
NEXT_PUBLIC_POSTHOG_HOST=https://app.posthog.com

# Application URL (Production)
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

> **Note:** Find your Supabase credentials in your [Supabase Dashboard](https://app.supabase.com/) under Project Settings → API.

#### 4. Set up the database

1. Navigate to your Supabase project's SQL Editor
2. Copy and execute the schema from `docs/supabase-schema.sql`
3. This will create all necessary tables, indexes, and Row Level Security (RLS) policies

#### 5. Configure Supabase Storage

1. In your Supabase Dashboard, go to **Storage**
2. Create a new bucket named `meal-photos`
3. Set the bucket to **public** (or configure appropriate RLS policies)

#### 6. Run the development server

```bash
npm run dev
```

The application will be available at [http://localhost:3000](http://localhost:3000)

### Building for Production

```bash
# Create an optimized production build
npm run build

# Start the production server
npm start
```

### Running Tests

```bash
# Run all tests
npm test

# Run tests in watch mode
npm test -- --watch

# Generate coverage report
npm test -- --coverage
```

---

## 📁 Project Structure

```
ezcare-web-app/
│
├── src/
│   ├── app/                      # Next.js App Router
│   │   ├── (auth)/              # Authentication routes
│   │   │   ├── sign-in/         # Sign in page
│   │   │   └── sign-up/         # Sign up page
│   │   ├── (member)/            # Protected member area
│   │   │   ├── app/             # Home dashboard
│   │   │   ├── chat/            # AI chat interface
│   │   │   ├── check-in/        # Morning & evening check-ins
│   │   │   ├── meal-logs/       # Meal tracking & history
│   │   │   ├── progress/        # Analytics & insights
│   │   │   └── settings/        # User preferences
│   │   ├── api/                 # API routes
│   │   │   ├── chat/            # AI chat endpoints
│   │   │   ├── checkins/        # Check-in CRUD operations
│   │   │   ├── meal-logs/       # Meal log management
│   │   │   └── subscriptions/   # Payment & subscription logic
│   │   ├── onboarding/          # Multi-step onboarding flow
│   │   ├── paywall/             # Subscription paywall
│   │   └── science/             # Research sources page
│   │
│   ├── components/              # React components
│   │   ├── check-ins/           # Check-in forms & UI
│   │   ├── dashboard/           # Dashboard widgets (streaks, timers)
│   │   ├── meals/               # Meal logging components
│   │   ├── onboarding/          # 15+ onboarding screens
│   │   ├── progress/            # Charts & trend visualizations
│   │   ├── ui/                  # Reusable UI primitives
│   │   └── __tests__/           # Component tests
│   │
│   ├── contexts/                # React Context providers
│   │   ├── EntitlementContext.tsx    # Subscription state
│   │   └── OnboardingContext.tsx     # Onboarding flow state
│   │
│   ├── lib/                     # Utility libraries
│   │   ├── analytics/           # PostHog event tracking
│   │   ├── auth/                # Authentication utilities
│   │   ├── data/                # Data fetching & caching
│   │   ├── storage/             # File upload helpers
│   │   ├── supabase/            # Supabase client setup
│   │   └── types/               # TypeScript type definitions
│   │
│   └── middleware.ts            # Next.js middleware (auth checks)
│
├── public/                      # Static assets
│   └── images/
│       └── robots/              # EZBuddy avatar images
│
├── docs/                        # Documentation
│   ├── supabase-schema.sql      # Database schema
│   ├── onboarding-contract.md   # Onboarding specifications
│   └── DEPLOY.md                # Deployment guide
│
├── supabase/                    # Supabase migrations
│   └── migrations/              # SQL migration files
│
├── .env.example                 # Environment variable template
├── next.config.ts               # Next.js configuration
├── tailwind.config.js           # Tailwind CSS configuration
├── tsconfig.json                # TypeScript configuration
├── vitest.config.ts             # Vitest test configuration
└── package.json                 # Project dependencies
```

### Key Directories

- **`src/app/`** — Next.js 16 App Router with file-based routing
- **`src/components/`** — Reusable React components organized by feature
- **`src/lib/`** — Core utilities, API clients, and helper functions
- **`src/contexts/`** — Global state management with React Context
- **`docs/`** — Technical documentation and database schemas

---

## 🗄️ Database Schema

EZCare AI uses **Supabase (PostgreSQL)** with Row Level Security (RLS) for data protection.

### Main Tables

| Table | Description | Key Fields |
|-------|-------------|------------|
| **`profiles`** | User profiles and onboarding data | `user_id`, `email`, `onboarding_completed`, `main_goal` |
| **`check_ins`** | Morning and evening check-in records | `user_id`, `type`, `mood`, `energy`, `sleep_quality`, `stress_level` |
| **`meal_logs`** | Meal entries with photos and scores | `user_id`, `meal_type`, `score`, `photo_url`, `notes` |
| **`subscriptions`** | User subscription status and plans | `user_id`, `plan`, `status`, `expires_at` |

### Security

- **Row Level Security (RLS)** enabled on all tables
- Users can only access their own data
- API keys use Supabase's `anon` key with RLS protection
- Storage bucket policies restrict file access

### Schema File

See the complete schema with indexes, functions, and triggers in [docs/supabase-schema.sql](docs/supabase-schema.sql).

---

## 🔬 Science-Backed Approach

All recommendations and insights in EZCare AI are grounded in peer-reviewed research and evidence from trusted sources:

| Source | Focus Areas |
|--------|-------------|
| 🎓 **Harvard Health Publishing** | Sleep science, nutrition, mental health |
| 📚 **PubMed / NIH** | Peer-reviewed medical research |
| 🏥 **Mayo Clinic** | Clinical health guidelines |
| 🌍 **World Health Organization** | Global health recommendations |
| 🧬 **Nature Medicine** | Behavioral health studies |

Users can explore all research sources and citations at `/science` within the application.

---

## 📊 Analytics & Event Tracking

EZCare AI includes comprehensive event tracking for product analytics via **PostHog**.

### Event Categories

| Category | Example Events |
|----------|----------------|
| **Authentication** | `user_signed_up`, `user_signed_in`, `user_signed_out` |
| **Onboarding** | `onboarding_started`, `step_completed`, `onboarding_finished` |
| **Check-Ins** | `morning_checkin_completed`, `evening_checkin_completed` |
| **Meals** | `meal_logged`, `meal_photo_uploaded`, `meal_edited`, `meal_deleted` |
| **Progress** | `progress_viewed`, `insights_generated`, `trend_analyzed` |
| **AI Chat** | `chat_message_sent`, `chat_opened`, `ezbuddy_response_received` |

### Privacy & Configuration

- **Opt-in Analytics** — Users can enable/disable tracking in settings
- **Development Stub Mode** — Analytics calls are stubbed in development
- **No PII Tracking** — Personal health data is never sent to analytics
- **GDPR Compliant** — Full data deletion support

View the complete event list in [src/lib/analytics/events.ts](src/lib/analytics/events.ts).

---

## 🚢 Deployment

### Deploy on Vercel (Recommended)

The easiest way to deploy EZCare AI is with [Vercel](https://vercel.com):

1. **Push your code to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Import to Vercel**
   - Visit [vercel.com/new](https://vercel.com/new)
   - Import your GitHub repository
   - Vercel will auto-detect Next.js configuration

3. **Add Environment Variables**
   
   In Vercel dashboard, add these environment variables:
   ```
   NEXT_PUBLIC_SUPABASE_URL
   NEXT_PUBLIC_SUPABASE_ANON_KEY
   NEXT_PUBLIC_POSTHOG_API_KEY (optional)
   NEXT_PUBLIC_APP_URL
   ```

4. **Deploy!**
   
   Click "Deploy" and Vercel will build and deploy your app.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

### Other Deployment Options

EZCare AI can be deployed on various platforms:

- **[Netlify](https://netlify.com)** — Connect GitHub repo and set environment variables
- **[Railway](https://railway.app)** — One-click deploy with automatic HTTPS
- **[Render](https://render.com)** — Free tier available with PostgreSQL support
- **[AWS Amplify](https://aws.amazon.com/amplify/)** — Integrated with AWS services
- **[Docker](https://www.docker.com/)** — Build custom image for self-hosting

### Pre-Deployment Checklist

Before deploying to production, review [docs/DEPLOY_CHECKLIST.md](docs/DEPLOY_CHECKLIST.md) for:

- ✅ Environment variable configuration
- ✅ Supabase RLS policies verification
- ✅ Storage bucket permissions
- ✅ Analytics setup
- ✅ Custom domain configuration
- ✅ SEO optimization

---

## 🤝 Contributing

We welcome contributions from the community! Whether you're fixing bugs, adding features, or improving documentation, your help is appreciated.

### How to Contribute

1. **Fork the repository**
   ```bash
   git clone https://github.com/yourusername/ezcare-web-app.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Write clean, documented code
   - Follow the existing code style
   - Add tests for new features

4. **Run linting and tests**
   ```bash
   npm run lint
   npm test
   ```

5. **Commit your changes**
   ```bash
   git commit -m "feat: add amazing feature"
   ```
   
   Use [Conventional Commits](https://www.conventionalcommits.org/):
   - `feat:` New feature
   - `fix:` Bug fix
   - `docs:` Documentation changes
   - `style:` Code style changes
   - `refactor:` Code refactoring
   - `test:` Test updates
   - `chore:` Maintenance tasks

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Open a Pull Request**
   - Provide a clear description of the changes
   - Reference any related issues
   - Include screenshots for UI changes

### Development Guidelines

- **TypeScript** — Use strict typing, avoid `any`
- **Tailwind CSS** — Use utility classes, avoid custom CSS when possible
- **Components** — Keep components small and focused
- **Accessibility** — Include ARIA labels and keyboard navigation
- **Testing** — Write unit tests for utility functions and components
- **Performance** — Optimize images, lazy load components
- **Mobile-First** — Test on mobile and tablet viewports

### Code of Conduct

Please be respectful and constructive. We're all here to build something great together.

### Need Help?

- 📖 Check the [documentation](docs/)
- 💬 Open an issue for questions
- 📧 Reach out to the maintainers

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to:
- ✅ Use commercially
- ✅ Modify
- ✅ Distribute
- ✅ Use privately

With the following conditions:
- 📄 Include the original license and copyright notice

---

## 🙏 Acknowledgments

EZCare AI is built with amazing open-source tools and libraries:

- [Next.js](https://nextjs.org/) — The React framework for production
- [Supabase](https://supabase.com/) — Open-source Firebase alternative
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework
- [PostHog](https://posthog.com/) — Product analytics platform
- [Heroicons](https://heroicons.com/) — Beautiful hand-crafted SVG icons
- [React](https://react.dev/) — The library for web interfaces
- [TypeScript](https://www.typescriptlang.org/) — JavaScript with syntax for types

Special thanks to all the open-source contributors who make projects like this possible! 💚

---

<p align="center">
  <strong>Made with 💚 for your wellness journey</strong>
</p>

<p align="center">
  <a href="https://ezcare.app">🌐 Website</a> •
  <a href="https://github.com/yourusername/ezcare-web-app">⭐ Star on GitHub</a> •
  <a href="mailto:hello@ezcare.app">📧 Contact Us</a>
</p>

<p align="center">
  <sub>Built with Next.js 16 • Powered by Supabase • Styled with Tailwind CSS 4</sub>
</p>
