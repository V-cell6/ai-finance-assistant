# Full Stack AI Fianace Platform with Next JS, Supabase, Tailwind, Prisma, Inngest, ArcJet, Shadcn UI
# Welth - AI-Driven Financial Platform

## Overview
Welth is an AI-powered financial management platform that helps users track their expenses, detect spending trends, and receive actionable insights via email. Built with modern full-stack technologies, Welth ensures a seamless and secure user experience.

![image](https://github.com/user-attachments/assets/1830e01c-3999-4c79-9131-73ec0f10e684)


## Features
- **AI-Powered Expense Tracking**: Uses Google Gemini AI to analyze and provide insights into spending patterns.
- **Automated Alerts**: Notifies users about unusual spending trends via email.
- **Interactive UI**: Built with Next.js, Tailwind CSS, and Shadcn UI for a sleek and modern interface.
- **Secure Authentication**: Implements Clerk and Arcjet for user authentication.
- **Scalable Backend**: Uses Supabase and Prisma for database management with PostgreSQL.
- **Background Processing**: Utilizes Inngest for efficient event-driven workflows.

Home Page

![image](https://github.com/user-attachments/assets/0e8d7ba7-c3a2-4eb3-9ce0-c70504df242f)

User Authentication/Sign-In Page
![image](https://github.com/user-attachments/assets/e4dac4b8-00db-47df-8eda-2df6bb513d6d)

Dashboard

![image](https://github.com/user-attachments/assets/168a4228-70f4-4ac3-a5de-cd81eab714d0)

![image](https://github.com/user-attachments/assets/b860c317-e7d2-495e-8afe-c998d2411f0e)

![image](https://github.com/user-attachments/assets/03b9c56f-cac0-403d-afb8-8a0add24d15a)

Scanning Receipts with AI

![image](https://github.com/user-attachments/assets/06c2d974-f53c-419c-a1c2-06c7a53c9835)

Inngest functions

![image](https://github.com/user-attachments/assets/b027c7c7-b93e-4c95-9f16-6813b7e4147e)









## Tech Stack
### Frontend
- [Next.js](https://nextjs.org/) - React-based framework for web applications
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Shadcn UI](https://ui.shadcn.com/) - Modern component library for Next.js

### Backend
- [Supabase](https://supabase.com/) - Open-source Firebase alternative for authentication and database
- [Prisma](https://www.prisma.io/) - ORM for PostgreSQL
- [Inngest](https://www.inngest.com/) - Event-driven workflows for background processing

### AI & Authentication
- [Gemini AI](https://ai.google.dev/) - AI service for analyzing spending habits
- [Clerk](https://clerk.dev/) - Authentication and user management
- [Arcjet](https://arcjet.com/) - Secure authentication and authorization


<img width="1470" alt="Screenshot 2024-12-10 at 9 45 45 AM" src="https://github.com/user-attachments/assets/1bc50b85-b421-4122-8ba4-ae68b2b61432">


### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```
