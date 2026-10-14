# 🚀 ONIK BAGHERWAL — Modern Personal Portfolio

A sleek, responsive, modern personal portfolio website built for **ONIK BAGHERWAL**, a B.Tech student at **JECRC University, Jaipur, Rajasthan**, specializing in Artificial Intelligence, Web Development, and Digital Productivity.

Designed with a high-performance modern tech aesthetic, glassmorphism, subtle glow animations, and a component-driven React architecture ready for instant deployment to **Vercel**.

---

## 🌟 Features & Sections

1. **Hero / Home**:
   - Dynamic headline with gradient typography.
   - Subtitle: *"B.Tech Student | AI & Technology Enthusiast"*.
   - Direct Call-to-Actions: *"View Projects"* & *"Contact Me"*.
   - Interactive terminal preview (`student_profile.json`).
   - Quick badges for JECRC University and Jaipur, Rajasthan.

2. **About Me**:
   - Student-friendly professional story.
   - Core Focus Pillars: *Artificial Intelligence & Gen AI*, *Modern Web Development*, and *Digital Productivity & Systems*.
   - Academic facts and personal engineering philosophy.

3. **Education**:
   - Degree: **Bachelor of Technology (B.Tech)**.
   - University: **JECRC University, Jaipur, Rajasthan**.
   - Coursework highlights: Data Structures & Algorithms, AI & Gen AI Foundations, Web Development, Databases, Digital Productivity.

4. **Skills**:
   - Interactive cards with proficiency meters for:
     - HTML
     - CSS
     - JavaScript
     - Python
     - Artificial Intelligence
     - Generative AI
     - Web Development
     - Digital Productivity
   - Category filtering (*All, AI & Emerging Tech, Programming, Web & Frontend, Tools & Systems*).

5. **Projects**:
   - **Personal Portfolio Website** (React, Vite, Tailwind CSS, Lucide Icons)
   - **AI Website Project** (Generative AI, Python, React, LLM APIs)
   - **Student Productivity Project** (React, LocalStorage, Pomodoro study timers)
   - Interactive **Project Details Modal** with full engineering highlights and GitHub links.

6. **Achievements**:
   - Organized tabs for *Certifications, Hackathons, Courses, Awards*.
   - Verified student milestone badges.
   - Extensible template to add new achievements easily.

7. **Contact**:
   - Official Email: `ajaybagherwal@gmail.com` with **1-click Copy to Clipboard** and instant toast feedback.
   - Direct links to **LinkedIn** and **GitHub**.
   - Interactive contact form with client-side validation and mailto drafting.
   - Current location indicator (Jaipur, Rajasthan, India).

8. **Footer**:
   - Quick navigation links, social icons, and back-to-top smooth scroll button.

---

## ⚡ Instant Preview (Zero Installation Required)

You can preview the entire website **immediately in any browser** without installing Node.js:

1. In Windows File Explorer, open `C:\ONIK portfolio`.
2. Double-click **`preview.html`** (or right-click → Open With → Chrome / Edge / Firefox).
3. The full interactive website will open with working modals, responsive drawers, toast notifications, and smooth scrolling!

---

## 💻 Running the React + Vite App Locally

When you have Node.js installed:

```bash
# 1. Open terminal in the project directory
cd "C:\ONIK portfolio"

# 2. Install dependencies
npm install

# 3. Start local Vite development server
npm run dev

# 4. Open in your browser (default: http://localhost:3000)
```

To create a production build:
```bash
npm run build
```

---

## 🚀 Deploying to Vercel

This portfolio is pre-configured for **Vercel** with `vercel.json` and standard Vite build outputs.

### Method 1: Deploy via GitHub (Recommended)
1. Push your project folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) and click **"Add New Project"**.
3. Import your GitHub repository.
4. Framework Preset will auto-detect as **Vite**.
5. Click **"Deploy"**!

### Method 2: Deploy via Vercel CLI
```bash
npx vercel
```
Follow the simple prompts in your terminal and your site will be live on a custom `.vercel.app` URL within seconds!

---

## ✏️ Customizing Your Content

All data (bio, email, university details, skills, projects, achievements, and social links) is centralized in:
```
src/data/portfolioData.js
```
Simply edit this file to update any information across the entire website.
