<p align="center">
  <strong>Jarbas Gouveia</strong><br>
  <em>CTO na Ativos Precatórios — construo software que faz mais com menos</em>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jarbasgouveia">LinkedIn</a> ·
  <a href="https://jjgouveia.github.io/">Site</a> ·
  <a href="mailto:gouvik.dev@gmail.com">Email</a>
</p>

CTO e sócio da [Ativos Precatórios](https://github.com/ativos-tecnologia), onde lidero a plataforma **Celer** — SaaS que estrutura a antecipação de precatórios no Brasil — e o **Ativos Intelligence**, nosso assistente de IA multi-agente para operações jurídicas e financeiras.

Comecei há 13+ anos na base do sistema operacional: desenvolvedor Android e mantenedor independente de Custom ROMs — incluindo a CyanogenMod — para o LG P350, portando seis versões do Android para um hardware abandonado pela fabricante. A escola da escassez ainda guia meu critério: **software bom é o que desperdiça menos**.

## O que construo

```text
problema manual  →  automação enxuta  →  dado estruturado  →  decisão de negócio
```

- **Plataformas LegalTech** — SaaS de antecipação de precatórios: precificação, due diligence, CRM, KYC e pagamentos.
- **IA aplicada a dados jurídicos** — orquestração multi-agente (LangGraph), GraphRAG, embeddings e retrieval com grounding sobre documentos jurídicos.
- **Automação de gargalos** — RPAs e integrações que eliminam processo manual onde ele trava negócio. O registro favorito: um RPA que reduziu o recálculo de precatórios de **20 minutos para 2 segundos**.
- **Ferramentas para desenvolvedores** — bibliotecas, extensões e filtros que tiram fricção do dia a dia.

## Na prática: o ecossistema Ativos

- **Celer (API)** — Django 5 / DRF, Celery, Postgres + pgvector, Redis e MongoDB. Domínio em camadas Clean/DDD (`core` puro, `adapters`, infra assíncrona), multi-tenant por host, RBAC híbrido e calendário de prazos judiciais com dias úteis.
- **Ativos Intelligence** — assistente de IA construído sobre **LangGraph**: registro de agentes (chat/evento/agendamento), roteamento de grafos, GraphRAG com reranker, cache semântico, *grounding guard* contra alucinação, modo sombra para rollout seguro e **gates de regressão com golden sets** validando cada release de agente antes de ir a produção.
- **CelerApp (front)** — Next.js App Router / React 19 / TypeScript, React Query, Cypress e quality gate de build.
- **Nexo** — substituto interno do Dropbox: NestJS, Prisma, Socket.io, RBAC hierárquico, compartilhamento e auditoria LGPD-compliant.
- **Ativos Finance** — backend NestJS + Prisma para o financeiro interno (ledger, contas, conciliação), integrado ao Celer via contrato de Operações.
- **Tasker** — MCP server HTTP construído sobre o **Page Comparison Tool** (ferramenta interna da Ativos, similar ao Linear, para especificação visual de mudanças em telas). Expondo tarefas para agentes de IA de qualquer repo: 8 ferramentas (leitura, comentário, conclusão), autenticação por PAT com hash SHA-256, botões de instalação de 1 clique para Cursor e Claude Code, e deploy remoto no mesmo domínio do app.

## Portal OAB-PE

Portal co-branded da Ativos com a Ordem dos Advogados do Brasil de Pernambuco: ponto centralizado para advogados pernambucanos consultarem, calcularem e resolverem dúvidas sobre precatórios — com suporte especializado em imposto de renda e agendamento direto. 4 módulos MVP: Calculadora de valor líquido (integração API Ativos), Tickets "Tirar Dúvida" (categorias jurídicas, protocolo, e-mail automático), Agendamento IR (slots 15 min, Cal.com self-hosted no Railway, invite de calendário), Biblioteca de materiais (grid por categoria, CMS via Notion/Airtable, rastreamento GA4). Arquitetura em 3 repositórios: backend Django 5.2/DRF (`api-celer/portal_oab`) com modelo dedicado de ticket, identidade e magic link; landing e área pública em repo próprio Next.js 16.3 + React 19.2 + NextAuth v5 + Tailwind 4 + Three.js (`Ativos-Labs/portal-oab-ativos`, deploy Vercel); dashboard autenticado no app principal Next.js 16 + React 19, TanStack Query, Zustand, Radix UI (`ativos-cvld-front`). Co-branding OAB-PE / Ativos: logo OAB-PE primário, "powered by Ativos" secundário, paleta branca/azul institucional, tipografia Inter, desktop-first.

## Open source & pacotes

- **[show-react](https://www.npmjs.com/package/show-react)** — renderização condicional declarativa no JSX, sem excesso de ternários e `&&`.
- **[maestro-express-async-errors](https://www.npmjs.com/package/maestro-express-async-errors)** — camada segura de tratamento de erros assíncronos para middlewares Express.
- **[Poetry Syntax Highlight](https://marketplace.visualstudio.com/items?itemName=jjgouveia.poetry-syntax-highlight)** — syntax highlighting de `pyproject.toml` para VS Code, construída com TextMate grammars durante o desenvolvimento do backend do Celer.
- **[Manda Jobs](https://github.com/jjgouveia/mandajobs)** — filtro inteligente de vagas do LinkedIn com geração de queries booleanas.

### Contribuições

- **[pittaya-ui/ui](https://github.com/pittaya-ui/ui)** — principal contribuidor (65+ contribuições): componentes no registry, comando `remove` da CLI, sistema de styles/themes e schema de validação do registry.
- **[Pittaya UI](https://github.com/jjgouveia?tab=repositories&q=pittaya)** — biblioteca de componentes React/Next.js.

## Trajetória

**Ativos Precatórios** (CTO & sócio) ← **bementor** (full stack: NestJS, Prisma, CI/CD, performance React) ← **Skill Labs** (sócio & CTO) ← **Programador.TV** (ASP.NET) ← **LG P350 custom ROMs** (onde tudo começou).

## Stack

`Python` · `Django/DRF` · `LangGraph` · `RAG/GraphRAG` · `pgvector` · `TypeScript` · `NestJS` · `Prisma` · `React/Next.js` · `Celery` · `PostgreSQL` · `Redis` · `MongoDB` · `Docker`

---

### 📈 Estatísticas

| GitHub Stats | Top Languages |
|---|---|
| ![GitHub stats](https://github-readme-stats-one-virid-55.vercel.app/api?username=jjgouveia&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=jolly) | ![Top Languages](https://github-readme-stats-one-virid-55.vercel.app/api/top-langs/?username=jjgouveia&langs_count=10&include_all_commits=true&hide_border=true&theme=jolly&layout=compact) |

![GitHub Streak](https://streak-stats.demolab.com?user=jjgouveia&theme=synthwave&locale=pt_BR)

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/wakatime?username=gouvik&layout=compact&card_width=300" />
</a>

---

<div align="center">
  <a href="https://www.linkedin.com/in/jarbasgouveia"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://api.whatsapp.com/send?phone=5581996122536"><img src="https://img.shields.io/badge/-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"></a>
  <a href="mailto:gouvik.dev@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.instagram.com/junior_gouveia/"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</div>

Recife, Brasil
