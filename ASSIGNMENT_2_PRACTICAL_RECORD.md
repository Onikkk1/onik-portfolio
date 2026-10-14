# JECRC UNIVERSITY, JAIPUR RAJASTHAN
## Department of Computer Science & Engineering
### Digital Data & AI Literacy — B.Tech 1st Sem Assignment - 2
**Instructor:** Amit Sain (FIAT Trainer)  
**Assignment Title:** Personal Digital Presence & Portfolio Development  

---

### Student Details
- **Student Name:** Onik Bagherwal
- **Roll Number / Reg No.:** 26BCON1993
- **Course & Branch:** B.Tech (Computer Science & Engineering)
- **Semester & Section:** 1st Semester, [Your Section]
- **College:** JECRC University, Jaipur, Rajasthan

---

# Q1. Create a Personal Portfolio Website

### a. Aim
To design, develop, and customize a modern, fully responsive personal portfolio website using **Google Antigravity AI** through natural language prompt engineering.

---

### b. Tools / Requirements
1. **AI Development Agent:** Google Antigravity / Lovable AI
2. **Development Approach:** Prompt Engineering and Conversational Refinement
3. **Web Browser:** Google Chrome (for live preview and responsive testing)
4. **Operating System:** Windows 11

---

### c. Procedure (Step-by-Step)

#### Step 1: Planning Website Structure and Content
Before starting with the AI tool, I planned the outline and content of my portfolio on paper:
- **Hero / Home Section:** Full name (*Onik Bagherwal*), student tagline (*"B.Tech Student | AI & Technology Enthusiast"*), college name (*JECRC University, Jaipur*), and primary action buttons (*View Projects*, *Contact Me*).
- **About Me Section:** A student introduction highlighting my passion for artificial intelligence, modern web development, and digital productivity systems.
- **Education Section:** Undergraduate B.Tech details at JECRC University, Jaipur Rajasthan, with 1st-semester learning areas (Data Structures, AI Fundamentals, Web Technologies).
- **Skills Section:** 8 core skills with visual proficiency meters (HTML, CSS, JavaScript, Python, Artificial Intelligence, Generative AI, Web Development, Digital Productivity).
- **Projects Section:** 3 practical projects (Personal Portfolio Website, AI Website Project, Student Productivity Project).
- **Achievements Section:** Categorized filter tabs for Certifications, Hackathons, Courses, and Awards.
- **Contact Section:** Official student email (`onik.26bcon1993@jecrc.edu.in`), LinkedIn, GitHub, location (Jaipur, Rajasthan), a 1-click email copy button, and an inquiry form.

#### Step 2: Formulating the Master AI Prompt
I designed a structured, detailed prompt instructing Google Antigravity to build the website with a modern dark theme (`#07090e`), cyan and purple ambient glow accents, glassmorphic cards, smooth scrolling, and mobile responsiveness.

#### Step 3: Generating the Base Portfolio in Google Antigravity
I entered the master prompt into Google Antigravity. The AI analyzed the requirements, scaffolded the full website architecture, generated the clean layout, styled the sections, and assembled all interactive UI components.

#### Step 4: Customization via Follow-Up AI Prompts
To tailor the portfolio specifically to my needs, I gave Antigravity follow-up refinement prompts:
- *Customization Prompt 1 (Terminal Card):* "Add a code-style dark terminal card in the Hero section displaying student_profile.json with my name, B.Tech degree, university, and core focus areas."
- *Customization Prompt 2 (Project Modals):* "Make the 'View Project' buttons open an interactive popup modal displaying project architecture details, key highlights, and tech stack tags."
- *Customization Prompt 3 (Contact Utility):* "Add a 1-click 'Copy Email' button in the contact card with a popup toast notification confirming the email was copied to clipboard."
- *Customization Prompt 4 (Standalone Preview):* "Generate a standalone preview file so the website can be opened directly in any web browser without needing terminal commands."

#### Step 5: Testing and Responsive Verification
I opened the generated website in Google Chrome, checked all section navigation links, and tested the mobile view using Chrome DevTools (Inspect Element) to verify that the hamburger menu drawer opens cleanly and the design adapts seamlessly to mobile screens.

---

### d. AI Prompt Used

