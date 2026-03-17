🍽️ Chi Restaurant – Full-stack Online Food Ordering System
A modern, high-performance e-commerce platform for restaurants, built with the PERN stack (PostgreSQL, Express/Node.js, React, Next.js) and TypeScript.

🚀 Live Demo
🔗 [https://chi-restaurant.vercel.app/](https://chi-restaurant.vercel.app/)
<img width="1920" height="2509" alt="image" src="https://github.com/user-attachments/assets/599115d7-bb7b-4918-ab68-722da918a5e1" />

🌟 Key Features
Dynamic Menu: Browse and search food items with real-time category filtering.
User Authentication: Secure social login (Google OAuth) and session management via Auth.js (NextAuth).
Shopping Cart: Persistent cart functionality with real-time price calculation.
Secure Payments: Integrated Stripe API for seamless checkout and automated order processing.
Order Management: Real-time order status tracking using Stripe Webhooks and PostgreSQL.
Responsive UI: Mobile-first design optimized for all devices using Tailwind CSS.

🛠️ Tech Stack
Frontend: Next.js 14+ (App Router), React, TypeScript, Tailwind CSS.
Backend: Node.js (Next.js API Routes), Auth.js.
Database: PostgreSQL with Prisma ORM for type-safe database access.
Payment: Stripe API & Webhooks.
Deployment: Vercel (Frontend/Backend), Supabase/Neon (PostgreSQL).

🏗️ Architecture & Database
The project follows a modern Full-stack architecture:
Database Schema: Designed with relational integrity in mind (Users, Products, Categories, Orders).
State Management: Managed using React Hooks and Context API for a smooth user experience.
Type Safety: End-to-end TypeScript implementation to minimize runtime errors.

🔧 Getting Started
1. Clone the repository
bash
git clone [https://github.com/chilunhay/chi-restaurant.git](https://github.com/chilunhay/chi-restaurant.git)
cd chi-restaurant
Hãy thận trọng khi sử dụng mã.

2. Install dependencies
bash
npm install
Hãy thận trọng khi sử dụng mã.

3. Setup Environment Variables
Create a .env file in the root directory and add:
env
DATABASE_URL=your_postgresql_url
NEXTAUTH_SECRET=your_secret
GOOGLE_ID=your_google_id
GOOGLE_CLIENT_SECRET=your_google_secret
STRIPE_SECRET_KEY=your_stripe_key
STRIPE_WEBHOOK_SECRET=your_webhook_secret
Hãy thận trọng khi sử dụng mã.

4. Run Migrations
bash
npx prisma generate
npx prisma db push
Hãy thận trọng khi sử dụng mã.

5. Start the Development Server
bash
npm run dev
Hãy thận trọng khi sử dụng mã.

👤 Author
Tat Duc Chi
GitHub: @chilunhay
Portfolio: 3d-portfolio-nine-eta.vercel.app
