# TAKI-DIGITAL-Web
Website development.
web application/stitch/projects/3001220994902815805/screens/0444d234bcd943a38a1bd934a35a3340
# Taki Digital Services - Project README

This repository contains the frontend, backend configuration, and deployment instructions for the **Taki Digital Hub**.

## 1. Project Overview
Taki Digital Services is a professional digital service bureau providing government applications (KRA, HEID, HELB), creative design (CVs, brochures), and educational support. This hub facilitates service discovery, order placement, and secure payment via M-Pesa.

## 2. Tech Stack
- **Frontend:** Next.js (React) with Tailwind CSS.
- **Backend:** Next.js API Routes (Serverless Functions).
- **Database:** Supabase (PostgreSQL) or MongoDB for order tracking and user data.
- **Hosting:** Vercel.
- **Payments:** Safaricom Daraja API (STK Push).

## 3. Integration Details
- **Email:** takidigitalservices@gmail.com
- **Phone:** 0113766493
- **WhatsApp:** 0706317275
- **M-Pesa Till Number:** 8107382

## 4. Getting Started

### Prerequisites
- Node.js (v18+)
- Vercel CLI
- GitHub Account

### Installation
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd taki-digital-hub
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in `.env.local`:
   ```env
   # M-Pesa API Credentials
   MPESA_CONSUMER_KEY=your_key
   MPESA_CONSUMER_SECRET=your_secret
   MPESA_TILL_NUMBER=8107382
   
   # Database
   DATABASE_URL=your_database_url
   ```

## 5. Deployment
The fastest way to deploy is via the Vercel GitHub integration:
1. Push your code to GitHub.
2. Import the project into Vercel.
3. Configure the environment variables in the Vercel Dashboard under **Project Settings > Environment Variables**.
4. Click **Deploy**.

## 6. Architecture
- `/components`: Shared UI components (SideNavBar, TopNavBar, Footer).
- `/pages`: Main application routes (Dashboard, Catalog, Checkout).
- `/api`: Backend logic for M-Pesa callbacks and database updates.
- `/public`: Static assets including the official Taki Digital logo.

---
*Developed for Taki Digital Services.*
