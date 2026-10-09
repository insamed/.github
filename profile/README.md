# Insamed Indonesia

**A workspace for Indonesian pharmacies.**

Insamed brings sales, inventory, prescriptions, purchasing, and teams into one system for independent apotek and pharmacy chains. Clear records help staff see what has happened, understand the current stage of work, and continue where the previous person left off.

[Website](https://insamed.id/) · [Open Insamed](https://app.insamed.id/) · [Guides](https://insamed.id/panduan)

## Pharmacy operations

- **Sales and cash:** OTC checkout, payments, receipts, returns, and cash-register sessions.
- **Inventory:** batch and expiry tracking, FEFO allocation, unit conversions, branch transfers, and stock opname.
- **Prescriptions:** intake, racikan, dispensing, labels, and handover in a shared workflow.
- **Purchasing and suppliers:** defekta, purchase orders, goods receiving, supplier invoices, and payments.
- **Business oversight:** sales, margins, stock needing attention, and reports across branches.
- **Teams:** access follows each person's role and assigned branches.

## Clear records, connected teams

Transaction and stock records stay available for review. Drafts, goods receipts, and prescription handovers show distinct stages of work. Owners can follow each branch from a shared business view, while staff work with familiar Indonesian pharmacy terms.

## Technology

TypeScript, Next.js and React, NestJS with Fastify, PostgreSQL with Drizzle, Redis and BullMQ, and Zod validation. Vitest and Playwright support behavior and workflow checks.

The application uses a modular monolith in a Turborepo workspace. Pharmacy and branch access is scoped on the server, financial calculations use integer rupiah, and stock movements, payments, and audit records preserve operational history.
