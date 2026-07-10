# Sidnei Domingues

**Desenvolvedor Full Stack — Next.js · TypeScript · Supabase · Orquestração de agentes de IA**

Construí e mantenho uma plataforma healthtech em produção, com usuários reais: **ERP clínico** (Next.js App Router, TypeScript, ~36k linhas de produto, 46 server actions como camada única de escrita, razão teste/produto de 0,54 com Vitest e Playwright) e **assistente com RAG híbrido** (pgvector + keyword, ingestão de documentos com embeddings, transcrição de áudio via Whisper — edge functions em Deno/TypeScript).

Os dois produtos rodam sobre um único Postgres/Supabase: 46 tabelas, 163 políticas de RLS, RBAC via claims de JWT e isolamento entre produtos no mesmo schema. LGPD por design: consentimento registrado, logs de acesso, tokens de acesso externo e retenção legal de áudio (Lei 13.787/2018).

O ritmo — da fundação ao uso real em ~13 semanas — vem de método: um pipeline de desenvolvimento multi-agente que construí sobre o Claude Code, com agentes de permissões segregadas (quem escreve código não faz merge; quem faz QA não implementa), gates adversariais de qualidade, 46 ADRs e enforcement via git hooks. 17 workflows de GitHub Actions fecham o ciclo: CI, auto-merge condicionado e deploy automático.

> **Por que este perfil tem pouco código público?**
> O código de produção (~44k linhas TS/JS) é privado por contrato e por LGPD — é uma plataforma de saúde com dados sensíveis. A arquitetura e os números estão no meu [LinkedIn](https://www.linkedin.com/in/sidnei-domingues); detalhes técnicos posso demonstrar em entrevista.

📫 [LinkedIn](https://www.linkedin.com/in/sidnei-domingues) · dominguessidnei08@gmail.com
