# Sports & Tennis — Sistema Base (Pronto para Railway)

Este repositório contém a base do sistema com API + Web + Configurações já preparadas para deploy no Railway.

## Estrutura
- apps/api → API Node/Express (produtos, pedidos, pagamentos, ST Match)
- apps/web → Painel simples HTML/JS conectado à API
- infra/ → docker-compose para Postgres (opcional local)
- db/ → schema.sql com tabelas base
- Procfile → comando de inicialização (usado no Railway)
- .env.example → variáveis de ambiente
