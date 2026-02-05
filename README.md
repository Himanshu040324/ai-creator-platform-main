# AI Creator Platform

A full-stack AI content creation platform built with **Next.js, Convex, Clerk, Tailwind CSS, and Gemini AI**.
This application allows users to generate, edit, and manage AI-powered content with authentication, media uploads, and a modern UI.

🔗 **Live Demo:** [https://ai-creator-platform-main-six.vercel.app](ai-creator-platform-main-six.vercel.app)

📦 **Repository:** [https://github.com/Himanshu040324/ai-creator-platform-main](https://github.com/Himanshu040324/ai-creator-platform-main)

---

## 🚀 Features

* 🔐 User authentication with Clerk
* ✍️ AI-generated content using Gemini API
* 📝 Rich text editing with React Quill
* 🖼️ Image uploads via ImageKit
* 🗂️ Content management dashboard
* 🎨 Modern UI using Tailwind CSS and shadcn/ui
* ⚡ Full-stack architecture using Convex backend

---

## 🛠️ Tech Stack

**Frontend**

* Next.js 15
* React 19
* Tailwind CSS
* shadcn/ui
* React Quill

**Backend**

* Convex (serverless backend)

**Authentication**

* Clerk

**AI & Media**

* Google Gemini API
* ImageKit
* Unsplash API

---

## 📂 Project Structure

```
ai-creator-platform-main/
│
├── app/            # Next.js app router pages
├── components/     # Reusable UI components
├── convex/         # Backend functions and schema
├── hooks/          # Custom React hooks
├── lib/            # Utility functions
├── public/         # Static assets
│
├── middleware.js
├── next.config.mjs
├── package.json
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory and add:

```
# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
CLERK_JWT_ISSUER_DOMAIN=

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
IMAGEKIT_PRIVATE_KEY=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

# Gemini AI
GEMINI_API_KEY=
```

---

## 🧑‍💻 Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/Himanshu040324/ai-creator-platform-main.git
cd ai-creator-platform-main/app
```

### 2. Install dependencies

```
npm install --legacy-peer-deps
```

### 3. Add environment variables

Create a `.env` file and fill in the required keys.

### 4. Start the development server

```
npm run dev
```

Open:

```
http://localhost:3000
```

---

## 📸 Screenshots (Optional)

Add screenshots of:

* Dashboard
* Content editor
* AI generation page

Example:

```
![Dashboard](./public/dashboard.png)
```

---

## 📌 Future Improvements

* Team collaboration features
* Content scheduling
* AI templates marketplace
* Analytics dashboard
* Dark/light theme toggle

---

## 🤝 Contributing

Contributions are welcome.
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is for educational and portfolio purposes.

---

## 👨‍💻 Author

**Himanshu**
GitHub: [https://github.com/Himanshu040324](https://github.com/Himanshu040324)
