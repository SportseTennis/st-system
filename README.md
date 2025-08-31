# Sports & Tennis — Sistema Base (Sem Shopify)

Monorepo inicial para o seu ecossistema: **Web (Next.js/HTML)** + **API (Node/Express)** + **Banco (PostgreSQL)** + **IA (gateway)**.

## Estrutura
- apps/api → API com rotas de produtos, pedidos, pagamentos, ST Match
- apps/web → Painel simples HTML/JS
- infra/docker-compose.yml → PostgreSQL + pgAdmin
- db/schema.sql → Tabelas base
- packages/shared → Tipos/DTOs
- ai/gateway.md → integração com GPT/Llama/Gemini
