# SENSAI - AI Career Coach

## About

SENSAI is a full-stack web application that empowers users to advance their careers through personalized guidance, interview preparation, resume building, and AI-powered tools. The platform offers:

- Smart career advice tailored to your goals
- Mock interviews and preparation resources
- Resume and cover letter generation
- Insights into industry growth and trends
- Secure authentication and user management

SENSAI is designed for job seekers and professionals who want to leverage technology to boost their career prospects.

## Features

- Personalized career guidance powered by AI
- Interview preparation and mock interviews
- Resume builder and cover letter generator
- Industry insights and growth analytics
- Secure authentication with Clerk
- Modern, responsive UI with Shadcn and Tailwind CSS

## Quick Start

1. Clone the repository and install dependencies.
2. Add your environment variables in a `.env` file (see below).
3. Start the development server.

### Required Environment Variables

DATABASE_URL= <br>
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY= <br>
CLERK_SECRET_KEY= <br>
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in <br>
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up <br>
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding <br>
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding <br>
GEMINI_API_KEY= <br>

