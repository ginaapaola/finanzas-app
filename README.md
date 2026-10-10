# Finanzas App

Aplicación móvil de finanzas personales para registrar ingresos, egresos y deudas.

## Stack
- API: NestJS + TypeScript
- Base de datos: PostgreSQL (Docker)
- Móvil: React Native + Expo (próximamente)

## Cómo levantar el proyecto
1. `docker compose up -d`
2. `pnpm install`
3. Copia `apps/api/.env.example` a `apps/api/.env`
4. `pnpm --filter api start:dev`