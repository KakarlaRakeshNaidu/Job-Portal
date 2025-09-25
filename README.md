🎯 Full Stack React JS Job Portal

A modern job portal web application built with React.js, TailwindCSS, Supabase, Clerk, and Shadcn UI.
This platform allows users to search, filter, and apply for jobs, track applications, manage job postings, and onboard seamlessly — all with a clean and intuitive interface.

🚀 Features
Authentication & User Management

🔐 Clerk authentication with onboarding flows

👤 User profiles with protected routes for secure access

Job Search & Application

🔍 Job search with filters for category, location, and skills

💾 Save/Unsave jobs

📄 Apply to jobs with structured forms and validation

Job Listings & Management

📃 Job listing pages with detailed descriptions

➕ Post a new job

🏢 Add new companies

🗑 Delete job listings

User Dashboard

📂 View saved jobs, applications, and created jobs

📊 Track application status and view applicants

🛠 Tech Stack

Frontend: React.js, Shadcn UI, TailwindCSS

Database: Supabase (PostgreSQL backend)

Authentication: Clerk

Forms & Validation: React Hook Form, Zod

Deployment (Recommended): Vercel

📁 Project Structure<br>
/src<br>
 ├── components/        # Reusable UI components<br>
 ├── hooks/             # Custom React hooks<br>
 ├── pages/             # Application routes and pages<br>
 ├── services/          # API / Supabase queries<br>
 ├── styles/            # Tailwind and custom styles<br>
 ├── utils/             # Helper functions<br>
 └── App.jsx            # Main application component<br>

⚙️ Setup & Installation
1️⃣ Clone the repository
git clone https://github.com/YourUsername/job-portal-react.git
cd job-portal-react

2️⃣ Install dependencies
npm install
# or yarn / pnpm

3️⃣ Configure environment variables

Create a .env file in the root directory:

VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
VITE_CLERK_PUBLISHABLE_KEY=


Replace placeholders with your actual credentials.

4️⃣ Run the development server
npm run dev


Open http://localhost:3000
 in your browser 🚀

📈 Future Enhancements

🌐 Multi-language / localization support

📱 Dedicated mobile app version

🔔 Email notifications for job updates

🛡 Enhanced security & role-based access control

📜 License

MIT License © 2025
Feel free to use, modify, and contribute.
