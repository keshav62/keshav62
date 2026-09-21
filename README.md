<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,50:4A00E0,100:00C9FF&height=240&section=header&text=Keshav%20Singh&fontSize=64&fontColor=ffffff&fontAlignY=38&animation=twinkling&desc=Full%20Stack%20%E2%80%A2%20GenAI%20%E2%80%A2%20AI%2FML&descSize=20&descAlignY=60" width="100%" alt="header" />

<a href="https://github.com/keshav62">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=8E2DE2&center=true&vCenter=true&random=false&width=720&height=50&lines=Building+full-stack+apps+that+ship+%F0%9F%9A%80;Turning+LLMs+into+real+products+%F0%9F%A4%96;Multi-agent+systems+%26+RAG+pipelines+%F0%9F%A7%A0;600%2B+DSA+problems+solved+%F0%9F%A7%A9;Build+%E2%86%92+Break+%E2%86%92+Debug+%E2%86%92+Learn+%E2%86%92+Repeat" alt="Typing animation" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=keshav62&label=Profile%20Views&color=8E2DE2&style=for-the-badge" alt="Profile Views" />
<img src="https://img.shields.io/github/followers/keshav62?label=Followers&style=for-the-badge&color=4A00E0&logo=github" alt="Followers" />
<img src="https://img.shields.io/badge/Based%20in-India%20%F0%9F%87%AE%F0%9F%87%B3-00C9FF?style=for-the-badge" alt="Location" />
<img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-2ea44f?style=for-the-badge" alt="Status" />

<br/><br/>

