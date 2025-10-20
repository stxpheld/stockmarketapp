# 📈 Modern Stock Market Platform – AI-Powered Real-Time Dashboard

A modern AI-powered stock market platform built with Next.js, shadcn/ui, Better Auth, and Inngest.
It allows users to track live stock prices, explore company fundamentals, manage personalized watchlists, receive automated alerts, and access AI-driven market insights.

The admin dashboard makes it easy to manage stocks, publish financial news, and monitor user activity, while event-driven workflows handle alerts, earnings notifications, and daily AI summaries behind the scenes.

# ⚙️ Tech Stack

Next.js – Full-stack React framework with SSR, SSG, and API routes.

TailwindCSS – Utility-first CSS framework for fast, responsive UI design.

shadcn/ui – Open-source React components with full customization and accessibility.

TypeScript – Strongly typed JavaScript for better maintainability and reliability.

Better Auth – Secure authentication (email/password, SSO, MFA).

Inngest – Event-driven workflows and background jobs (alerts, reporting, AI tasks).

Finnhub API – Real-time stock, crypto, and forex market data.

MongoDB – Flexible, high-performance NoSQL database.

Nodemailer – Email notifications and alerts.

CodeRabbit (optional) – AI-powered code review assistant.

🚀 Key Features

📊 Real-Time Dashboard – Track live prices with interactive line & candlestick charts, filter by sector, performance, or market cap.

🔍 Smart Search – Quickly find stocks using an intelligent search system.

⭐ Watchlist & Alerts – Create personalized watchlists, set price/volume alerts, and receive instant emails.

🧾 Company Insights – Access P/E ratio, EPS, revenue, news, filings, analyst ratings, and sentiment scores.

⚡ Event-Driven Workflows – Automated price updates, scheduled alerts, and AI-powered reporting with Inngest.

🤖 AI Alerts & Summaries – Daily digests, earnings notifications, and personalized summaries.

✉️ Custom Notifications – Tailored alerts and preferences for each user.

📈 Analytics & Insights – Understand trends, user behavior, and engagement metrics.

# 🧰 Getting Started
📦 Prerequisites

Git

Node.js

npm

# 🌀 Clone the Repository
git clone https://github.com/your-username/stock-market-app.git
cd stock-market-app

# 📥 Install Dependencies
npm install

# ⚙️ Set Up Environment Variables

Create a .env file in the project root:

NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB
NEXT_PUBLIC_FINNHUB_API_KEY=
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB
MONGODB_URI=

# BETTER AUTH
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000

# GEMINI
GEMINI_API_KEY=

# NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=


👉 You can get API keys from MongoDB
, Gemini
, Inngest
, and Finnhub
.

# 🧪 Run the Project
npm run dev
npx inngest-cli@latest dev


Open http://localhost:3000
 in your browser to view the application.

# 🧠 About the Project

This project was built as a scalable real-time financial platform, ideal for:

Developers exploring event-driven architectures

Builders looking for a solid fintech base

Finance enthusiasts automating their market tracking

It’s not just a demo — it’s a production-ready foundation to build your own product.

# 🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new feature branch

Submit a Pull Request 🚀

# 📜 License

This project is licensed under the MIT License.
