# Prepwise: Your AI-Powered Job Interview Coach

<div align="center">
  <img src="https://img.shields.io/badge/-Next.JS-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=black" alt="Next.js" />
  <img src="https://img.shields.io/badge/-Vapi-white?style=for-the-badge&color=5dfeca" alt="Vapi" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/-Firebase-black?style=for-the-badge&logoColor=white&logo=firebase&color=DD2C00" alt="Firebase" />
</div>

---

## 🚀 About Prepwise

Prepwise is an innovative platform designed to help job seekers prepare for interviews with the power of AI. Using Vapi AI voice agents, Prepwise simulates real-world interview scenarios, provides instant feedback, and helps you refine your skills. Whether you're a beginner or an experienced professional, Prepwise is your ultimate interview preparation companion.

---

## 🛠️ Tech Stack

- **Next.js**: For building a fast and scalable user interface.
- **Firebase**: For authentication and real-time data storage.
- **Tailwind CSS**: For modern and responsive styling.
- **Vapi AI**: For voice-based AI interview simulations.
- **Google Gemini**: For generating intelligent interview questions.
- **Zod**: For schema validation and type safety.

---

## 🌟 Features

- **AI-Powered Interviews**: Simulate interviews with Vapi AI voice agents.
- **Customizable Scenarios**: Tailor interviews based on role, experience level, and tech stack.
- **Real-Time Feedback**: Get instant feedback on communication, technical knowledge, and more.
- **Dashboard**: Track your progress and manage past interviews.
- **Modern UI/UX**: Enjoy a sleek, user-friendly interface.
- **Fully Responsive**: Works seamlessly across all devices.

---

## ⚡ Quick Start

### Prerequisites

Ensure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Colyzo466/Ai_Interview_Provider.git
   cd Ai_Interview_Provider

2. Install dependencies:
   npm install

3. Set up environment variables: Create a .env.local file in the root directory and add the following:

NEXT_PUBLIC_VAPI_WEB_TOKEN=
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_FIREBASE_API_KEY=
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=
NEXT_PUBLIC_FIREBASE_PROJECT_ID=
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=
NEXT_PUBLIC_FIREBASE_APP_ID=
FIREBASE_PROJECT_ID=
FIREBASE_CLIENT_EMAIL=
FIREBASE_PRIVATE_KEY=

4. Start the development server:

npm run dev

5. Open the app in your browser: http://localhost:3000

📋 Features in Detail
1. AI-Generated Questions
Generate interview questions tailored to your role, experience level, and tech stack.
Powered by Google Gemini and Vapi AI.

2. Voice-Based Interviews
Conduct mock interviews with AI voice agents for a realistic experience.

3. Feedback and Analysis
Receive detailed feedback on:
Communication Skills
Technical Knowledge
Problem-Solving
Confidence and Clarity
Identify strengths and areas for improvement.

4. Dashboard
Manage all your interviews in one place.
Track your progress over time.

📂 Folder Structure

├── app/
│   ├── api/
│   │   └── vapi/
│   │       └── generate/
│   │           └── route.ts
│   ├── (root)/
│   │   ├── interview/
│   │   │   ├── page.tsx
│   │   │   └── [id]/
│   │   │       └── feedback/
│   │   │           └── page.tsx
├── components/
│   ├── Agent.tsx
│   ├── DisplayTechIcons.tsx
│   └── ui/
├── lib/
│   ├── actions/
│   │   ├── auth.action.ts
│   │   └── general.action.ts
│   ├── utils.ts
├── firebase/
│   ├── admin.ts
│   └── client.ts
├── public/
│   └── assets/
├── types/
│   └── index.d.ts

🛡️ License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Contributing
We welcome contributions! Feel free to submit issues or pull requests to improve Prepwise.

📞 Contact
For any inquiries or support, please reach out to:

Email: colyzo466@gmail.com
GitHub: Colyzo466
Prepwise: Empowering you to ace your next job interview with confidence!