**[About](#-about)** • **[Projects](#-featured-projects)** • **[Tech Stack](#-tech-stack)** • **[Stats](#-github-stats)** • **[Contact](#-lets-connect)**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8E2DE2,100:00C9FF&height=3" width="100%" alt="divider" />

</div>

## 👨‍💻 About

I'm a **Full Stack Developer from India** who loves building real-world products at the intersection of **software engineering, Machine Learning and Generative AI**. I learn fastest by shipping, and I care about understanding *why* something works, not just making it work.

```js
const keshav = {
  role: "Full Stack Developer",
  focus: ["Generative AI", "LLMs", "RAG", "AI Agents", "Machine Learning"],
  building: ["MPLADS Drishti", "ResearchHive AI", "AI-powered SaaS"],
  learning: ["Next.js App Router", "TypeScript", "System Design", "Docker"],
  motto: "Don't just make it work. Understand why it works.",
};
```

| 💻 Full-Stack Apps | 🤖 GenAI & Agents | 📊 ML & Analytics | ⚡ Real-Time |
| :---: | :---: | :---: | :---: |
| React, Next.js, Node, FastAPI | LangChain, LangGraph, RAG | Pandas, Scikit-learn, Isolation Forest | WebSockets, Socket.io |

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8E2DE2,100:00C9FF&height=3" width="100%" alt="divider" />
</div>

## 🏆 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏛️ MPLADS Drishti
**AI project monitoring & risk intelligence** for government development projects: anomaly detection, investigations, RBAC and AI-generated reports.

`React` `Node.js` `FastAPI` `Scikit-learn` `Supabase` `Prisma`

[Repository](https://github.com/keshav62/mplads_ai) • [SIH2026](https://github.com/keshav62/SIH2026_techhustlers)

</td>
<td width="50%" valign="top">

### 🔬 ResearchHive AI
**Multi-agent research system.** Scout, Researcher and Critic agents search, scrape, verify and write the final report.

`Python` `FastAPI` `LangGraph` `LangChain` `Tavily` `Groq` `React`

[Repository](https://github.com/keshav62/ResearchHive-AI-A-Multi-Agent-Research-System)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎓 CourseMate AI
**RAG study assistant.** Upload PDFs and get answers grounded in your own material, with source references.

`Python` `LangChain` `Gemini` `ChromaDB` `HuggingFace`

[Repository](https://github.com/keshav62/CourseMate-AI-Using-RAG)

</td>
<td width="50%" valign="top">

### 🧠 Intervue AI
**AI interview platform** with mock interviews, system design practice, an AI co-pilot and progress analytics.

`Next.js` `TypeScript` `Gemini` `Prisma` `PostgreSQL` `Stream Video`

[Repository](https://github.com/keshav62/AI-Powered-Interview-Platform-)

</td>
</tr>
</table>

<details>
<summary><b>🏗️ MPLADS Drishti — architecture</b></summary>

```mermaid
flowchart TD
    A[React Dashboard] --> B[Node.js API Gateway]
    B --> C[(Supabase / Prisma)]
    B --> D[FastAPI ML Engine]
    D --> E[Pandas Feature Engineering]
    E --> F[Isolation Forest]
    F --> G[Risk / Anomaly Score]
    G --> B
```

**Highlights:** Isolation Forest anomaly detection • investigation management • AI-assisted reports • role-based and data-level security • State / District / Constituency filtering • time-series and financial analytics.

</details>

<details>
<summary><b>🤖 ResearchHive AI — agent workflow</b></summary>

```mermaid
flowchart LR
    Q[User Query] --> S[🔭 Scout Agent]
    S --> T[🌐 Tavily Search]
    T --> R[🔬 Researcher Agent]
    R --> C[🧐 Critic Agent]
    C -->|needs more| S
    C -->|verified| F[📝 Final Report]
```

**Highlights:** specialised agents instead of one do-everything model • web search and scraping • source collection • automated, quality-checked reports.

</details>

### 🚀 More Projects

<details>
<summary><b>AI &amp; SaaS</b></summary>
<br/>

| Project | What it does | Stack | Link |
| :-- | :-- | :-- | :-: |
| 🤖 **MindGPT** | AI chat + image generation SaaS with Stripe credits, voice-to-text, chat sessions and community gallery | React, Node, MongoDB, Gemini, ImageKit, Stripe | [Repo](https://github.com/keshav62/-MindGPT---AI-Chat-Image-Generator-SaaS-MERN-Gemini-Stripe-) |
| 🎨 **Text-to-Image SaaS** | Prompt-to-image generator with credits, pricing plans and downloads | React, Node, MongoDB, Clipdrop API | [Repo](https://github.com/keshav62/AI-Text-to-Image-Generator-SaaS-) |
| 🏙️ **City Intelligence Agent** | Tool-using agent for live weather, news and web search about any city | Python, LangChain, Gemini, Tavily | [Repo](https://github.com/keshav62/City-Intelligence-Agent) |

</details>

<details>
<summary><b>Full-stack platforms</b></summary>
<br/>

| Project | What it does | Stack | Link |
| :-- | :-- | :-- | :-: |
| 🏛️ **CivicConnect** | Civic issue reporter with GPS, maps, heatmaps and citizen / admin / field-worker roles | React, Node, Express, Maps | [Repo](https://github.com/keshav62/Pothole-Civic-Issue-Reporter-with-Map-View) |
| 📚 **LibraFlow** | Library management and digital catalog | Next.js 16, React 19, TS, Clerk, Prisma | [Repo](https://github.com/keshav62/Library-Management-System) |
| 🎓 **Learning Management System** | Courses, video lectures, progress tracking, Stripe payments | React, Node, MongoDB, Clerk, Stripe | [Repo](https://github.com/keshav62/LEARNING-MANAGEMENT-SYSTEM) |
| 💬 **Real-Time Chat** | Instant messaging with typing indicators, read receipts and presence | React, Socket.io, MongoDB, JWT | [Repo](https://github.com/keshav62/RealTime-Chat-Application-) |
| 📦 **Inventory System** | Stock tracking, EOQ calculation, reorder alerts, procurement | Node, MongoDB | [Repo](https://github.com/keshav62/inventory-system) |

</details>

<details>
<summary><b>Learning &amp; experiments</b></summary>
<br/>

[🛒 Amazon Clone](https://github.com/keshav62/Amazon-clone) •
[🎬 Netflix Clone](https://github.com/keshav62/Netflix-clone) •
[📖 Bright Future](https://github.com/keshav62/BRIGHT-FUTURE) •
[🏗️ System Design](https://github.com/keshav62/SYSTEM-DESIGN) •
[💻 Operating System](https://github.com/keshav62/Operating_System) •
[🏆 Hackathon](https://github.com/keshav62/hackathon) •
[🚀 Itzfizz](https://github.com/keshav62/Itzfizz)

</details>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8E2DE2,100:00C9FF&height=3" width="100%" alt="divider" />
</div>

## 🛠️ Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=cpp,java,python,js,ts,html,css&theme=dark" alt="Languages" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,bootstrap&theme=dark" alt="Frontend" />

**Backend**<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,fastapi&theme=dark" alt="Backend" />

**Databases**<br/>
<img src="https://skillicons.dev/icons?i=mongodb,mysql,postgres,supabase,prisma&theme=dark" alt="Databases" />

**AI / ML**<br/>
<img src="https://skillicons.dev/icons?i=pandas,sklearn&theme=dark" alt="ML" /><br/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge" alt="LangChain" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="HuggingFace" />
<img src="https://img.shields.io/badge/RAG-8E2DE2?style=for-the-badge" alt="RAG" />
<img src="https://img.shields.io/badge/AI_Agents-4A00E0?style=for-the-badge" alt="AI Agents" />

**Auth, Payments & Services**<br/>
<img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
<img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white" alt="Clerk" />
<img src="https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white" alt="Stripe" />
<img src="https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white" alt="Cloudinary" />
<img src="https://img.shields.io/badge/ImageKit-00AEEF?style=for-the-badge" alt="ImageKit" />

**Tools**<br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,postman,vscode,vercel&theme=dark" alt="Tools" />

</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8E2DE2,100:00C9FF&height=3" width="100%" alt="divider" />
</div>

## 🧩 DSA &amp; Problem Solving

**600+ problems solved** across LeetCode and practice sets.

`Arrays & Strings` `Hashing` `Sliding Window` `Two Pointers` `Binary Search` `Prefix Sum` `Linked Lists` `Stack & Queue` `Trees` `Heaps` `Graphs` `BFS / DFS` `Dijkstra` `Topological Sort` `Dynamic Programming` `Segment Trees` `Greedy`

## 🎯 Highlights

- 🏆 Hackathon Winner
- 🤖 Built AI-powered SaaS apps and multi-agent systems
- 📊 Built ML-based risk and anomaly detection
- ⚡ Built real-time apps with WebSockets
- 🚀 Shipped many full-stack applications end to end

## 🌱 Currently Learning

| Area | Focus |
| :-- | :-- |
| 🤖 **GenAI** | Prompt engineering, RAG, agents, tool calling, multi-agent systems |
| ⚛️ **Next.js** | App Router, Server Components, full-stack apps |
| 🔷 **TypeScript** | Advanced types, generics, type-safe architecture |
| 🏗️ **System Design** | Caching, load balancing, distributed systems |
| 🐳 **Docker** | Containers, images, deployment |

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:8E2DE2,100:00C9FF&height=3" width="100%" alt="divider" />
</div>

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/keshav62">
  <img src="https://github-readme-stats.vercel.app/api?username=keshav62&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8E2DE2&icon_color=00C9FF&text_color=FFFFFF" height="180" alt="GitHub Stats" />
</a>
<a href="https://github.com/keshav62">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=keshav62&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=8E2DE2&text_color=FFFFFF" height="180" alt="Top Languages" />
</a>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=keshav62&theme=tokyonight&hide_border=true&background=0D1117&ring=8E2DE2&fire=00C9FF&currStreakLabel=8E2DE2" width="70%" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=keshav62&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" width="90%" alt="Trophies" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=keshav62&theme=react-dark&bg_color=0D1117&color=00C9FF&line=8E2DE2&point=FFFFFF&area=true&hide_border=true" width="95%" alt="Contribution Activity" />

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/keshav62/keshav62/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/keshav62/keshav62/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/keshav62/keshav62/output/github-contribution-grid-snake.svg" />
</picture>

</div>

## 🤝 Let's Connect

<div align="center">

<a href="https://github.com/keshav62"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://linkedin.com/in/keshav62"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:keshav62@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

> *Coffee + Code = Productive Day ☕*

<a href="https://github.com/keshav62">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1500&color=00C9FF&center=true&vCenter=true&width=520&lines=Thanks+for+stopping+by!+%E2%9C%A8;Let's+build+something+great+together." alt="Footer typing" />
</a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,50:4A00E0,100:8E2DE2&height=140&section=footer&animation=fadeIn" width="100%" alt="footer" />

</div>