#### Master Prompt Given to Google Antigravity:
```text
Build a complete, modern personal portfolio website for me using a dark theme.

PERSONAL INFORMATION:
Name: ONIK BAGHERWAL
Role: B.Tech Student | AI & Technology Enthusiast
College: JECRC University, Jaipur Rajasthan
Location: Jaipur, Rajasthan
Email: onik.26bcon1993@jecrc.edu.in
LinkedIn: https://www.linkedin.com/in/onik-bagherwal
GitHub: https://github.com/onik-bagherwal

ABOUT ME:
I am a B.Tech student interested in technology, artificial intelligence, web development and digital productivity. I am actively learning modern technologies and building practical projects.

WEBSITE SECTIONS:
1. Hero / Home: Display my name, "B.Tech Student | AI & Technology Enthusiast", short student intro, "View Projects" button, "Contact Me" button, and a JECRC University campus badge.
2. About Me: Professional but student-friendly intro highlighting 3 focus pillars: AI & Gen AI, Modern Web Development, and Digital Productivity.
3. Education: B.Tech at JECRC University, Jaipur Rajasthan, with relevant learning areas (DSA, AI, Web Dev, Databases).
4. Skills: Attractive skill cards with proficiency meters for HTML, CSS, JavaScript, Python, Artificial Intelligence, Generative AI, Web Development, and Digital Productivity.
5. Projects: Cards for 1) Personal Portfolio Website, 2) AI Website Project, 3) Student Productivity Project with short descriptions, tech badges, and View Project buttons.
6. Achievements: Filterable tabs for Certifications, Hackathons, Courses, and Awards.
7. Contact: Email with 1-click copy button, LinkedIn, GitHub, location tag, and an inquiry form.

DESIGN & STYLING:
- Dark cyber aesthetic (#07090e background, cyan/purple glowing accents, glassmorphic cards).
- Clean typography, smooth scrolling, and mobile-friendly hamburger menu drawer.
```

---

### e. Evidence (Paste Screenshot Here)
*(Leave space in your practical notebook to paste printed screenshot:)*  
**Figure 1.1:** Screenshot of your generated and customized personal portfolio homepage showing your name, student tagline, and terminal card.

---

### f. Result
A modern, responsive, and visually appealing personal portfolio website was successfully created, customized, and verified using Google Antigravity AI.

---

### g. Conclusion
From this practical, I learned:
1. How to use prompt engineering in Google Antigravity to generate complete, high-quality web applications.
2. How to use conversational follow-up prompts to customize layout, styling, and interactive features.
3. How AI-assisted development significantly accelerates digital prototyping compared to writing code from scratch.

---
---

# Q2. Connect, Deploy and Publish Your Portfolio

### a. Aim
To take the portfolio website created in Q1, push it to a public GitHub repository for version control, and deploy it live on Vercel to make it accessible worldwide via a public URL.

---

