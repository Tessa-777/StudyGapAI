# 🚀 StudyGapAI 

## 🥇 1st Place Winner - WUD AI Hackathon 2025

<p align="center">
  <img alt="React" src="https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img alt="Vite" src="https://img.shields.io/badge/Vite-5.x-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-3.x-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-Auth-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
</p>

This is the official frontend for **StudyGapAI**, an AI-powered diagnostic tool that identifies the hidden, foundational knowledge gaps holding Nigerian JAMB students back. Built with React, Vite, and TailwindCSS.

**➡️ Live App:** [https://Tessa-777.github.io/Royal-Light-StudyGapAI](https://Tessa-777.github.io/Royal-Light-StudyGapAI)  
**➡️ Backend Repository:** [https://github.com/Tessa-777/Royal-Light-StudyGapAI-Backend.git](https://github.com/Tessa-777/Royal-Light-StudyGapAI-Backend.git)

> **⚠️ Important: The `backend-ai-integrated-main` Branch**
> The primary and most up-to-date code for this backend is located in the `backend-ai-integrated-main` branch. Please ensure you clone and work from this specific branch.
---

## Development & Authorship

StudyGapAI was developed entirely by Theresia Saumu as the sole developer for the WUD AI Hackathon 2025 (1st Place Winner).

**Technical Development:** 100% developed by Theresia Kitele
- Full-stack architecture and implementation
- All backend code (Python Flask)
- All frontend code
- Database design and implementation
- AI integration and prompt engineering
- Deployment and DevOps

**Hackathon Collaboration:** During the 1 week hackathon sprint, team members contributed to ideation and strategic direction. All code and technical implementation was authored solely by Theresia Saumu.

**Current Status:** StudyGapAI is now being developed independently by Theresia Saumu.

## ✨ Core Features

- **Guest Mode Quiz:** Users can take a full diagnostic quiz without creating an account. All progress is saved locally and can be migrated after signing up.
- **AI-Powered Diagnostics:** The core of our app. Submits quiz answers *and* student explanations to our Gemini-powered backend to get a deep analysis of strengths and weaknesses.
- **Root Cause Analysis:** Goes beyond simple scores to identify the *foundational* reasons for mistakes (e.g., "weak in Algebra" is the root cause for failing "Calculus" questions).
- **Personalized 6-Week Study Plans:** The AI generates a tailored, week-by-week study plan based on the diagnostic results, prioritizing foundational gaps first.
- **Progress Tracking & Resource Library:** Dashboards with charts to monitor improvement and access to curated learning resources.

## 🛠️ Tech Stack

- **Framework:** React 18+ with Vite
- **Styling:** TailwindCSS (mobile-first)
- **State Management:** TanStack Query (React Query) for server state
- **API Client:** Axios
- **Authentication:** Supabase Auth SDK (JWT management)
- **Charts:** Recharts

## 🚀 Getting Started

### 1. Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### 2. Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Tessa-777/Royal-Light-StudyGapAI.git
    cd Royal-Light-StudyGapAI
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up environment variables:**
    Create a `.env.local` file in the root and add your keys:
    ```env
    VITE_API_BASE_URL=http://localhost:5000/api
    VITE_SUPABASE_URL=your_supabase_url
    VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    ```
    The app will be available at `http://localhost:5173`.

## 🤖 AI Integration

This frontend consumes a powerful backend API that leverages **Google Gemini 2.0 Flash**. The AI is responsible for:
- **Deep Diagnostic Analysis** of quiz results and student explanations.
- **Generating Personalized 6-Week Study Plans**.
- **Providing Detailed, Step-by-Step Answer Explanations**.

For a complete breakdown of the AI tools used in development and in the product, see the main **[AI Acceleration Report](AI_ACCELERATION_REPORT.md)**.

## 📚 Project Documentation

All project documentation, including technical specifications and setup guides, is organized in the [`/docs`](./docs/) folder.

```
