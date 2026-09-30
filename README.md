<a href="https://github.com/RodolfoAAPR">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=58A6FF&vCenter=true&width=560&lines=Ol%C3%A1%2C+eu+sou+o+Rodolfo+%F0%9F%91%8B;AI+Master+%C2%B7+Founder+%C2%B7+Tech+Lead;Full-stack+%C2%B7+TypeScript+%C2%B7+Java;Construindo+produto+com+IA;Balne%C3%A1rio+Cambori%C3%BA-SC+%2F+Maring%C3%A1-PR" alt="Olá, eu sou o Rodolfo · AI Master · Founder · Tech Lead" />
</a>

<img src="assets/banner-sobre.svg" width="100%" alt="Sobre mim: Rodolfo Alves · AI Master · Founder · Tech Lead · Balneário Camboriú-SC / Maringá-PR" />

```ts
const rodolfo = {
  cargo: ["AI Master", "Founder", "Tech Lead"],
  local: "Balneário Camboriú, SC / Maringá, PR",
  stack: {
    web: ["Next.js", "React", "TypeScript"],
    mobile: ["Expo", "React Native"],
    backend: ["Hono", "Node.js", "Java"],
    dados: ["PostgreSQL", "Supabase"],
    ia: ["Claude", "AI SDK", "Agentes"],
  },
  contato: "linkedin.com/in/rodolfoaapr",
} as const;
```

<img src="assets/banner-projeto.svg" width="100%" alt="Construindo agora: marketplace imobiliário · web + mobile + API" />

- Monorepo Turborepo + pnpm
- API type-safe com Hono + Zod
- Postgres com RLS e auditoria
- Web no Cloud Run + app iOS/Android com updates OTA
- E2E de web e mobile no CI
- IA: subagents em paralelo, revisão de código e entregas mais rápidas

<details>
<summary><b>Arquitetura</b></summary>
<br />

```mermaid
flowchart LR
  web["Web · Next.js"] --> api["API · Hono + Zod"]
  app["Mobile · Expo"] --> api
  api --> db[("Postgres · Supabase<br/>RLS + RPCs")]
  api --> ia["IA · Claude / OpenAI"]
  ci["GitHub Actions"] -. deploy .-> run["Cloud Run"]
  ci -. build .-> eas["EAS · lojas"]
```

</details>

<br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts%2Creact%2Cnextjs%2Cnodejs%2Ctailwind%2Csupabase%2Cpostgres%2Cgcp%2Cgithubactions%2Cdocker%2Cjava&theme=dark" />
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,tailwind,supabase,postgres,gcp,githubactions,docker,java&theme=light" alt="TypeScript, React, Next.js, Node.js, Tailwind, Supabase, PostgreSQL, Google Cloud, GitHub Actions, Docker, Java" />
</picture>

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RodolfoAAPR/RodolfoAAPR/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/RodolfoAAPR/RodolfoAAPR/output/github-snake.svg" alt="Cobrinha comendo o gráfico de contribuições" />
</picture>
