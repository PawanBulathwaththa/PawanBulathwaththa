<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f2027,50:203a43,100:6DB33F&height=230&section=header&text=Pawan%20Bulathwaththa&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20%C2%B7%20Enterprise%20Java%20%C2%B7%20Cloud-Native%20%C2%B7%20AI-Curious&descAlignY=60&descSize=17" width="100%"/>

<a href="https://github.com/pawanbulathwaththa">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&color=6DB33F&center=true&vCenter=true&width=720&lines=%24+sudo+build+scalable+things;Spring+Boot+%E2%86%92+Next.js+%E2%86%92+Docker+%E2%86%92+Production;I+turn+coffee+into+REST+APIs+%E2%98%95;I+write+tests+so+bugs+can't+hide+%F0%9F%8E%AD;Undergrad+%40+Coventry+%C3%97+NIBM+%7C+Colombo%2C+Sri+Lanka+%F0%9F%87%B1%F0%9F%87%B0" alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=pawanbulathwaththa&label=VISITORS&color=6DB33F&style=for-the-badge)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-203a43?style=for-the-badge&logo=githubpages&logoColor=white)](https://pawanbulathwaththa.github.io/my_portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pawan-bulathwaththa-99a51733b)
[![Gmail](https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pawanbulatwaththa@gmail.com)

</div>

---

## 🌱 `Application Started`

Like a Spring Boot app, this profile boots up with a banner. Scroll to see what's running. 👇

```text
  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Pawan Bulathwaththa ::          (v2026.0.1)

 INFO  --- Starting Developer on Colombo, LK with PID 1337
 INFO  --- Active profile(s): fullstack, backend-leaning, curious
 INFO  --- Loading beans: Java ✓  TypeScript ✓  PostgreSQL ✓  Docker ✓
 INFO  --- Keycloak realm connected ✓  OAuth2 tokens flowing ✓
 INFO  --- Playwright watching for regressions 👀
 INFO  --- Started Pawan in 3.2 seconds (JVM running for ∞ ambition)
 HTTP  --- GET /hire-me  →  200 OK 🟢  (open to opportunities)
```

---

## 👨‍💻 `GET /about`

```java
@Entity
public class Pawan implements Developer {

    private String role      = "Associate Software Engineer";
    private String location  = "Colombo, Sri Lanka 🇱🇰";
    private String studying  = "BSc (Hons) CS with Software Engineering, Coventry University";
    private String baseCamp  = "NIBM City University (Kandy)";

    private List<String> superpowers = List.of(
        "Enterprise backends with Spring Boot",
        "Modern UIs with Next.js + TypeScript",
        "Secure auth with Keycloak & OAuth 2.0",
        "Containers, VPS, Traefik & Cloudflare",
        "End-to-end testing that actually catches bugs"
    );

    public String currentlyExploring() {
        return "Agentic AI · Model Context Protocol (MCP) · LLM integration";
    }

    public String funFact() {
        return "Built a talking, gesture-controlled robot powered by Gemini AI 🤖";
    }
}
```

---

## 🏗️ `My Typical Architecture`

> The kind of system I like to ship, from the browser all the way to a secured, containerized production edge.

```mermaid
flowchart LR
    U([👤 User]) --> CF[☁️ Cloudflare<br/>Proxy · SSL · HSTS]
    CF --> TR[🚦 Traefik<br/>Ingress]
    TR --> FE[⚛️ Next.js<br/>TypeScript · Tailwind]
    FE -->|REST| BE[☕ Spring Boot<br/>Microservices · MVC]
    BE --> KC[🔐 Keycloak<br/>OAuth 2.0 · RBAC]
    BE --> PG[(🐘 PostgreSQL)]
    BE --> MG[(🍃 MongoDB)]
    BE -.->|LLM APIs| AI[🤖 Gemini · OpenAI · Claude]
    PW{{🎭 Playwright<br/>E2E tests}} -.->|guards| FE
    JU{{✅ JUnit 5 + Mockito}} -.->|guards| BE
    DK[🐳 Docker + Coolify] -.->|deploys| TR

    style CF fill:#F38020,color:#fff
    style FE fill:#000,color:#fff
    style BE fill:#6DB33F,color:#fff
    style KC fill:#4D4D4D,color:#fff
    style PG fill:#336791,color:#fff
    style MG fill:#47A248,color:#fff
    style DK fill:#2496ED,color:#fff
```

---

## 🧰 `Tech Stack`

<div align="center">

### 🔙 Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=for-the-badge&logo=keycloak&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth_2.0-EB5424?style=for-the-badge&logo=auth0&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

### 🎨 Frontend
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin_Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)

### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### 🧪 Testing & Quality
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![JUnit5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78A641?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

### ☁️ DevOps & Infra
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux_VPS-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Coolify](https://img.shields.io/badge/Coolify-6B16ED?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### 🤖 AI & Tooling
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model_Context_Protocol-000000?style=for-the-badge)
![Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

</div>

---

## 🎮 `Skill Levels` (RPG style)

```text
☕ Java / Spring Boot    ████████████████████░░  Lv. 18  "Backend Knight"
⚛️ Next.js / TypeScript  ██████████████████░░░░  Lv. 16  "Frontend Mage"
🔐 Keycloak / OAuth2     ████████████████░░░░░░  Lv. 14  "Gatekeeper"
🎭 Playwright / JUnit    ████████████████░░░░░░  Lv. 14  "Bug Slayer"
🐳 Docker / Traefik / VPS███████████████░░░░░░░  Lv. 13  "Ship Captain"
🤖 LLMs / MCP / Agents   █████████████░░░░░░░░░  Lv. 11  "Apprentice Wizard" (levelling up fast)
```

---

## 🚀 `git log --career`

```text
* a1b2c3d (HEAD -> main) 🧑‍💻 Associate Software Engineer path | Feb 2026 → present
|   Trainee Software Engineer @ DvTechLabs (Pvt) Ltd, Colombo
|   ├─ Shipped full-stack SaaS & e-commerce features (Spring Boot · Next.js · PostgreSQL)
|   ├─ Built secure auth & RBAC with Keycloak + OAuth 2.0
|   ├─ Wrote JUnit 5 / Mockito suites + Playwright E2E regression tests
|   ├─ Architected an isolated staging env on Linux VPS (Docker · Coolify · Traefik)
|   ├─ Locked down the edge: Cloudflare proxy, full SSL termination, strict HSTS
|   └─ Optimized containerized builds for Spring Boot & Next.js (less memory, faster deploys)
|
* e4f5a6b 🎓 BSc (Hons) CS with Software Engineering, Coventry University | 2026
* 7c8d9e0 📘 Higher Diploma in Software Engineering, NIBM | 2024 – 2025
* 1a2b3c4 📗 Diploma in Computer System Design, NIBM | 2023 – 2024
* 0000000 🌱 Initial commit: "hello, world"
```

---

## 🏆 `Featured Projects`

<table>
<tr>
<td width="50%" valign="top">

### 🛒 udaratacomputers.lk
*Live e-commerce platform for a computer store*

Took a local business online so it can sell through its own website.

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)

</td>
<td width="50%" valign="top">

### 🏛️ Smart Hall Management System
*Automatic hall allocation with zero scheduling conflicts*

