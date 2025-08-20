# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI 🔥🔥

# AI Career Coach

**Full-Stack AI Career Coach** built with Next.js, NeonDB, Tailwind CSS, Prisma, Inngest, and Shadcn UI. This app provides personalized career guidance, resume and cover letter tools, and smart job insights through AI.

## Features

-  **Secure User Authentication** via Clerk (sign-up, sign-in, onboarding flows).
-  **Resume Builder**: Create and customize a professional resume with guided prompts.
-  **Cover Letter Generator**: Draft impressively written cover letters using AI templates.
-  **Industry Insights**: Get demand trends, salary ranges, and top in-demand skills powered by AI.
-  **Interview Preparation**: Practice with AI-generated mock interviews and quizzes.
-  **Background Processing** with Inngest: Efficient handling of async tasks like document generation, scoring, and data fetch.
-  **Responsive UI** built using Tailwind CSS and Shadcn UI for seamless user experience.

## Tech Stack

| Layer               | Technologies                                |
|--------------------|----------------------------------------------|
| Frontend           | Next.js, React, Tailwind CSS, Shadcn UI      |
| Backend / API      | Next.js API Routes, Prisma ORM               |
| Database           | NeonDB                                       |
| Authentication     | Clerk                                        |
| Background Jobs    | Inngest                                      |
| AI Integration     | Gemini API (for resume analysis, cover letters, insights) |
| Development Tools  | ESLint, Prettier, Tailwind, PRISMA Studio    |

## Getting Started

### Prerequisites

Ensure you have:

- Node.js (v16+)
- npm or yarn
- Git

### Setup

1. Clone the repo:

    ```bash
    git clone https://github.com/abhasbali/ai-carrer-coach.git
    cd ai-carrer-coach
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

3. Create a `.env` file at the root with the following variables:

    ```env
    DATABASE_URL=
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
    GEMINI_API_KEY=
    ```

4. Apply database schema and set up Prisma:

    ```bash
    npx prisma generate
    npx prisma db push
    ```

5. Run the development server:

    ```bash
    npm run dev
    # or
    yarn dev
    ```

6. Open [http://localhost:3000](http://localhost:3000) to view your app.

## Deployment

This project can be seamlessly deployed to Vercel (or any node-compatible hosting provider). Just push to your repo and link to Vercel—remember to configure the same environment variables in your deployment settings.

## Screenshots / Demo

(Optional: Add screenshots or a live demo link similar to other full-stack AI career coach repositories.)

## Contributing

Contributions are welcome! Want to suggest a feature or fix a bug?

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Commit your changes.
4. Push to your branch and open a Pull Request.

Please ensure your code follows existing style patterns and includes relevant tests or previews.

## License

This project is licensed under the MIT License — see the [LICENSE file](LICENSE.md) for details.

---

**Powered by modern AI and React technologies—your career coach, always on-demand.**  



### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```
