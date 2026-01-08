# JobForge 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework: Next.js 15](https://img.shields.io/badge/Framework-Next.js%2015-black.svg)](https://nextjs.org/)
[![Security: Arcjet](https://img.shields.io/badge/Security-Arcjet-blueviolet.svg)](https://arcjet.com/)
[![Deployment: Vercel](https://img.shields.io/badge/Deployment-Vercel-black.svg)](https://vercel.com/)

**JobForge** is an AI-powered career platform designed to help candidates automate their job search and master their interview performance. By integrating cutting-edge emotional intelligence and robust security, JobForge provides a professional-grade suite for resume optimization, technical questions generation, and empathic mock interviews.

---

## ✨ Key Features

- **AI Resume Architect:** Tailor your resume to specific Job Descriptions (JD) with high-precision ATS optimization using **Vercel AI SDK** & **Gemini AI**.
- **Empathic Mock Interviews:** Practice with **Hume AI**, which analyzes your vocal tone, confidence, and emotional cues to provide a realistic interview experience.
- **User-Friendly Interface**: Modern and responsive design for seamless user experience.
- **Enterprise-Grade Security:** Protected by **Arcjet** to prevent bot abuse, rate-limit API calls, and ensure secure form submissions.
- **Instant Authentication:** Seamless and secure user onboarding powered by **Clerk**.
- **Skills Gap Analysis:** Identify missing keywords and technical skills required for your desired career path.
- **Interview Preparation**: Practice interviews with AI-generated questions and receive constructive feedback.
- **Job Description Insights**: Analyze job postings to identify key skills and tailor applications accordingly.
- **Dashboard Analytics:** Track your application versions and interview progress in one centralized hub.

---

## 🛠️ The Tech Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | [Next.js 15 (App Router)](https://nextjs.org/) |
| **AI Orchestration** | [Vercel AI SDK](https://sdk.vercel.ai/) |
| **Empathic Voice** | [Hume AI (EVI)](https://hume.ai/) |
| **Authentication** | [Clerk](https://clerk.com/) |
| **Security/WAF** | [Arcjet](https://arcjet.com/) |
| **Database** | [PostgreSQL (via Drizzle ORM)](https://www.prisma.io/) |
| **Styling** | [Tailwind CSS + Shadcn UI](https://ui.shadcn.com/) |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js 18+** & **npm/pnpm**
- Accounts for: [Clerk](https://clerk.com/), [Arcjet](https://arcjet.com/), [Hume AI](https://hume.ai/), and [Vercel](https://vercel.com/).

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ninjasri98/JobForge.git
   cd JobForge
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Environment Setup: Create a `.env.local` file using the `example.env` file and populate it with your keys**
  
4. **Initialize Database:**
   ```bash
   npm run db:generate
   npm run db:push
   npm run db:migrate //For migrations
   ```
5. **Start Developing:**
   ```bash
   npm run dev
   ```