Role-based access for admins, lecturers and students, secured with Keycloak + OAuth 2.0.

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![Postgres](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Talking Robot with Gemini AI
*Gesture-controlled robot you can actually have a conversation with*

Custom prompt handling, context framing and structured responses for real-time, voice-based Q&A.

![Gemini](https://img.shields.io/badge/Gemini_AI-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![IoT](https://img.shields.io/badge/Hardware_%2B_APIs-333?style=flat-square)

</td>
<td width="50%" valign="top">

### 💧 Smart Water Management System
*IoT platform with an autonomous water controller*

Monitors water quality and manages household usage through web and mobile apps.

![IoT](https://img.shields.io/badge/IoT-0A66C2?style=flat-square)
![Web](https://img.shields.io/badge/Web_%2B_Mobile-333?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔧 FixMyRide
*Breakdown? Find the nearest mechanic.*

Mobile and web app with backend APIs and a smooth user workflow.

![Kotlin](https://img.shields.io/badge/Kotlin_Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Postgres](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)

</td>
<td width="50%" valign="top">

### 🍔 UrbanFood System
*Full-stack food ordering platform*

Catalog, cart and order management. Oracle for core data, MongoDB for reviews and ratings.

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Mongo](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚗 Vehicle Ordering System
*Customer, dealer and admin panels in one platform*

Authentication, data management and backend business logic.

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>
<td width="50%" valign="top">

### ❤️ Heart Disease Prediction Model
*Machine learning on patient data*

Data preprocessing and model evaluation in Python.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![ML](https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square)

</td>
</tr>
</table>

---

## 🎭 `Test Report` (yes, my README has a test suite)

```text
$ npx playwright test --project=pawan

Running 7 tests using 1 worker

  ✓ [pawan] › writes clean, SOLID code                        (always)
  ✓ [pawan] › designs REST APIs people enjoy using            (1.2s)
  ✓ [pawan] › secures apps with Keycloak & OAuth 2.0          (0.9s)
  ✓ [pawan] › deploys to Linux VPS with Docker + Traefik      (2.1s)
  ✓ [pawan] › leads teams (President, Media Club NIBM Kandy)  (2024-25)
  ✓ [pawan] › learns new tech faster than npm installs it     (0.3s)
  ✓ [pawan] › survives code review with a smile 😄            (∞)

  7 passed (0 flaky, 0 skipped)
```

---

## 🧠 `Currently Levelling Up`

| 🎯 Focus | 📌 What I'm doing |
|---|---|
| 🤖 **Agentic AI** | Autonomous agent workflows with the **Model Context Protocol (MCP)**, structured tool/resource invocation and context orchestration |
| 🧬 **LLM Integration** | Gemini · OpenAI · Claude APIs, prompt engineering, vector databases (basics) |
| 🏛️ **Architecture** | Clean Architecture, SOLID, microservices patterns |
| ⚙️ **CI/CD** | Faster, leaner, repeatable deployment pipelines |

---

## 🤝 `Beyond the Code`

- 🎙️ **President**, Media Club of NIBM Kandy (2024 – 2025)
- ✍️ **Editor**, Rotaract Club of NIBM Kandy (2024 – 2025)
- 💻 **Active Member**, IT Society of NIBM Kandy (2023 – 2025)
- 🎨 Comfortable in Figma and UI/UX design, so I can sit between design and engineering

---

## 📊 `GitHub Analytics`

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=pawanbulathwaththa&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&count_private=true" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pawanbulathwaththa&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117" />

<br/>

<img src="https://streak-stats.demolab.com?user=pawanbulathwaththa&theme=tokyonight&hide_border=true&background=0d1117" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=pawanbulathwaththa&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&row=1&column=7" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=pawanbulathwaththa&bg_color=0d1117&color=6DB33F&line=6DB33F&point=ffffff&area=true&hide_border=true" width="100%"/>

</div>

---

## 📬 `POST /contact`

```http
POST /contact HTTP/1.1
Host: pawanbulathwaththa.github.io
Content-Type: application/json

{
  "name": "Pawan Bulathwaththa",
  "email": "pawanbulatwaththa@gmail.com",
  "linkedin": "linkedin.com/in/pawan-bulathwaththa-99a51733b",
  "portfolio": "pawanbulathwaththa.github.io/my_portfolio",
  "location": "Colombo, Sri Lanka",
  "interests": ["Backend engineering", "Full-stack products", "Cloud-native delivery", "Agentic AI"],
  "message": "Got an interesting problem? Let's build it."
}

HTTP/1.1 200 OK ✅  (typical response time: fast)
```

<div align="center">

<br/>

### ⭐ *"First, solve the problem. Then, write the code."*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6DB33F,50:203a43,100:0f2027&height=140&section=footer&animation=twinkling" width="100%"/>

</div>
