<!-- ═══════════════════════ HEADER ═══════════════════════ -->
<div align="center">
  <img src="assets/header.svg" width="100%" alt="terminal banner — Jahidun Nur Mahee, Software Engineer @ Strativ AB"/>

  <!-- rotating prompt tagline -->
  <img src="assets/tagline.svg" width="720" alt="❯ Software Engineer @ Strativ AB · Founder &amp; CEO @ Ternion Loop · Building Sports Loop"/>

  <br/>

  <!-- terminal-path badges -->
  <a href="https://jahidun-nur-mahee.vercel.app">
    <img src="https://img.shields.io/badge/~%2Fportfolio-visit-00C9A7?style=for-the-badge&labelColor=161B22&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/differentmahee13/">
    <img src="https://img.shields.io/badge/~%2Flinkedin-connect-0A66C2?style=for-the-badge&labelColor=161B22&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/maheenur13?tab=followers">
    <img src="https://img.shields.io/github/followers/maheenur13?style=for-the-badge&labelColor=161B22&logo=github&label=~%2Ffollowers&color=6C63FF" alt="GitHub followers"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=maheenur13&style=for-the-badge&color=6c63ff&label=~%2Fviews" alt="profile views"/>

</div>

<br/>

<!-- ═══════════════════════ ABOUT ME ═══════════════════════ -->
## 💻 `$ whoami`

<img align="right" width="360" src="assets/whoami.svg" alt="animated dev-musician avatar — Mahee coding with headphones on"/>

```typescript
// mahee.service.ts — running since 2021, zero downtime ☕

@Injectable({ scope: Scope.DEFAULT }) // always available
export class Mahee extends SoftwareEngineer implements Musician {
  readonly company = "Strativ AB 🇸🇪";
  readonly startup = "Ternion Loop — Founder & CEO 🚀";
  readonly firstProduct = "Sports Loop 🏟️";
  readonly base = "Dhaka, Bangladesh 🇧🇩";
  readonly uptime = "4+ years in production";
  readonly motto = "I code everyday! ^_^";

  async currentFocus(): Promise<Focus[]> {
    return ["AI & LLM apps 🤖", "RAG pipelines", "Microservices", "DevOps"];
  }

  @Get("/stack")
  stack(): TechStack {
    return {
      frontend: ["TypeScript", "React", "Next.js"],
      backend: ["Node.js", "NestJS", "PostgreSQL", "Redis"],
      mobile: ["React Native", "Expo"],
    };
  }

  @Cron("*/60 * * * *") // hourly, non-negotiable
  refuel(): Coffee { return new Coffee({ size: "large" }); }

  @OnEvent("work.done")
  unwind(): Music {
    return this.play("guitar 🎸") ?? this.produce("FL Studio 🎹");
  }
}
```

```console
$ mahee --achievements
  🏆 3rd place — Inter-University Programming Competition
  🧩 260+ problems solved on LeetCode & Beecrowd
  🌐 portfolio → https://jahidun-nur-mahee.vercel.app
```

<br clear="right"/>

<!-- ═══════════════════════ EXPERIENCE ═══════════════════════ -->
## 💼 `$ git log --career`

```console
$ git log --career --oneline --graph

* e7d19f3 (feature/startup) Founder & CEO · Ternion Loop 🚀
│          shipping Sports Loop 🏟️ — our first product
│
* a4f2b1c (HEAD -> main, origin/stockholm) Software Engineer · Strativ AB 🇸🇪
│          Aug 2024 → present · scalable web apps · code reviews · mentoring
│
* 9c8e3d2 (dhaka) Software Engineer · APSIS Solutions Ltd 🇧🇩
│          Jun 2022 → Jul 2024 · full-stack apps · microservices · performance
│
* 1f0a7e5 (dhaka) Junior Software Engineer · Zaynax Ltd 🇧🇩
           Aug 2021 → Jun 2022 · responsive web apps · REST APIs · agile

$ # 4+ years committed, zero force-pushes to production 😌
```

<!-- ═══════════════════════ TECH STACK ═══════════════════════ -->
## 🛠️ `$ npx mahee --stack`

<div align="center">

### `~/frontend`
<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,redux,tailwind,materialui,bootstrap,html,css&theme=dark" alt="frontend"/>

<sub>+ Ant Design • Redux Toolkit • Zustand • Recoil • TanStack Query • Socket.io</sub>

### `~/backend`
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,redis&theme=dark" alt="backend"/>

<sub>+ Microservices • Zod • REST APIs • Authentication & Authorization</sub>

