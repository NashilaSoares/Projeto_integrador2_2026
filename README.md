# time-platform

Sistema de controle de ponto e apontamento de horas. Monorepo TurboRepo: `apps/api` (Fastify), `apps/web` (Next.js), `packages/database` (Prisma), `packages/shared` (validações Zod).

## Desenvolvimento

```bash
cp .env.example .env
docker compose up
```

- Web: http://localhost:3000
- API: http://localhost:3001/api/v1/health

## Seed

`npm run db:seed` popula usuários, projetos e apontamentos de exemplo (mesmos dados do mockup original).

Contas de desenvolvimento (senha: `time123`):

- `marina@time.co` — Desenvolvedora
- `rafael@time.co` — Designer

`julia@time.co` fica com status de convite pendente (sem senha) para testar o fluxo de aceite de convite.

> Senha de seed apenas para desenvolvimento — nunca usar em produção.
