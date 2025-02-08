# Recepito - Smart Expense Tracking Platform

<div align="center">
  <img src="/public/logo.png" alt="Recepito Logo" width="300"/>
</div>

## 📖 Overview

Recepito is a modern expense tracking platform that combines the power of AI Smart Expense Tracking Platform. Built for both personal and business use, it features automated receipt scanning, intelligent categorization.

## 🌟 Key Features

### User Authentication & Security
- Secure sign-up and login with Clerk Authentication
- Role-based access control
- Protected API routes
- Bot protection with ArcJet
- CSRF protection and rate limiting

### Receipt Management
- Automatic data extraction (amount, date, merchant, category)
- Support for multiple image formats
- Bulk receipt upload

### Financial Tracking
- Real-time expense tracking
- Custom categories and tags
- Multiple currency support
- Budget planning and monitoring
- Recurring expense management

### Analytics & Reporting
- 📊 Interactive dashboards
- Expense trends and patterns
- Category-wise analysis
- Exportable reports (CSV, PDF)
- Custom date range filtering

### User Experience
- 🌓 Dark/Light mode
- Responsive design
- Progressive Web App (PWA)
- Keyboard shortcuts
- Toast notifications

## 🛠️ Technical Architecture

### Frontend
- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS with custom configurations
- **Components**: Shadcn UI
- **State Management**: React Hooks
- **Forms**: React Hook Form with Zod validation

### Backend
- **Database**: Supabase (PostgreSQL)
- **ORM**: Prisma
- **API**: Next.js API Routes
- **Background Jobs**: Inngest
- **File Storage**: Supabase Storage
- **Caching**: Next.js Cache

### AI/ML
- **Text Extraction**: OCR with custom processing
- **Category Prediction**: Machine learning models


