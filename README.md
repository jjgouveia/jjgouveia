<p align="center">
  <strong>Jarbas Gouveia Jr</strong><br>
  <em>CTO na Ativos Precatórios · engenharia moldada na escassez, dos 140MB do LG P350 à escala judicial</em>
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
- **IA aplicada a dados jurídicos** — orquestração multi-agente, GraphRAG, embeddings e retrieval com grounding sobre documentos jurídicos.
- **Automação de gargalos** — RPAs e integrações que eliminam processo manual onde ele trava negócio. O registro favorito: um RPA que reduziu o recálculo de precatórios de **20 minutos para 2 segundos**.
- **Ferramentas para desenvolvedores** — bibliotecas, extensões e filtros que tiram fricção do dia a dia.

## Na prática: o ecossistema Ativos

- **Celer (API)** — Django 5 / DRF, Celery, Postgres + pgvector, Redis e MongoDB. Domínio em camadas Clean/DDD (`core` puro, `adapters`, infra assíncrona), multi-tenant por host, RBAC híbrido e calendário de prazos judiciais com dias úteis.
- **Ativos Intelligence** — assistente de IA construído sobre **LangGraph**: registro de agentes (chat/evento/agendamento), roteamento de grafos, GraphRAG com reranker, cache semântico, *grounding guard* contra alucinação, modo sombra para rollout seguro e **gates de regressão com golden sets** validando cada release de agente antes de ir a produção.
- **CelerApp (front)** — Next.js App Router / React 19 / TypeScript, React Query, Cypress e quality gate de build.
- **Nexo** — substituto interno do Dropbox: NestJS, Prisma, Socket.io, RBAC hierárquico, compartilhamento e auditoria LGPD-compliant.
- **Ativos Finance** — backend NestJS + Prisma para o financeiro interno (ledger, contas, conciliação), integrado ao Celer via contrato de Operações.

## Produtos e open source

- **[show-react](https://www.npmjs.com/package/show-react)** — renderização condicional declarativa no JSX, sem excesso de ternários e `&&`.
- **[Poetry Syntax Highlight](https://marketplace.visualstudio.com/items?itemName=jjgouveia.poetry-syntax-highlight)** — syntax highlighting de `pyproject.toml` para VS Code, construída com TextMate grammars durante o desenvolvimento do backend do Celer.
- **[Manda Jobs](https://github.com/jjgouveia/mandajobs)** — filtro inteligente de vagas do LinkedIn com geração de queries booleanas.
- **Pittaya UI** — biblioteca de componentes React.
- **Emojify** — transformação de fotos em mosaicos de emojis.

## Trajetória

**Ativos Precatórios** (CTO & sócio) ← **bementor** (full stack: NestJS, Prisma, CI/CD, performance React) ← **Skill Labs** (sócio & CTO) ← **Programador.TV** (ASP.NET) ← **LG P350 custom ROMs** (onde tudo começou).

## Stack

`Python` · `Django/DRF` · `LangGraph` · `RAG/GraphRAG` · `pgvector` · `TypeScript` · `NestJS` · `Prisma` · `React/Next.js` · `Celery` · `PostgreSQL` · `Redis` · `MongoDB` · `Docker`

---

Recife, Brasil · [LinkedIn](https://www.linkedin.com/in/jarbasgouveia) · [gouvik.dev@gmail.com](mailto:gouvik.dev@gmail.com)
