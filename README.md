# 🧠 AI-Powered Full Stack Blog Website
---

<!-- ![SkillForge Banner](https://github.com/h1a2r3s4h/SkillForge/blob/main/banner1.png?raw=true)-->

---

## 🌐 Live Demo  
🔗 **Website:** [https://quickblog.vercel.app](https://quick-blog-livid.vercel.app)  
<!--📦 **GitHub Repo:** [https://github.com/h1a2r3s4h/SkillForge](https://github.com/h1a2r3s4h/SkillForge)-->

---

## 📜 Overview

**QuickBlog** 
A modern, full stack blog platform powered by AI for content assistance. This project allows users to create, edit, and read blog posts with rich text editing, authentication, and AI-based features to improve writing quality.

---

## ✨ Features
- 📝 **Rich Text Blog Editor** with formatting and media support  
- 🤖 **AI Assistance** to generate or enhance blog content  
- 🔐 **User Authentication** and secure dashboard access  
- 📚 **Blog Listing**, filtering, and search functionality  
- 💬 **Toasts and Notifications** using React Toastify  
- 🌍 **Fully Responsive Design** built with Tailwind CSS

---

## 🧰 Tech Stack

| Category | Technologies Used |
|-----------|-------------------|
| **Frontend** | ReactJs, Tailwind CSS, Quill.js (Rich text editor)|
| **Backend** | NodeJs, ExpressJs|
| **Database** | MongoDB (MonogooseORM) |
| **Authentication** | JWT (JSON Web Tokens) |
| **AI Engine** | Gemini API |
| **Hosting** | Vercel |
| **Version Control** | Git & GitHub |

---

## ⚙️ Installation & Setup

Follow these steps to run SkillForge locally:

```bash
# 1️⃣ Clone the repository
git clone https://github.com/your-username/quick-blog.git
cd quick-blog

# 2️⃣  Setup Backend
cd server
npm install
npm start

# 3️⃣ Create environment variables
# Add the following in `.env.local`
MONGODB_URL="mongodb+srv://<username>:<password>@cluster0.<your-cluster-id>.mongodb.net"
ADMIN_EMAIL="admin@example.com"
ADMIN_PASSWORD="greatstack"
JWT_SECRET="your-jwt-secret-key"
IMAGEKIT_PUBLIC_KEY="your-imagekit-public-key"
IMAGEKIT_PRIVATE_KEY="your-imagekit-private-key"
IMAGEKIT_URL_ENDPOINT="https://ik.imagekit.io/<your-imagekit-id>"
GEMINI_API_KEY="your-gemini-api-key"

# 4️⃣ Setup Frontend
cd ../client
npm install
npm start

# 5️⃣ Visit
http://localhost:3000