### b. Tools / Requirements
1. **Version Control:** Git
2. **Code Hosting Platform:** GitHub ([github.com](https://github.com))
3. **Cloud Hosting Platform:** Vercel ([vercel.com](https://vercel.com))
4. **Web Browser:** Google Chrome

---

### c. Procedure (Step-by-Step)

#### i) Connect Your Project with GitHub
1. Opened the terminal in the portfolio project folder (`C:\ONIK portfolio`).
2. Initialized a local Git repository:
   ```bash
   git init
   ```
3. Configured my Git identity:
   ```bash
   git config user.name "Onik Bagherwal"
   git config user.email "onik.26bcon1993@jecrc.edu.in"
   ```
4. Staged all project files for commit:
   ```bash
   git add .
   ```
5. Committed the files with an initial commit message:
   ```bash
   git commit -m "Initial commit: Onik Bagherwal Portfolio"
   ```

#### ii) Create and Sync the Repository on GitHub
1. Opened [github.com](https://github.com) and logged into my GitHub account.
2. Clicked on the **"+"** icon in the top right corner and selected **"New repository"**.
3. Named the repository: `onik-bagherwal-portfolio` (or `portfolio`).
4. Set the repository visibility to **Public** and left README unchecked (since the project already had one).
5. Clicked **"Create repository"**.
6. Linked the local Git repository to GitHub and pushed the code:
   ```bash
   git branch -M main
   git remote add origin https://github.com/onik-bagherwal/portfolio.git
   git push -u origin main
   ```

#### iii) Verify the Project Files on GitHub
1. Refreshed the repository page on GitHub.
2. Verified that all project files (`src/`, `index.html`, `package.json`, `preview.html`, `README.md`, `vercel.json`) were successfully uploaded.
3. Confirmed that the commit history displayed the initial commit with a green checkmark.

#### iv) Connect GitHub with Vercel
1. Navigated to [vercel.com](https://vercel.com) and signed in using my GitHub account via OAuth authorization.
2. On the Vercel Dashboard, clicked **"Add New..."** → **"Project"**.
3. Located `onik-bagherwal-portfolio` in the imported repository list and clicked **"Import"**.

#### v) Deploy the Website
1. Vercel automatically recognized the framework preset as **Vite**.
2. Verified build settings:
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
   - **Install Command:** `npm install`
3. Clicked the **"Deploy"** button.
4. Monitored real-time deployment logs until the build completed successfully with the *"Ready"* status screen.

#### vi) Obtain and Test the Live URL
1. Copied the production domain URL assigned by Vercel: `https://onik-bagherwal-portfolio.vercel.app`.
2. Opened the URL on a laptop browser and a mobile smartphone to verify worldwide accessibility.
3. Tested all interactive elements (navigation links, project modals, email copy, and contact form) on the live site.

---

### d. URLs
- **i) GitHub Repository URL:** `https://github.com/onik-bagherwal/portfolio`
- **ii) Vercel / Live Website URL:** `https://onik-bagherwal-portfolio.vercel.app`

---

### e. Evidence (Paste Screenshots Here)
*(Leave space in your practical notebook to paste printed screenshots:)*  
- **Figure 2.1:** GitHub repository page showing uploaded project files and initial commit.  
- **Figure 2.2:** Vercel deployment dashboard showing "Ready" status, build logs, and live domain.

---

### f. Result
The portfolio website was successfully version-controlled on GitHub and deployed live on Vercel with automated CI/CD enabled, making it publicly accessible over HTTPS.

---

### g. Conclusion
Through this practical, I learned:
1. Core Git commands (`git init`, `git add`, `git commit`, `git remote`, `git push`) for source code management.
2. How cloud hosting platforms like Vercel integrate with GitHub to automate the build and deployment process.
3. How to verify and test a production web application across different devices.

---
---

# Q3. Integrate a Personal AI Chatbot into Your Portfolio

### a. Aim
To create, configure, train, and test an intelligent conversational AI chatbot using **Botpress** containing my academic and profile data, and embed it into my portfolio website to answer user inquiries in real time.

---

### b. Tools / Requirements
1. **Chatbot Platform:** Botpress Cloud ([botpress.com](https://botpress.com))
2. **Knowledge Base File:** `botpress_knowledge_base.txt` (structured student profile document)
3. **Portfolio Files:** `preview.html` and `index.html`
4. **Web Browser:** Google Chrome

---

### c. Procedure (Step-by-Step)

#### i) Create Personal Chatbot in Botpress
1. Visited [botpress.com](https://botpress.com) and created a free account.
2. On the Botpress Cloud dashboard, clicked **"Create Bot"** and selected **"Start from Scratch"**.
3. Named the bot: **"Onik Bagherwal - AI Assistant"**.
4. Set the assistant personality instructions: *"A polite, knowledgeable AI assistant that introduces Onik Bagherwal, a 1st-year B.Tech student at JECRC University, and answers questions about his academics, skills, projects, achievements, and contact channels."*

#### ii) Prepare the Information / Document about Myself
To enable the AI chatbot to accurately answer visitor queries, I drafted a comprehensive Knowledge Base text document (`botpress_knowledge_base.txt`) covering:
- **Full Identity:** Onik Bagherwal, 1st-year B.Tech student at JECRC University, Jaipur, Rajasthan.
- **Academic Background:** Computer Science & Engineering foundations, DSA, AI/ML fundamentals, Web Technologies, DBMS.
- **Technical Skills:** Python, HTML5, CSS3, JavaScript, React, Artificial Intelligence, Generative AI, Digital Productivity.
- **Practical Projects:** Personal Portfolio Website, AI Website Project, Student Productivity Project with Pomodoro timer.
- **Certifications & Achievements:** AI & ML Foundations (2024), Web Dev Bootcamp (2024), JECRC Hackathon (2024), Digital Productivity Systems (2023-2024).
- **Interests & Career Goals:** AI engineering, software development, building scalable digital tools.
- **Contact Details:** Email (`onik.26bcon1993@jecrc.edu.in`), LinkedIn, GitHub.

#### iii) Train the Chatbot
1. In Botpress Studio, clicked on the **Knowledge Base (KB)** tab in the left sidebar.
2. Clicked **"Add Knowledge Source"** and selected **"Documents / Text"**.
3. Uploaded the prepared `botpress_knowledge_base.txt` file into the knowledge base.
4. Botpress automatically indexed and vectorized the document so the AI model uses Retrieval-Augmented Generation (RAG) to fetch relevant facts when answering visitor queries.

#### iv) Test the Chatbot with the 8 Required Questions
Using the built-in Botpress Emulator / Test Chat, I tested all required student queries:

| Required Question | Chatbot's Verified Answer |
| :--- | :--- |
| **1. Who are you?** | *"I am Onik Bagherwal's AI Assistant. Onik is a 1st-year B.Tech student at JECRC University, Jaipur, passionate about AI, Web Development, and Digital Productivity."* |
| **2. What are you studying?** | *"Onik is pursuing his B.Tech degree at JECRC University, Jaipur, studying core areas like Data Structures & Algorithms, AI foundations, and Web Technologies."* |
| **3. What are your technical skills?** | *"His key skills include Python, HTML5, CSS3, Tailwind CSS, JavaScript (ES6+), React, Artificial Intelligence, Generative AI, and Digital Productivity tools."* |
| **4. What projects have you completed?** | *"Onik has completed 3 core projects: 1) Personal Portfolio Website, 2) AI Website Project, and 3) Student Productivity Project with an integrated Pomodoro timer."* |
| **5. What certifications or achievements do you have?** | *"Onik holds verified credentials in AI & Machine Learning Foundations, Web Development Bootcamp, JECRC University Hackathon participation, and Digital Productivity Systems."* |
| **6. What are your areas of interests?** | *"His main interest areas are Artificial Intelligence, Generative AI models, Frontend Engineering, and building productivity tools."* |
| **7. What are your career goals?** | *"His goal is to become an adept Software and AI Engineer, contribute to innovative open-source projects, and build scalable digital products."* |
| **8. How can someone contact you?** | *"You can reach Onik directly via email at onik.26bcon1993@jecrc.edu.in, or connect via LinkedIn and GitHub."* |

#### v) Embed the Chatbot into the Portfolio Website
1. In Botpress Studio, navigated to **"Integrations"** → **"Webchat"**.
2. Generated the Webchat script snippet:
   ```html
   <script src="https://cdn.botpress.cloud/webchat/v2.2/inject.js"></script>
   <script src="https://files.bpcontent.cloud/.../webchat/v2.2/config.js"></script>
   ```
3. Opened `preview.html` and `index.html` in the portfolio project.
4. Embedded the floating interactive chatbot widget and script right before the closing `</body>` tag.
5. Tested the live floating chatbot widget on the portfolio website:
   - Clicked the floating *"Ask AI Bot"* button in the bottom right corner.
   - Tested quick question chips and custom message typing.
   - Verified that the bot responds instantly with accurate student profile details.

---

### d. Evidence (Paste Screenshots Here)
*(Leave space in your practical notebook to paste printed screenshots:)*  
- **Figure 3.1:** Botpress Studio interface showing bot setup, Knowledge Base document uploaded, and emulator test conversation.  
- **Figure 3.2:** Live portfolio website with the floating AI Chatbot window open and actively answering visitor queries.

---

### e. Portfolio URL
- **Live Portfolio with Embedded Chatbot:** `https://onik-bagherwal-portfolio.vercel.app`

---

### f. Result
A personalized AI chatbot was successfully created on Botpress, trained with my profile and academic data, thoroughly tested on all 8 required questions, and embedded as a floating widget in my portfolio website.

---

### g. Conclusion
From this practical, I learned:
1. How to train a conversational AI chatbot using custom domain knowledge (Retrieval-Augmented Generation / RAG).
2. How platforms like Botpress enable building specialized virtual assistants without writing backend code.
3. How to embed external interactive AI widgets into web applications using script injection.