### `~/ai-llm` 🤖
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/> <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude"/> <img src="https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logoColor=white" alt="DeepSeek"/> <img src="https://img.shields.io/badge/RAG_Pipelines-6C63FF?style=for-the-badge" alt="RAG"/> <img src="https://img.shields.io/badge/Embeddings_%26_Vector_Search-00C9A7?style=for-the-badge" alt="Embeddings"/>

<sub>LLM-powered apps • chatbots • tool calling • content engines • document extraction</sub>

### `~/databases`
<img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,prisma,sequelize&theme=dark" alt="databases"/>

<sub>+ Mongoose • SQL</sub>

### `~/mobile-desktop`
<img src="https://skillicons.dev/icons?i=react,electron&theme=dark" alt="mobile and desktop"/>

<sub>React Native • Expo • iOS Development • Electron.js</sub>

### `~/devops-tools`
<img src="https://skillicons.dev/icons?i=docker,cloudflare,vercel,git,github,vscode,postman&theme=dark" alt="devops and tools"/>

<sub>+ Railway • Cursor • Husky • Prettier • ESLint • Jira • ClickUp • cPanel</sub>

</div>

<!-- ═══════════════════════ FEATURED PROJECTS ═══════════════════════ -->
## 🚀 `$ ls ~/projects --featured`

| Project | Description | Tech |
|---------|-------------|------|
| 🏟️ **Sports Loop** | Ternion Loop's first product — as Founder & CEO 🚀 | TypeScript |
| ⚙️ **Alent Dynamic** | Industrial IoT system for real-time monitoring & control of manufacturing processes | React.js • Node.js • MQTT • PostgreSQL • Redis |
| 🧠 **Content Engine (RAG)** | Retrieval-Augmented Generation pipeline for AI-powered content generation & semantic search | TypeScript • LLMs • Embeddings • Vector DB |
| 🤖 **[AI Invoice Extractor](https://github.com/maheenur13/ai-invoice-extractor)** | LLM-powered invoice data extraction | TypeScript |
| 💬 **[LLM Chatbot](https://github.com/maheenur13/llm-chatbot)** | Full-stack AI chatbot ([backend](https://github.com/maheenur13/chatbot-backend)) | TypeScript |
| 📄 **[Resume Builder](https://github.com/maheenur13/resume-builder)** | Modern resume building tool | TypeScript |

<!-- ═══════════════════════ GITHUB STATS ═══════════════════════ -->
## 📊 `$ git stats --all-time`

<div align="center">

  <img height="180" src="https://github-readme-stats.vercel.app/api?username=maheenur13&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats"/>
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=maheenur13&theme=tokyonight&hide_border=true&bg_color=00000000&layout=compact&langs_count=8" alt="Top languages"/>

  <br/><br/>

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=maheenur13&theme=tokyonight&hide_border=true&background=00000000" alt="GitHub streak"/>

  <br/><br/>

  <img src="https://github-readme-activity-graph.vercel.app/graph?username=maheenur13&theme=tokyo-night&hide_border=true&bg_color=00000000&color=6C63FF&line=00C9A7&point=FFFFFF&area=true" width="95%" alt="Contribution graph"/>

</div>

<!-- ═══════════════════════ TROPHIES ═══════════════════════ -->
## 🏆 `$ gh trophies --unlock-all`

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=maheenur13&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" alt="trophies"/>
</div>

<!-- ═══════════════════════ SNAKE ═══════════════════════ -->
## 🐍 `$ ./snake --eat contributions`

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maheenur13/maheenur13/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/maheenur13/maheenur13/output/github-contribution-grid-snake.svg"/>
    <img src="https://raw.githubusercontent.com/maheenur13/maheenur13/output/github-contribution-grid-snake.svg" alt="snake animation" width="95%"/>
  </picture>
</div>

<!-- ═══════════════════════ QUOTE ═══════════════════════ -->
## ✍️ `$ fortune --dev`

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="dev quote"/>
</div>

<!-- ═══════════════════════ FOOTER ═══════════════════════ -->
<div align="center">

  ### 🤝 `$ mahee --connect`

  <sub>establishing connection… let's build something great together</sub>
  <br/><br/>

  <a href="https://jahidun-nur-mahee.vercel.app">
    <img src="https://img.shields.io/badge/-Visit%20My%20Portfolio-00C9A7?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/differentmahee13/">
    <img src="https://img.shields.io/badge/-Reach%20out%20on%20LinkedIn-6C63FF?style=for-the-badge&logo=linkedin&logoColor=white" alt="Reach out"/>
  </a>

  <br/>

  <img src="assets/footer.svg" width="100%" alt="VS Code status bar footer"/>
</div>
