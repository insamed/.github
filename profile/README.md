<p align="center">
  <img src="https://img.shields.io/badge/status-in%20development-blue" alt="In development" />
  <img src="https://img.shields.io/badge/built%20for-Indonesian%20pharmacies-red" alt="Built for Indonesian pharmacies" />
  <img src="https://img.shields.io/badge/license-proprietary-lightgrey" alt="Proprietary software" />
</p>

## Insamed Indonesia

**Pharmacy management for independent apotek and pharmacy chains in Indonesia.**

Insamed brings sales, prescriptions, inventory, purchasing, and owner oversight into one application. We build around everyday pharmacy work, with familiar Indonesian terms and clear workflows for staff with different levels of software experience.

[Visit insamed.id](https://insamed.id/)

### What we're building

- **Sales and prescriptions** — OTC checkout, prescription dispensing, racikan, labels, receipts, and returns.
- **Stock control** — batch and expiry tracking, FEFO allocation, unit conversions, branch transfers, and stock opname.
- **Purchasing** — defekta, purchase orders, goods receiving, supplier invoices, and payments.
- **Daily operations** — cash-register sessions, staff permissions, branch management, and reports.
- **Account and platform administration** — onboarding, invitations, account recovery, and subscription management.

### What guides the work

- **Clear workflows:** readable screens, useful feedback, and ways to recover from mistakes.
- **Scoped access:** pharmacy and branch boundaries, with permissions resolved on the server.
- **Traceable records:** stock movements, payment records, and audit history preserve the record of changes.
- **Exact money:** integer rupiah throughout financial calculations.
- **Focused scope:** software for pharmacy operations, shaped by the people who use it.

### Technology

TypeScript, Next.js and React, NestJS with Fastify, PostgreSQL with Drizzle, Redis and BullMQ, and Zod validation. Vitest and Playwright support behavior and workflow checks.

The application is a modular monolith in a Turborepo workspace, designed for a small team to maintain.
