# OpenHive MVP

## Vision

OpenHive is an AI-powered platform that helps beginner developers go from zero open-source experience to their first accepted Pull Request (PR).

The long-term vision is to become the most trusted platform for discovering, contributing to, and showcasing open-source work, eventually connecting contributors, maintainers, and hiring companies.

However, the MVP focuses on solving one problem only:

**Helping a beginner make their first successful contribution to an open-source project.**

---

# Problem Statement

Every year, thousands of students want to contribute to open source.

Most of them face the same challenges:

* They don't know which repository to choose.
* Large repositories feel overwhelming.
* They don't know which issue is beginner-friendly.
* They struggle to understand project structure.
* They don't know how to make their first Pull Request.
* They often give up before contributing.

As a result, many aspiring contributors never make their first contribution.

---

# Target Users

## Primary Users

* College students
* Beginner developers
* First-time open-source contributors

### Characteristics

* Know basic programming
* Have a GitHub account
* Want to contribute but don't know where to start
* Need guidance and confidence

---

# MVP Goal

The MVP succeeds if a beginner can:

1. Sign in with GitHub.
2. Discover a suitable repository.
3. Find a suitable issue.
4. Understand what to do.
5. Submit their first Pull Request.

---

# Core User Journey

User visits OpenHive

↓

Signs in with GitHub

↓

Completes skill profile

↓

Receives repository recommendations

↓

Chooses a repository

↓

Receives beginner-friendly issue recommendations

↓

Views contribution roadmap

↓

Starts contributing

↓

Submits Pull Request

↓

Tracks contribution progress

---

# MVP Features

## 1. GitHub Authentication

Purpose:

Allow users to sign in using GitHub.

Features:

* GitHub OAuth login
* User profile creation
* GitHub username retrieval
* Avatar display

---

## 2. Skill Assessment

Purpose:

Understand user background.

Information Collected:

* Programming languages
* Experience level
* Areas of interest
* Open-source experience

Examples:

Languages:

* JavaScript
* Python
* Java

Experience:

* Beginner
* Intermediate

Interest:

* Web Development
* AI/ML
* Backend
* DevOps

---

## 3. Repository Recommendation Engine

Purpose:

Recommend repositories suitable for the user.

Selection Criteria:

* Beginner friendly
* Active repository
* Recently maintained
* Matching technology stack
* Good documentation

Output:

Recommended repositories with:

* Repository name
* Description
* Primary language
* Difficulty level

---

## 4. Issue Recommendation System

Purpose:

Help users find issues they can realistically solve.

Selection Criteria:

* Good First Issue
* Help Wanted
* Beginner Friendly
* Recently active

Output:

Issue title

Difficulty

Estimated effort

Issue description

---

## 5. Repository Overview

Purpose:

Reduce repository complexity.

Show:

* Project purpose
* Technology stack
* Important folders
* Contribution guide
* Setup instructions

This may initially use simple parsing and later be enhanced with AI.

---

## 6. Contribution Roadmap

Purpose:

Provide step-by-step guidance.

Example:

Step 1:
Fork repository

Step 2:
Clone repository

Step 3:
Set up environment

Step 4:
Understand issue

Step 5:
Make changes

Step 6:
Create Pull Request

---

## 7. Progress Tracking

Purpose:

Keep contributors motivated.

Track:

* Selected repository
* Selected issue
* Repository cloned
* PR submitted
* PR merged

Status Examples:

Not Started

In Progress

Completed

Merged

---

# Features Explicitly NOT Included In MVP

The following features are intentionally postponed:

* Hiring platform
* Maintainer dashboard
* Contributor reputation score
* Bounty marketplace
* Team formation
* Resume builder
* AI mentor chatbot
* Enterprise analytics
* Sponsorship system

Reason:

Focus on solving one problem exceptionally well before expanding.

---

# Success Metrics

The MVP will be considered successful if:

* 50+ students sign up
* 20+ users select a repository
* 10+ users submit a Pull Request
* At least 5 users get their first PR accepted

---

# Tech Stack

Frontend:

* Next.js
* TypeScript
* Tailwind CSS

Backend:

* Next.js API Routes

Database:

* PostgreSQL

ORM:

* Prisma

Authentication:

* GitHub OAuth

External APIs:

* GitHub API

Deployment:

* Vercel

Analytics:

* PostHog

---

# Future Vision

OpenHive will evolve from a contribution platform into a complete open-source ecosystem.

Future phases may include:

Phase 2:
Contributor Profiles

Phase 3:
Maintainer Tools

Phase 4:
Open-Source Reputation System

Phase 5:
Hiring Marketplace

Phase 6:
Enterprise Talent Platform

The long-term mission is to create a world where developers are evaluated based on real contributions rather than resumes alone.
