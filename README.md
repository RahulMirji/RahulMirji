<h1 align="center">🚀 Rahul Mirji – Agentic AI Engineer | Full Stack AI Builder</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=F76C6C&center=true&vCenter=true&width=600&lines=Building+production+AI+Agent+systems+🤖;Multi-Agent+Orchestration+%7C+Google+ADK+%7C+LangGraph;CI%2FCD+Pipelines+%7C+Cloud+Run+%7C+Docker+🐳;Chrome+Extensions+%7C+Mobile+Apps+📱" />
</p>

<p align="center">
  <a href="https://twitter.com/mirjirahul" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
  </a>
  <a href="https://www.kaggle.com/rahulmirji" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" />
  </a>
  <a href="https://rahulmirji.dev" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-2ECC71?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/rahul-mirji-7764551ba" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:devprahulmirji@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## 🔥 Meet `rahul.js`

```js
const rahul = {
  name: "Rahul Mirji",
  roles: ["Agentic AI Engineer", "Full-Stack AI Builder"],
  stack: ["Google ADK", "LangGraph", "MCP", "Python", "MERN", "FastAPI", "Supabase"],
  currentFocus: [
    "Production Multi-Agent Systems (IP Signals)",
    "CI/CD Pipelines for AI & Mobile Apps",
    "AI Chrome Extensions (TryOnNow)",
    "AI-first product development"
  ],
  cicd: {
    platforms: ["GitHub Actions"],
    targets: ["Google Play Store (.aab)", "App Store Connect (.ipa)"],
    infra: ["Docker", "Google Cloud Run", "GCR", "Workload Identity Federation"],
    practices: ["Reusable Workflows", "Secrets Management", "Caching", "Auto-concurrency cancellation"]
  },
  funFact: "Shipped ~4,500 lines of production code in 24 hours at a national hackathon 🏆"
}
```

---

## 🧠 What I'm Working On

- 🤖 **IP Signals — Production Multi-Agent IP Protection System**
  👉 [ipsignals.ai](https://ipsignals.ai) — Onboarding pilot organizations
  Google ADK · Multi-Agent Orchestration · GCP Cloud Run · Docker · CI/CD

- 👗 **StyleGPT – AI Fashion Assistant**
  👉 Published on Google Play Store
  AI stylist, outfit scoring, virtual try-on, Razorpay payments

- 🧥 **TryOnNow – AI Virtual Try-On Chrome Extension**
  👉 Live on Chrome Web Store
  Works directly on Amazon & Flipkart · Gemini 2.5 Flash · Supabase Edge Functions

- 🎓 **ClassTwin — AI Digital Twin for Live Classrooms**
  👉 3rd Place, SYNTHVERSE 2026 National Hackathon
  RAG · MediaPipe Gaze Tracking · WebRTC · Real-time Risk Engine · ~4,500 lines in 24 hrs

- 🛡 **SecureExam — AI Exam Proctoring Platform**
  Real-time monitoring · Autonomous violation detection

---

## 🚀 Live Products

| Product | Platform | Tech |
|---|---|---|
| 📱 StyleGPT | [Google Play Store](https://play.google.com/store) | React Native, Supabase, Gemini |
| 🌐 TryOnNow Extension | [Chrome Web Store](https://chrome.google.com/webstore) | Gemini 2.5 Flash, Supabase Edge Functions |
| 🔒 IP Signals | [ipsignals.ai](https://ipsignals.ai) | Google ADK, GCP Cloud Run, Docker |
| 🎓 SecureExam | AI Proctoring Platform | Real-time CV, LLMs |
| 🖥 Shana 2.0 | Desktop AI Assistant | Tauri |

---

## ⚙️ CI/CD Pipelines — What I've Built

> I've designed and shipped end-to-end automated release pipelines for both mobile and AI backends.

### 📦 Android Pipeline (GitHub Actions → Google Play Store)
- **Ubuntu runner** builds signed `.aab` with Flutter
- **Keystore secrets** decoded from Base64 at runtime — never stored in code
- **Reusable `ci.yml`** for linting & tests; build jobs only run after CI passes
- **Workload Identity Federation (OIDC)** — passwordless GCP auth, no JSON keys exposed
- **Dynamic build numbers** via `github.run_number` — no duplicate rejection from Play Store
- **Gradle caching** via `actions/cache` — faster builds on every run

### 🍎 iOS Pipeline (GitHub Actions → TestFlight / App Store Connect)
- **macOS runner** — ephemeral Apple VM with Xcode pre-installed
- **Temporary Keychain sandbox** — `.p12` certificate + `.mobileprovision` injected securely
- **CocoaPods caching** using `hashFiles('Podfile.lock')` — cuts build times by 70%+
- **`xcrun altool`** for native App Store Connect upload — zero Fastlane dependency
- **Concurrency cancellation** — new push auto-kills the previous in-progress pipeline

### 🐳 AI Backend Pipeline (Docker → Google Cloud Run)
- Every release auto-builds a Docker image of the multi-agent backend
- Pushes to **Google Container Registry (GCR)** and deploys to **Cloud Run**
- Agents run as containerized microservices — isolated, scalable, independently deployable

```yaml
# Sample concurrency config I use
concurrency:
  group: android-build-${{ github.ref }}
  cancel-in-progress: true
```

---

## 🧰 Tech Stack & Tools

### 🤖 Agentic AI & LLMs
<p>
  <img src="https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-FF6B35?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-FF4B4B?style=for-the-badge" />
</p>

### ☁️ Cloud, DevOps & CI/CD
<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Google_Cloud_Run-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/GCR-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/GCS-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
</p>

### 🖥 Full Stack & Backend
<p>
  <img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,mongodb,typescript,javascript,python,fastapi,supabase,vercel,linux,git" />
</p>

---

## 🏆 Achievements

- 🥇 **1st Place** — Technovate 2K26 Mini Project Expo (HKBK + IEEE) · ClassTwin
- 🥉 **3rd Place** — SYNTHVERSE 2026 National Hackathon (BMSCE IEEE) · ClassTwin
- 🥉 **3rd Place** — AI Verse 1.0 National Hackathon · Voice Sentiment Agent
- 🥇 **1st Place** — ISTE App Development Contest · Gemini Vision Injury-Care App
- 🏅 **Top 10** — AI Verse 2.0 National Hackathon · SecureExam AI Proctoring
- 📱 Play Store published app (StyleGPT)
- 🌐 Chrome Web Store published extension (TryOnNow)
- 🤖 Production multi-agent system live at ipsignals.ai
- 🛠 End-to-end CI/CD pipelines for Android (.aab) and iOS (.ipa) deployments

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rahulmirji&show_icons=true&theme=radical" height="180"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rahulmirji&layout=compact&theme=radical" height="180"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=rahulmirji&theme=radical" height="180"/>
</p>

---

## ✨ Let's Build Together

💬 Open to AI product collaborations, agentic system design & hackathons
📩 Email: [devprahulmirji@gmail.com](mailto:devprahulmirji@gmail.com)
🌍 GitHub: [https://github.com/RahulMirji](https://github.com/RahulMirji)
🔗 LeetCode: [rahulmirji07](https://www.leetcode.com/rahulmirji07)

<p align="center"><b>📍 Bengaluru, India | #BuildInPublic | #AgenticsEngineer</b></p>
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=rahulmirji&label=Profile%20Views&color=blueviolet&style=flat-square" />
</p>
