# 💼  HireWave

A full-stack Job Portal built using the MERN stack — designed to connect **employers** with **students**. Employers can post jobs, view applicants, and manage their hiring pipeline. Students can build their profiles, apply for jobs, and track their application statuses.

> Built with 💻 React, Node.js, Express.js, MongoDB, and styled using Tailwind CSS. Profile images and resumes are stored using Cloudinary.

---

## 🔑 Roles & Workflow

### 👩‍💼 Employer Flow
1. **Signup/Login** as an Employer.
2. After logging in:
   - Prompted to **create a company** (only once).
   - Fill out additional **company details**.
3. Gain access to:
   - **Job Creation Form** to post new jobs.
   - **Dashboard** showing all jobs posted.
   - **Applicant Management**: View applicants per job, and **Accept** or **Reject** with a single click.
   - **Job Deletion** option.

### 🎓 Student Flow
1. **Signup/Login** as a Student.
2. After logging in:
   - Navigate to **Profile** and update:
     - Profile Picture
     - Bio
     - Skills
     - Upload Resume (view-only by employers)
3. Visit **Jobs Page** to:
   - View all jobs posted by all companies.
   - Apply to any job — applications are marked as **Pending**.
4. Track application statuses (**Pending / Accepted / Rejected**) on the profile page.

---

## 🧰 Tech Stack

| Layer     | Technology               |
|-----------|--------------------------|
| Frontend  | React, Tailwind CSS      |
| Backend   | Node.js, Express.js      |
| Database  | MongoDB + Mongoose       |
| Auth      | JWT (JSON Web Tokens)    |
| File Uploads | Cloudinary (Profile + Resume) |

---

## ⚙️ Environment Variables

Make sure to create a `.env` file in the `backend/` directory with the following:

MONGO_URL=mongodb://127.0.0.1:27017/database
PORT=8000
SECRET_KEY=asdfghjjjkldfsaf

Cloudinary Config
CLOUD_NAME=dqcl9hcnd
API_KEY=your_cloudinary_api_key
API_SECRET=your_cloudinary_api_secret

yaml
Copy
Edit

> Cloudinary is used to store **profile pictures** and **resumes**.

---

## 🛠 How to Run Locally

# Clone the repo
git clone https://github.com/OSSworup/HireWave-Job-portal
cd HireWave-Job-portal

# Backend setup
cd backend
npm install
npm run dev

# Frontend setup
cd ../frontend
npm install
npm run dev

### 📝 Features Summary
# Employer
🔐 Auth with role-based login

🏢 Company creation (one per employer)

📄 Create jobs

📬 View applicants for each job

✅ Accept or ❌ Reject applicants

🗑️ Delete jobs

# Student
👤 Update profile with image, bio, skills, and resume

🔎 Browse all available jobs

📥 Apply to jobs

📊 Track application status

📄 Resumes are view-only by employers

#### 🚫 Not Implemented Yet
No input validation on profile fields (bio, skills)

No notification system for new applications

No admin panel or analytics

Not responsive for mobile screens yet

No test data seeding scripts

### 👤 Author
Omm Subham Sworup Ojha  

BSc Computer Science Graduate  
Aspiring Full-Stack Web Developer  
Contact: connect via GitHub, or [LinkedIn](http://linkedin.com/in/omm-subham-sworup-ojha-b80144338)




