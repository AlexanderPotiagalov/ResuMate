<div align="center">

# 🤖 ResuMate — Your AI-Powered Career Copilot

### Unlock smarter job applications with AI-driven resume analysis, personalized job matching, and auto-generated cover letters.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-00C897?style=for-the-badge&logo=vercel&logoColor=white)](https://final-project-lakes.vercel.app)

![Stars](https://img.shields.io/github/stars/CMPT-276-SPRING-2025/final-project-lakes?style=for-the-badge)
![Forks](https://img.shields.io/github/forks/CMPT-276-SPRING-2025/final-project-lakes?style=for-the-badge)
![Issues](https://img.shields.io/github/issues/CMPT-276-SPRING-2025/final-project-lakes?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/CMPT-276-SPRING-2025/final-project-lakes?style=for-the-badge)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shadcn/UI](https://img.shields.io/badge/Shadcn--UI-000000?style=for-the-badge)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![JSearch API](https://img.shields.io/badge/JSearch_API-000000?style=for-the-badge)

</div>

---

<div align="center">
  <img src="Images/Homepage.png" width="48%" />
  <img src="Images/HomePage1.png" width="48%" />
</div>

<div align="center">
  <img src="public/gifs/resumate_demo.gif" width="70%" alt="Live demo walkthrough" />
</div>

---

## 🚀 What is ResuMate?

**ResuMate** is an intelligent, full-stack web application that streamlines job applications using artificial intelligence. Whether you're looking to improve your resume, find the perfect role, or instantly generate cover letters, ResuMate brings it all together in one sleek experience.

---

## ✨ Key Features

- 🔍 **AI Resume Analyzer** – Upload your resume and get smart recommendations using OpenAI.
- 🎯 **Personalized Job Matching** – Match your skills to real jobs via the JSearch API.
- ✍️ **Cover Letter Generator** – One-click generation of tailored cover letters based on your resume and job title.
- 🌗 **Dark/Light Theme Support** – Designed with a beautiful, responsive UI using TailwindCSS + Shadcn UI.
- ⚡ **Live Deployment & CI/CD** – Built with Vite, tested with Vitest, and continuously deployed via Vercel.

---

## 🛠 Tech Stack

| Area              | Technology                            |
|-------------------|----------------------------------------|
| Frontend Framework | React.js                              |
| UI Styling         | Tailwind CSS + Shadcn UI              |
| API Integration    | OpenAI, JSearch                       |
| Testing            | Vitest                                |
| Build Tool         | Vite                                  |
| PDF Parsing        | `pdf-parse` for client-side resume reading |
| Deployment         | Vercel                                |

---

## 🧑‍💻 Getting Started Locally

### Prerequisites
- Node.js (v18 or higher)
- npm

### 📦 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/CMPT-276-SPRING-2025/final-project-lakes.git
cd final-project-lakes

# 2. Install dependencies
npm install

# 3. Create an environment file
touch .env
```

### 🔑 Add your API keys in `.env`

```env
OPENAI_API_KEY=your_openai_key_here
JSEARCH_API_KEY=your_jsearch_key_here
```

```bash
# 4. Run the development server
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) to use it locally.

---

## 📂 Project Structure

```
.
├── public/                 # Static assets & favicon
├── src/                   # Main application source code
│   ├── components/        # Reusable components
│   ├── pages/             # Main pages (Home, Resume, Cover Letter, etc.)
│   ├── api/               # API call utilities
│   └── hooks/             # Custom React hooks
├── .github/workflows/     # CI/CD workflows
├── tailwind.config.js     # Tailwind config
├── vite.config.js         # Vite config
└── README.md              # You're here.
```

---

## 🧪 Testing

ResuMate is tested with **Vitest** for performance and reliability.

```bash
# Run unit tests
npm run test
```

---

## 🤝 Contributors

Built with 💙 by:

- [Alexander Potiagalov](https://github.com/AlexanderPotiagalov)
- [Manan Mehta](https://github.com/Manan565)
- [Khalid Karim](https://github.com/khalidkarimkqr)
- [Mohammad A.](https://github.com/Mohammad220044)

---

## 📫 Feedback or Suggestions?

Feel free to [open an issue](https://github.com/CMPT-276-SPRING-2025/final-project-lakes/issues) or reach out via GitHub!

---

<div align="center">
  <b>📍 Empowering job seekers through smart technology — ResuMate.</b>
</div>
