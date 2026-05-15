---
title: Taksh
description: A multi-agentic SaaS platform for AI-powered mock interviews based on job descriptions.
pubDate: 2026-05-15
heroImage: ../../assets/blog-placeholder-about.png
updatedDate: 2026-05-16
tags:
  - Multi-Agent AI
  - SaaS Platform
  - Next.js
  - Python
---

Taksh is a multi-agentic SaaS platform that revolutionizes mock interview preparation. Users submit a job description, and our AI agents orchestrate a complete interview experience—from personalized question generation to detailed performance analysis.

## How It Works

### 1. User Onboarding & Profile Generation

Users submit their resume and optionally a LinkedIn profile export (PDF). Our first agent analyzes these documents to build a comprehensive user profile, identifying key skills, experience levels, and career trajectory.

![Resume Upload & Profile Generation](/SS-1.png)
*Users upload resume PDF → AI extracts skills, experience, and generates profile*

### 2. Job Description Submission & Analysis

From the dashboard, users submit job descriptions for positions they're targeting. A dedicated agent parses the JD, extracting required skills, seniority level, company culture cues, and technical requirements.

![Dashboard & JD Submission](/SS-2.png)
*User dashboard showing submitted JDs with analysis status*

### 3. Interview Session Creation

Based on the JD analysis and user profile, our system automatically creates a tailored interview session. Questions are generated to match the specific role requirements, difficulty level, and the user's experience gaps.

### 4. Pre-Interview Lobby

Before entering the interview, users land in a lobby where they can review what to expect: interview topics, estimated duration, question types, and tips for success.

![Pre-Interview Lobby](/SS-3.png)
*Users review interview details, topics, and expectations before joining*

### 5. Live Interview with AI Agent

Users connect with our live interview agent in a real-time session. The agent asks contextual questions based on the JD analysis, adapts difficulty based on responses, and collects performance data throughout the interview.

![Live Interview Session](/SS-4.png)
*Real-time interview interface with AI agent asking contextual questions*

### 6. Comprehensive Report Generation

After the interview, our final agent synthesizes all collected data—response quality, technical accuracy, communication skills, and areas for improvement—into a detailed performance report with actionable feedback.

## Tech Stack

- **Frontend:** Next.js with Server Components for optimized rendering
- **AI Agents:** Python-based live interview agent with real-time processing
- **Analytics:** PostHog for feature flag-based deployment and user analytics
- **Infrastructure:** Containerized microservices with Kubernetes orchestration
- **Real-time:** WebSocket-based live interview sessions

## Key Features

- Resume & LinkedIn profile parsing for automatic user profiling
- JD analysis engine that extracts role-specific requirements
- Dynamic question generation tailored to user experience level
- Real-time adaptive interviewing with difficulty adjustment
- Comprehensive performance analytics and actionable feedback
- Multi-agent orchestration for seamless user experience
- Feature flag-based deployment for gradual rollouts

## Sample Report

<div class="my-8 p-6 rounded-xl border border-base-200 bg-surface/50">
  <div class="flex items-center justify-between flex-wrap gap-4">
    <div>
      <h3 class="text-white font-bold uppercase mb-1">Download Sample Interview Report</h3>
      <p class="text-base-600 text-sm">See the level of detail and insights provided in a Taksh performance report.</p>
    </div>
    <a href="/SS-1.png" download class="inline-flex items-center gap-2 px-6 py-3 bg-white text-black font-bold uppercase text-sm rounded-lg hover:bg-base-500 transition-colors no-underline">
      <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 10v6m0 0l-3-3m3 3l3-3m2 8H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path>
      </svg>
      Download Sample Report
    </a>
  </div>
</div>
