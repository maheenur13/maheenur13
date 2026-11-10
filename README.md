<!-- ═══════════════════════ HEADER ═══════════════════════ -->
<div align="center">
  <img src="assets/header.svg" width="100%" alt="terminal banner — Jahidun Nur Mahee, Software Engineer @ Strativ AB"/>

  <!-- rotating prompt tagline -->
  <img src="assets/tagline.svg" width="720" alt="❯ Software Engineer @ Strativ AB · Founder &amp; CEO @ Ternion Loop · Building Sports Loop"/>

  <br/>

  <!-- terminal-path badges -->
  <a href="https://www.maheenur13.dev">
    <img src="https://img.shields.io/badge/~%2Fmaheenur13.dev-visit-00C9A7?style=for-the-badge&labelColor=161B22&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.maheenur13.dev/workflow">
    <img src="https://img.shields.io/badge/~%2Fworkflow-how_I_work-6C63FF?style=for-the-badge&labelColor=161B22" alt="My workflow"/>
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
  readonly uptime = "5 years in production";
  readonly motto = "I code everyday! ^_^";

  async currentFocus(): Promise<Focus[]> {
    return [
      "LLM products on Claude 🤖",
      "RAG: chunking, embeddings, pgvector",
      "MCP: connecting AI tools to real data",
      "System design & microservices",
    ];
  }

  @Get("/stack")
  stack(): TechStack {
    return {
      frontend: ["TypeScript", "React", "Next.js"],
      backend: ["Node.js", "NestJS", "PostgreSQL", "Redis"],
      mobile: ["React Native", "Expo"],
      ai: ["Claude", "OpenAI", "Groq", "MCP", "RAG"],
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
  🥇 Employee of the Year, APSIS Solutions (top 1%) · 2023
  🏅 Employee of the Quarter, APSIS Solutions (top 2%) · 2022
  🏆 3rd place, Inter-University Programming Contest (Take Off)
  🧩 250+ problems solved on LeetCode & Beecrowd
  🌐 portfolio → https://www.maheenur13.dev
```

<br clear="right"/>

<!-- ═══════════════════════ EXPERIENCE ═══════════════════════ -->
## 💼 `$ git log --career`

```console
$ git log --career --oneline --graph

* e7d19f3 (feature/startup) Founder & CEO · Ternion Loop 🚀
│          shipping Sports Loop 🏟️ — our first product, live on Google Play
│
* a4f2b1c (HEAD -> main, origin/stockholm) Software Engineer · Strativ AB 🇸🇪
│          Aug 2024 → present
│          · context engine: RAG knowledge base over every project, answers with Claude, now sold to clients
│          · MCP connections between AI tools and internal knowledge bases
│          · Strativ Greenroom: AI interviewer used for candidate screening
│          · Alent Dynamic (industrial IoT for sawmills), Chefry, Biap (App Store)
│
* 9c8e3d2 (dhaka) Software Engineer · APSIS Solutions Ltd 🇧🇩
│          Jun 2022 → Aug 2024
│          · led 8 frontend developers on an ERP for IFIC Bank, BRAC University, Prime Bank
│          · ERP mobile apps (React Native + Expo), Storybook component library as an npm package
│
* 1f0a7e5 (dhaka) Junior Software Engineer · Zaynax Ltd 🇧🇩
           Aug 2021 → Jul 2022 · Next.js component library · e-commerce admin & seller dashboards

$ # 5 years committed, zero force-pushes to production 😌
```

<!-- ═══════════════════════ WORKFLOW ═══════════════════════ -->
## 🧭 `$ cat ~/workflow`

I built **Wayline**, my own app for learning and shipping, on an Android phone and a Windows laptop. Its backend is my portfolio.

```console
$ wayline --how-it-works
  📱 Android (Expo)  ┐
  🖥️  Windows (Electron)├──▶  maheenur13.dev (Next.js + Payload + Postgres)
  🎙️ voice assistant  ┘            │
                                     ├──▶ Groq · Workers AI   (assistant, memory, drafts)
                                     ├──▶ /learning · /notes  (what I'm learning, in public)
                                     └──▶ LinkedIn             (posts, after I approve them)

$ wayline --loop
  plan → focus → practice → review → share   # one app, $0 a month on free tiers
```

<sub>Full diagram and the weekly loop → <a href="https://www.maheenur13.dev/workflow">maheenur13.dev/workflow</a></sub>

<!-- ═══════════════════════ TECH STACK ═══════════════════════ -->
## 🛠️ `$ npx mahee --stack`

<div align="center">

### `~/frontend`
<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,redux,tailwind,svelte,vite,html,css&theme=dark" alt="frontend"/>

<sub>+ Ant Design • shadcn/ui • Zustand • Redux Toolkit • TanStack Query • Socket.io • Playwright</sub>

### `~/backend`
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,redis,python&theme=dark" alt="backend"/>

<sub>+ Microservices • REST • gRPC • WebSocket • Zod • queues & background jobs • Stripe</sub>

### `~/ai-llm` 🤖
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude"/> <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/> <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" alt="Groq"/> <img src="https://img.shields.io/badge/MCP-111111?style=for-the-badge&logoColor=white" alt="MCP"/> <img src="https://img.shields.io/badge/RAG_Pipelines-6C63FF?style=for-the-badge" alt="RAG"/> <img src="https://img.shields.io/badge/pgvector_%26_Embeddings-00C9A7?style=for-the-badge" alt="pgvector and embeddings"/>

<sub>knowledge bases • AI interviewer • tool calling • streaming • prompt engineering</sub>

### `~/databases`
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma,supabase,sequelize&theme=dark" alt="databases"/>

<sub>+ Mongoose • NeonDB • SQL</sub>

### `~/mobile-desktop`
<img src="https://skillicons.dev/icons?i=react,electron&theme=dark" alt="mobile and desktop"/>

<sub>React Native • Expo • EAS builds & OTA updates • Electron</sub>

### `~/devops-tools`
<img src="https://skillicons.dev/icons?i=docker,aws,cloudflare,vercel,git,github,vscode,postman&theme=dark" alt="devops and tools"/>

<sub>+ CI/CD • Railway • Sentry • Supabase Edge Functions • Cursor • Claude Code</sub>

</div>

<!-- ═══════════════════════ FEATURED PROJECTS ═══════════════════════ -->
## 🚀 `$ ls ~/projects --featured`

| Project | Description | Tech |
|---------|-------------|------|
| 🧠 **[Strativ Context Engine](https://www.maheenur13.dev/projects/strativ-context-engine)** | AI knowledge base over project data, meeting notes and docs; answers with Claude, reached from AI tools through MCP. Now sold to clients | RAG • pgvector • Claude • MCP |
| 🏟️ **[Sports Loop](https://www.maheenur13.dev/projects/sports-loop)** | Sports community app: matchmaking, chat, venues on a map, live cricket scores. iOS, Android and web from one codebase | Expo • NestJS microservices • PostgreSQL • Redis |
| 📄 **[TernCV](https://terncv.vercel.app)** | Free ATS resume builder in the browser, no account. PDFs carry their data for re-import | React 19 • Vite • @react-pdf • Web Crypto |
| 📝 **[Prompt Grade](https://www.maheenur13.dev/projects/prompt-grade)** | Teachers describe a quiz in plain words; an LLM builds it and grades the answers with feedback | React • Express • MongoDB • Groq |
| ⚙️ **[Alent Dynamic](https://www.maheenur13.dev/projects/alent-dynamic)** | Industrial IoT for Swedish sawmills: monitor and control wood-drying kilns in real time | React • real-time data |
| 🧭 **[Wayline](https://www.maheenur13.dev/workflow)** | My own learning and shipping app: Android + Windows, voice assistant, LinkedIn drafts, on my portfolio's backend | Expo • Electron • Next.js • Payload |

<sub>More case studies → <a href="https://www.maheenur13.dev/#projects">maheenur13.dev/#projects</a></sub>

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

  <a href="https://www.maheenur13.dev">
    <img src="https://img.shields.io/badge/-Visit%20maheenur13.dev-00C9A7?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/differentmahee13/">
    <img src="https://img.shields.io/badge/-Reach%20out%20on%20LinkedIn-6C63FF?style=for-the-badge&logo=linkedin&logoColor=white" alt="Reach out"/>
  </a>

  <br/>

  <img src="assets/footer.svg" width="100%" alt="VS Code status bar footer"/>
</div>
